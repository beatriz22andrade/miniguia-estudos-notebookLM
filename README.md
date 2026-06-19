# 🧠 Engenharia de Prompt e Técnicas de RAG com NotebookLM

## 📑 Contexto e Objetivos
Este projeto foi desenvolvido para a aplicação prática dos conhecimentos adquiridos no curso da **DIO (Digital Innovation One)**. O objetivo central é observar na prática o poder da Inteligência Artificial Generativa para a obtenção de conhecimento confiável e com baixa taxa de alucinações. 

O assunto escolhido aborda conceitos do próprio curso para aprofundar ainda mais o conteúdo ministrado. Para isso, utilizamos o **NotebookLM** como ferramenta de suporte, adicionando informações profundas sobre **RAG (Retrieval-Augmented Generation)** — a tecnologia exata em que essa ferramenta é baseada, criando uma experiência de aprendizado prático e metalinguístico.

---

## 📚 Curadoria de Fontes
As seguintes fontes foram selecionadas e carregadas no NotebookLM para compor a base de dados deste projeto:

1. **ChatGPT e Engenharia de Prompt: Técnicas para o Prompt Perfeito** - *Vídeo introdutório da Alura sobre geração de resposta* - [[Link do vídeo]](https://www.youtube.com/watch?v=NsXfldreSPQ)
2. **Engenharia de Prompt: Guia para Iniciantes** - *Definindo a engenharia de Prompt* - [[Link do vídeo]](https://www.youtube.com/watch?v=fNZcG-Ya168)
3. **Engenharia de Prompt: O Guia Definitivo** - *Abordagem prática para extrair o máximo potencial dos modelos de linguagem* - [[Link do vídeo]](https://www.youtube.com/watch?v=1VDcke66TRE)
4. **Engenharia de prompt, Fine tunning ou RAG, o que é e qual usar** - *Abordagens para otimizar o uso de IA em projetos práticos* - [[Link do vídeo]](https://www.youtube.com/watch?v=rNdINgxhHWc)
5. **Fine Tuning, RAG e Prompt Engineering: Qual é melhor? e Quando Usar?** - *Distinção entre Prompt Engineering, RAG e Fine-Tuning* - [[Link do vídeo]](https://www.youtube.com/watch?v=SFpzAWu_qs0)
6. **O que é engenharia de prompts?** - *Guia sobre a engenharia de prompt* - [[Link do site]](https://www.ibm.com/br-pt/think/topics/prompt-engineering)
7. **O que é engenharia de prompts?** - *Artigo técnico da AWS define a engenharia de prompts* - [[Link do site]](https://aws.amazon.com/pt/what-is/prompt-engineering/)
8. **RAG (Retrieval-Augmented Generation) // Dicionário do Programador** - *Explicação do conceito de RAG* - [[Link do vídeo]](https://www.youtube.com/watch?v=CuPKOGdA46Q)
9. **RAG vs. ajuste fino vs. engenharia de prompts** - *Texto da IBM como um guia técnico que compara as três principais metodologias* - [[Link do site]](https://www.ibm.com/br-pt/think/topics/rag-vs-fine-tuning-vs-prompt-engineering)
10. **Retrieval Augmented Generation (RAG)** - *Um guia abrangente sobre a técnica de Geração Aumentada de Recuperação (RAG)* - [[Link do site]](https://www.promptingguide.ai/techniques/rag)
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
