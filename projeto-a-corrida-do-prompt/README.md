# 🚀 A Corrida do Prompt: Experimentos com Engenharia de Prompt e IA Generativa

## 📝 Descrição do Projeto
[cite_start]Este projeto consiste em um laboratório prático e documental sobre **Engenharia de Prompt (Prompt Engineering)** aplicada a modelos de IA generativa de imagem (como DALL-E integrado ao ChatGPT)[cite: 1, 4, 13]. [cite_start]O objetivo principal é explorar como modificações iterativas em instruções textuais impactam a composição visual, a precisão estilística e a renderização de elementos complexos de fundo e iluminação[cite: 8, 14, 17].

[cite_start]Desenvolvido como um registro de experimentação técnica, o projeto demonstra o processo de refinamento de um conceito criativo surrealista: um músico astronauta executando um instrumento clássico em um cenário marciano, progredindo de um sujeito humano para variações com animais e cenários de fundo catastróficos altamente detalhados[cite: 4, 13, 17, 22].

![Figura 1: Evolução da geração de imagem a partir do refinamento de prompt estilo Barroco](https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=800&q=80)
*Figura 1: Representação abstrata do processo iterativo de criação e refinamento visual por IA.*

---

## 🔬 Linha do Tempo e Iteração de Prompts

[cite_start]O projeto documenta a evolução de quatro prompts principais, avaliando o comportamento da IA perante estilos históricos (Barroco) e elementos de iluminação (*Chiaroscuro*)[cite: 8, 14].

| Etapa | Prompt Utilizado | Foco do Teste / Variáveis | Resultado Observado |
| :--- | :--- | :--- | :--- |
| **01** | [cite_start]`"Uma imagem de um astronauta estilo barroco tocando violoncelo em Marte"` [cite: 4] | [cite_start]Validação inicial de estilo e conceito base[cite: 4]. | [cite_start]Composição sólida, centralizada e paleta quente[cite: 8]. |
| **02** | [cite_start]`"Um rato astronauta tocando violoncelo em Marte e a lua explodindo de fundo, estilo pintura barroca, iluminação dramática com chiaroscuro..."` [cite: 13, 14] | [cite_start]Alteração do sujeito principal (humano para animal) e adição de evento dinâmico de fundo[cite: 4, 13]. | [cite_start]Substituição com sucesso para camundongo; iluminação dramática bem aplicada[cite: 14, 15]. |
| **03** | [cite_start]`"Um gorila astronauta tocando violoncelo em Marte a estatua da liberdade de fundo e a lua explodindo mais lá no fundo..."` [cite: 17] | [cite_start]Inclusão de múltiplos elementos de fundo (Estátua da Liberdade + Explosão Cósmica)[cite: 17]. | [cite_start]Inserção correta do Gorila[cite: 18]. [cite_start]Contudo, a renderização geométrica da lua apresentou distorções artísticas inesperadas[cite: 19]. |
| **04** | [cite_start]`"Um gorila astronauta tocando violoncelo em Marte a estatua da liberdade de fundo e uma estação espacial explodindo mais lá no fundo..."` [cite: 22] | [cite_start]Substituição de elemento problemático ("lua") por "estação espacial" para mitigar alucinações de formato[cite: 19, 22]. | [cite_start]Correção da geometria de fundo com detritos espaciais mais condizentes com o caos do cenário[cite: 22]. |

---

## 🎨 Técnicas de Prompting Exploradas
* [cite_start]**Transferência de Estilo Artístico:** Aplicação de características do movimento **Barroco** (dramaticidade, emoção) em cenários de ficção científica[cite: 4, 8].
* [cite_start]**Direção de Iluminação:** Uso do termo técnico **Chiaroscuro** para forçar contrastes marcantes entre luz e sombra[cite: 8].
* [cite_start]**Controle de Atmosfera:** Inclusão de palavras-chave emocionais (`atmosfera melancólica`) para ditar o tom psicológico da imagem[cite: 8].
* [cite_start]**Depuração de Prompt (Debugging):** Substituição ativa de termos que geravam artefatos visuais bizarros por alternativas semanticamente mais fáceis para a IA processar[cite: 19, 22].

---

## 📊 Aprendizados Obtidos
* [cite_start]**Sensibilidade de Contexto:** Pequenas mudanças na ordem dos fatores de fundo modificam drasticamente as proporções dos objetos gerados[cite: 17, 22].
* [cite_start]**Limitações Geométricas:** Modelos de difusão de imagem por vezes falham em renderizar esferas perfeitas (como luas) quando associadas a conceitos de destruição ("explodindo"), tendendo a deformar o objeto[cite: 19].
* [cite_start]**Substituição de Tokens:** Mudar o foco do problema (de *Lua* para *Estação Espacial*) costuma ser mais eficiente do que tentar insistir no mesmo termo adicionando adjetivos corretivos[cite: 19, 22].

---

## 🔧 Como Visualizar este Laboratório
1. Certifique-se de ter um leitor de PDF instalado ou acesse a pasta `/assets` deste repositório para ver as imagens originais exportadas.
2. [cite_start]Abra o arquivo `a+corrida+do+prompt.pdf` para acompanhar os prints de tela da evolução temporal das gerações de IA[cite: 1, 10, 21].

---
[Voltar ao início](https://github.com/seu-usuario/seu-repositorio)
