# 🧠 Análise de Viés e Curadoria Humana em Classificação Visual por IA

## 📝 Descrição do Projeto
Este projeto documenta um experimento prático focado na identificação de viés de amostragem em modelos de aprendizado de máquina e no desenvolvimento de estratégias de mitigação baseadas em abordagens **Human-in-the-loop (HITL)**. Utilizando a plataforma Teachable Machine, foi construído um classificador visual para analisar como conjuntos de dados restritos afetam a generalização do algoritmo.

O laboratório explora o impacto ético e psicossocial gerado por sistemas enviesados, propondo um arcabouço estruturado de curadoria humana diversificada aplicável antes e depois do treinamento de modelos preditivos.

![Figura 1: Interface do Teachable Machine demonstrando o treinamento com classes desbalanceadas](https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=800&q=80)
*Figura 1: Exemplo ilustrativo de fluxo de treinamento de modelos de visão computacional.*

---

## 🔬 O Experimento: Teachable Machine
O modelo foi configurado com duas classes de imagem distintas utilizando amostragem de rostos:
* **Classe 1:** Usuário Leigo
* **Classe 2:** Gênio da Tecnologia

### Configurações de Hiperparâmetros Utilizadas:
* **Épocas (Epochs):** 200
* **Tamanho do Lote (Batch Size):** 32
* **Taxa de Aprendizado (Learning Rate):** 0.001

O resultado do teste revelou o comportamento clássico de um algoritmo exposto a um viés de amostragem: ao analisar dados restritos, ele aprende padrões incompletos e passa a generalizar essas correlações superficiais como verdades absolutas, falhando ao classificar novos perfis na etapa de visualização.

---

## 🚀 Tecnologias e Ferramentas Utilizadas
* **Plataforma Core:** Teachable Machine (Google)
* **Conceitos Computacionais:** Visão Computacional, Redes Neurais Convolucionais, Ajuste de Hiperparâmetros.
* **Metodologia de Governança:** Human-in-the-loop (HITL).

---

## 🎨 Impactos Identificados e Estratégia de Intervenção

### Consequências do Viés Algorítmico:
* **Distorção de Realidade:** Decisões automatizadas baseadas em correlações errôneas.
* **Impacto Emocional:** Geração de sentimentos de exclusão, invisibilidade, frustração e queda de autoestima em grupos marginalizados.
* **Prejuízo Profissional:** Perda real de oportunidades e estagnação na carreira ao perpetuar desigualdades históricas.

### Plano de Mitigação Human-in-the-loop Proposto:
O projeto detalha 5 etapas essenciais de intervenção humana para garantir a equidade do sistema:
[ Coleta de Dados ]

▼
  1. Comitê Plural: Revisão por perfis diversos         

  2. Auditoria: Ajuste de grupos sub-representados     

  3. Rotulagem Ética: Diretrizes para evitar viés       


▼
[ Treinamento da IA ]

▼

 4. Validação Cruzada: Múltiplas revisões humanas     

 5. Feedback Contínuo: Ajustes pós-implementação    



1. **Comitê Plural:** Formação de um grupo com diferentes perfis sociais, acadêmicos e culturais para auditar os dados brutos.
2. **Auditoria de Representatividade:** Análise minuciosa para detectar e corrigir a ausência de grupos minoritários na amostra.
3. **Rotulagem Ética:** Aplicação de diretrizes rigorosas durante a classificação dos dados para remover subjetividades nocivas.
4. **Validação Cruzada Humana:** Revisão compartilhada de amostras por diferentes pessoas para anular vieses individuais.
5. **Feedback Contínuo:** Sistema pós-implementação baseado em relatos reais dos usuários para correções rápidas em produção.

---

## 🔧 Como Replicar este Laboratório
1. Acesse o portal do Teachable Machine.
2. Crie um projeto de Imagem (Image Project).
3. Adicione duas classes e utilize amostras de rostos que induzam propositalmente o modelo ao erro para testar seus limites de generalização.
4. Configure os hiperparâmetros de acordo com a seção do experimento acima e execute o treinamento.

---
[Voltar ao início](https://github.com/diegobmferrari//diegobmferrari/)
