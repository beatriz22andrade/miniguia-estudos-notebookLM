# 🧠 Engenharia de Prompt e Técnicas de RAG com NotebookLM

## 📑 Contexto e Objetivos
Este projeto foi desenvolvido para a aplicação prática dos conhecimentos adquiridos no curso da **... (Coloque o nome do curso aqui, ex: Santander Bootcamp) ...** na plataforma **DIO (Digital Innovation One)**. O objetivo central é observar na prática o poder da Inteligência Artificial Generativa para a obtenção de conhecimento confiável e com baixa taxa de alucinações. 

O assunto escolhido aborda conceitos do próprio curso para aprofundar ainda mais o conteúdo ministrado. Para isso, utilizamos o **NotebookLM** como ferramenta de suporte, adicionando informações profundas sobre **RAG (Retrieval-Augmented Generation)** — a tecnologia exata em que essa ferramenta é baseada, criando uma experiência de aprendizado prático e metalinguístico.

---

## 📚 Curadoria de Fontes
As seguintes fontes foram selecionadas e carregadas no NotebookLM para compor a base de dados deste projeto:

1. **ChatGPT e Engenharia de Prompt: Técnicas para o Prompt Perfeito** - *Vídeo introdutório da Alura sobre geração de resposta* - [[Link do vídeo]](https://www.youtube.com/watch?v=NsXfldreSPQ)
2. **Engenharia de Prompt: Guia para Iniciantes** - *Definindo a engenharia de Prompt* - [[Link do vídeo]](https://www.youtube.com/watch?v=fNZcG-Ya168)
3. **Engenharia de Prompt: O Guia Definitivo** - *Abordagem prática para extrair o máximo potencial dos modelos de linguagem* - [[Link do vídeo]](https://www.youtube.com/watch?v=1VDcke66TRE)
4. **Engenharia de prompt, Fine tunning ou RAG, o que é e qual usar** - *Abordagens para otimizar o uso de IA in projetos práticos* - [[Link do vídeo]](https://www.youtube.com/watch?v=rNdINgxhHWc)
5. **Fine Tuning, RAG e Prompt Engineering: Qual é melhor? e Quando Usar?** - *Distinção entre Prompt Engineering, RAG e Fine-Tuning* - [[Link do vídeo]](https://www.youtube.com/watch?v=SFpzAWu_qs0)
6. **O que é engenharia de prompts?** - *Guia sobre a engenharia de prompt* - [[Link do site]](https://www.ibm.com/br-pt/think/topics/prompt-engineering)
7. **O que é engenharia de prompts?** - *Artigo técnico da AWS define a engenharia de prompts* - [[Link do site]](https://aws.amazon.com/pt/what-is/prompt-engineering/)
8. **RAG (Retrieval-Augmented Generation) // Dicionário do Programador** - *Explicação do conceito de RAG* - [[Link do vídeo]](https://www.youtube.com/watch?v=CuPKOGdA46Q)
9. **RAG vs. ajuste fino vs. engenharia de prompts** - *Texto da IBM como um guia técnico que compara as três principais metodologias* - [[Link do site]](https://www.ibm.com/br-pt/think/topics/rag-vs-fine-tuning-vs-prompt-engineering)
10. **Retrieval Augmented Generation (RAG)** - *Um guia abrangente sobre a técnica de Geração Aumentada de Recuperação (RAG)* - [[Link do site]](https://www.promptingguide.ai/techniques/rag)

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Para extrair o conhecimento factual das fontes sem dar margem a alucinações, foram realizados testes estruturados de prompts dentro do NotebookLM.

### 🔬 Teste de Prompt 1: Análise Conceitual de RAG
* **Prompt Inicial:** *"Me explica o que o curso diz sobre RAG."*
* **Resultado/Problema:** A resposta foi correta, mas rasa, sem explorar os detalhes técnicos dos documentos anexados.
* **Prompt Otimizado (Solução):** *"Com base exclusivamente nas fontes fornecidas, faça uma síntese de como o RAG combina a busca de documentos com a geração de texto para mitigar alucinações. Cite os termos-chave encontrados no texto."*
* **Cicatriz/Aprendizado:** Delimitar o escopo ("com base exclusivamente nas fontes") força a IA a ignorar o conhecimento geral da internet e focar estritamente no documento fornecido.

### 🔬 Teste de Prompt 2: Diferenciação de Abordagens (RAG x Fine-Tuning)
* **Prompt Inicial:** *"Qual a diferença entre RAG e Fine-Tuning?"*
* **Resultado/Problema:** O modelo trouxe definições prontas da internet, misturando conceitos que não estavam destacados nos links selecionados.
* **Prompt Otimizado (Solução):** *"Utilizando as tabelas e guias comparativos da IBM e da AWS que foram carregados, monte uma tabela comparando RAG, Fine-Tuning e Engenharia de Prompt. Foque nos critérios de Custo, Necessidade de Dados e Casos de Uso."*
* **Cicatriz/Aprendizado:** Ao solicitar um formato de saída específico (tabela) e amarrar os critérios de comparação, a IA organiza o pensamento de forma muito mais analítica, facilitando o nosso estudo.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados
* **O que é RAG?** É o processo de otimizar a saída de um modelo de linguagem grande (LLM), fazendo-o consultar uma base de conhecimento externa confiável antes de responder ao usuário. Isso garante respostas atualizadas e factuais.
* **Engenharia de Prompt:** É a prática de projetar, refinar e estruturar textos de entrada (prompts) para guiar os modelos de IA generativa a produzirem os resultados desejados com a máxima precisão.

### 🔤 Glossário de Conceitos Aprendidos
* **Alucinação:** Respostas geradas por IA que parecem perfeitamente corretas e coerentes, mas que são factualmente falsas.
* **Fine-Tuning (Ajuste Fino):** Processo de treinar adicionalmente um modelo de IA já existente em um conjunto de dados específico para adaptá-lo a uma tarefa ou estilo muito nichado.
* **Grounding (Ancoragem):** Técnica de vincular as respostas da IA a fontes de dados do mundo real para garantir a veracidade das informações.

### 🤖 Prompts Reutilizáveis para Revisão
Copie e cole estes prompts no seu NotebookLM para revisar o conteúdo futuramente:

```text
Atue como um tutor acadêmico. Com base nos documentos anexados, gere um questionário de 3 perguntas e respostas para testar meu conhecimento sobre Engenharia de Prompts.
