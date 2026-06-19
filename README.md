# 🧠 Engenharia de Prompt e Técnicas de RAG com NotebookLM

## 📑 Contexto e Objetivos
Este projeto foi desenvolvido para a aplicação prática dos conhecimentos adquiridos no curso da **DIO (Digital Innovation One)**. O objetivo central é observar na prática o poder da Inteligência Artificial Generativa para a obtenção de conhecimento confiável e com baixa taxa de alucinações. 

O assunto escolhido aborda conceitos do próprio curso para aprofundar ainda mais o conteúdo ministrado. Para isso, utilizamos o **NotebookLM** como ferramenta de suporte, adicionando informações profundas sobre **RAG (Retrieval-Augmented Generation)** — a tecnologia exata em que essa ferramenta é baseada, criando uma experiência de aprendizado prático e metalinguístico.

---

## 📚 Curadoria de Fontes
As seguintes fontes foram selecionadas e carregadas no NotebookLM para compor a base de dados deste projeto:

1. **ChatGPT e Engenharia de Prompt: Técnicas para o Prompt Perfeito** - *Vídeo introdutório da Alura sobre geração de resposta* - (https://www.youtube.com/watch?v=NsXfldreSPQ)
2. **[Nome da Fonte 2]** - *[Breve descrição do documento, ex: Artigo técnico explicativo sobre arquitetura RAG]* - [[Link ou Referência]](https://www.youtube.com/watch?v=fNZcG-Ya168)
3. **[Nome da Fonte 3]** - *[Breve descrição do documento, ex: Guia de boas práticas em Engenharia de Prompts]* - [Link ou Referência]

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Para extrair o conhecimento factual das fontes sem dar margem a alucinações, foram realizados testes estruturados de prompts dentro do NotebookLM.

### 🔬 Teste de Prompt 1: Análise Conceitual
* **Prompt Inicial:** *"Me explica o que o curso diz sobre RAG."*
* **Resultado/Problema:** A resposta foi correta, mas rasa, sem explorar os detalhes técnicos dos documentos anexados.
* **Prompt Otimizado (Solução):** *"Com base exclusivamente nas fontes fornecidas, faça uma síntese de como o RAG combina a busca de documentos com a geração de texto para mitigar alucinações. Cite os termos-chave encontrados no texto."*
* **Cicatriz/Aprendizado:** Delimitar o escopo ("com base exclusivamente nas fontes") força a IA a ignorar o conhecimento geral da internet e focar estritamente no documento fornecido.

### 🔬 Teste de Prompt 2: [Adicione seu segundo teste aqui]
* **Prompt Inicial:** *[Seu prompt inicial]*
* **Prompt Otimizado:** *[Seu prompt otimizado]*
* **Cicatriz/Aprendizado:** *[O que você aprendeu com a variação do resultado]*

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados
* **O que é RAG?** É o processo de otimizar a saída de um modelo de linguagem grande (LLM), fazendo-o consultar
