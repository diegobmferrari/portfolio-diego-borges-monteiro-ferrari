# Security Specification - AmebaMaker

## 1. Data Invariants
- An Ameba document cannot exist without a valid `userId` matching the creator's UID.
- `createdAt` must be established at creation and never modified.
- `updatedAt` must be updated on every write to the current server time.
- Field `isActive` determines if an ameba is "active" in the user's view, but can only be modified by the owner or an admin.
- Resource constraints: `name` must be 1-100 characters. `path` must be a valid SVG path string.

## 2. The Dirty Dozen Payloads
1. **Identity Theft**: Creating an ameba with a `userId` belonging to someone else.
2. **Ghost Update**: Attempting to update `userId` of an existing ameba.
3. **Immortality Hack**: Attempting to change the `createdAt` timestamp after creation.
4. **Data Poisoning**: Setting `complexity` to `Infinity` or a very large number.
5. **Admin Spoofing**: Attempting to write to the `/admins/` collection.
6. **Anonymous Vandalism**: Attempting to write without being signed in.
7. **Cross-User Leak**: Attempting to read an ameba where `userId` != `request.auth.uid`.
8. **Shadow Field Injection**: Adding a `isAdmin: true` field to the ameba document.
9. **Email Spoofing**: Bypassing `email_verified` check if required.
10. **State Skipping**: Manually setting terminal states if any existed.
11. **Resource Exhaustion**: Sending a 1MB string for the `name` field.
12. **Orphaned Writes**: Creating an ameba that doesn't link to a real user profile (if we had a users collection).

## 3. Test Runner
(See `firestore.rules.test.ts` for implementation)
