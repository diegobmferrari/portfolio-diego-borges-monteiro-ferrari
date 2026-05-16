# ⚔️ Batalha de Modelos: Engenharia de Prompt com Estruturação XML

## 📝 Descrição do Projeto
Este projeto consiste em um estudo comparativo de **Engenharia de Prompt (Prompt Engineering)** focado na eficácia da estruturação de instruções utilizando tags XML. O objetivo principal é avaliar a capacidade de interpretação, a precisão técnica e a eficiência de diferentes Grandes Modelos de Linguagem (LLMs) do mercado ao processarem um mesmo prompt padronizado.

Desenvolvido como parte do laboratório prático de **Engenharia de Prompt e Aplicações em IA**, o experimento consistiu em submeter as IAs a um desafio técnico: gerar o código para uma página web única (*Single Page Application*) em HTML5 e CSS3, com design responsivo, baseada no tema "Mestre do Miojo".

![Figura 1: Representação de testes e análises comparativas entre múltiplos modelos de IA](https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=800&q=80)
*Figura 1: Fluxo conceitual de avaliação cruzada e engenharia de prompts estruturados.*

---

## 👥 Integrantes do Grupo
* Eduardo Costa de Alencar
* Diego Borges Monteiro Ferrari
* Jose Guilherme do Santos Guedes

---

## 🛠️ O Prompt Estruturado (XML)
A técnica de delimitação por tags XML foi utilizada para separar claramente os objetivos, restrições e escopo do projeto, otimizando o processamento do contexto pelas IAs. O esqueleto do prompt aplicado seguiu a estrutura abaixo:

```xml
<tarefa>
  <objetivo>Criar uma página HTML5 única com CSS3 interno (single page).</objetivo>
  <tema>Mestre do Miojo</tema>
  <diretrizes_design>
    <layout>Responsivo e minimalista.</layout>
    <paleta_cores>Verde, Vermelho e Laranja</paleta_cores>
    <tipografia>Sans-serif para títulos, Serif para corpo.</tipografia>
  </diretrizes_design>
  <obrigatoriedades_tecnicas>
    <item>Menu de navegação functional (âncoras).</item>
    <item>Seção de portfólio ou galeria.</item>
    <item>Rodapé com informações de contato simuladas.</item>
    <item>Macarrão instantâneo</item>
  </obrigatoriedades_tecnicas>
  <metrica_obrigatoria>
    Ao final da resposta, informe uma estimativa de quantos tokens foram gerados para este código.
  </metrica_obrigatoria>
</tarefa>

🚀 Modelos Avaliados
O protocolo de execução foi testado de forma cruzada nas seguintes ferramentas:

OpenAI (ChatGPT / GPT)

Google (Gemini)

DeepSeek

Alibaba (Qwen)

xAI (Grok)

Maritaca AI (Maritaca)

Anthropic (Claude)

📊 Resultados e Reflexão Crítica
Os modelos apresentaram comportamentos e consumos de recursos extremamente heterogêneos para a mesma entrada de dados.

Resumo das Métricas Coletadas:
Maior Compreensão Estrutural: O Claude demonstrou a melhor capacidade de interpretação do formato XML, alcançando precisão excelente nas diretrizes e superando muito as expectativas na entrega do HTML.

Disparidade de Verbosidade: Houve uma variação massiva no gasto de tokens. Enquanto o GPT solucionou o problema de forma básica gastando apenas 900 tokens, o Qwen consumiu 3500 tokens para uma entrega de precisão considerada básica.

Bugs Comuns: Falhas ou ausência total no carregamento de imagens integradas foram as ocorrências de erro mais frequentes entre a maioria das IAs (como Gemini, Qwen e Maritaca).

Diagnóstico de Ferramenta Ideal:
De acordo com as análises do laboratório, o modelo Claude consolidou-se como a escolha ideal para ambos os cenários avaliados: tanto para a realização de prototipagem rápida quanto para o desenvolvimento de códigos mais complexos.

🔧 Como Visualizar este Estudo
Navegue até a pasta /docs deste repositório.

Abra o arquivo Experiência 3 - Batalha de Modelos & Engenharia de Prompt (XML).pdf para consultar as tabelas detalhadas com notas de criatividade, erros de sintaxe e comportamento individual de cada motor de IA analisado.

Voltar ao início
