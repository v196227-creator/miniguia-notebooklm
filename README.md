# 📚 Miniguia de Estudos: Inteligência Artificial Generativa com NotebookLM

Este repositório contém o projeto prático focado na criação de um Caderno Temático utilizando o Google NotebookLM, explorando a IA como ferramenta de aprendizagem ativa e curadoria de conhecimento. 

---

## 🎯 Contexto e Objetivos

- **Assunto de Interesse:** Fundamentos de Inteligência Artificial Generativa e Large Language Models (LLMs).
- **Objetivos de Estudo:**
  1. Compreender a arquitetura básica por trás dos LLMs (ex: Transformers).
  2. Mapear as principais aplicações práticas da IA Generativa no desenvolvimento de software.
  3. Estruturar um método de revisão contínua utilizando os recursos de "Notas" e "Resumos" do NotebookLM.

---

## 🔍 Curadoria de Fontes

Para alimentar o NotebookLM com informações confiáveis e criar um ambiente restrito de conhecimento (evitando alucinações), foram selecionadas as seguintes fontes abertas:

1. **[Artigo] Attention Is All You Need:** O paper original do Google que introduziu a arquitetura Transformer. *(Upload em PDF)*
2. **[Guia] OpenAI Prompt Engineering Guide:** Melhores práticas documentadas para extração de respostas precisas. *(Link salvo como texto)*
3. **[Relatório] The State of Generative AI in the Enterprise:** Um panorama de como empresas estão adotando a tecnologia. *(Upload em PDF)*
4. **[Artigo] IBM - What is Generative AI?:** Conceitos fundamentais e glossário inicial. *(Link da Web)*

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante a interação com o NotebookLM, o objetivo foi extrair resumos precisos e evitar respostas genéricas. Abaixo está o registro da evolução dos prompts:

### Tentativa 1: O Prompt Ingênuo
- **Prompt:** *"Resuma o que é IA Generativa e como os Transformers funcionam."*
- **Resposta do NotebookLM:** Entregou um parágrafo denso e acadêmico, misturando os conceitos do paper do Google de forma confusa para um iniciante.
- **Cicatriz/Troubleshooting:** A falta de restrição de formato e a pergunta muito ampla geraram uma resposta difícil de ler. Foi necessário instruir a IA sobre o público-alvo e o formato de saída.

### Tentativa 2: O Prompt Estruturado (Refinamento)
- **Prompt:** *"Atuando como um professor de tecnologia, explique o conceito de IA Generativa e a arquitetura Transformer. Utilize analogias simples. Estruture a resposta em tópicos (bullet points) e cite o nome do documento fonte utilizado para cada afirmação."*
- **Resposta do NotebookLM:** Excelente. A IA separou os conceitos, usou a analogia de um "coral de vozes" para explicar a *Self-Attention* (atenção do Transformer) e referenciou corretamente os PDFs.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto
A **Inteligência Artificial Generativa** é um subcampo do aprendizado de máquina focado em criar novos conteúdos (textos, códigos, imagens) a partir de padrões aprendidos em vastos conjuntos de dados.
- **A Revolução do Transformer:** Diferente dos modelos antigos que liam palavras sequencialmente, a arquitetura Transformer consegue analisar todas as palavras de uma frase simultaneamente (mecanismo de atenção), entendendo o contexto global.
- **LLMs (Large Language Models):** São modelos treinados em bilhões de parâmetros focados especificamente em linguagem humana e código.
- **Aplicações no Mercado:** Geração de código (Copilots), automação de atendimento, sumarização de documentos complexos e ideação criativa.

### 2. Glossário de Conceitos
* **Alucinação:** Quando a IA gera uma resposta confiante, mas incorreta ou sem base factual nos documentos fornecidos.
* **Tokenização:** O processo de quebrar palavras em pedaços menores (tokens) para que a máquina possa processar matematicamente o texto.
* **Self-Attention:** Mecanismo matemático que permite ao modelo entender a relação e a importância de uma palavra em relação a todas as outras na mesma frase.
* **Prompt Engineering:** A técnica de desenhar e refinar instruções (prompts) para obter o melhor resultado possível de um LLM.

### 3. Prompts Reutilizáveis para Revisão
Guarde estes prompts no NotebookLM para gerar testes práticos e revisar o conteúdo periodicamente:

> 🧠 **Gerador de Flashcards:** *"Crie 5 flashcards baseados nas fontes fornecidas. De um lado coloque um conceito chave sobre LLMs, e do outro a sua definição em no máximo duas frases."*

> 📝 **Simulador de Entrevista:** *"Assuma o papel de um recrutador técnico. Faça 3 perguntas de nível júnior sobre a arquitetura Transformer baseando-se nos documentos carregados. Espere eu responder uma a uma e corrija minhas respostas."*

> 🔄 **Resumo de Lacunas:** *"Analise as anotações que fiz nos documentos. Existe algum conceito crucial sobre IA Generativa que eu não destaquei? Se sim, explique-o brevemente."*
