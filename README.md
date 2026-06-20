# 🧠 Engenharia de Prompt e Técnicas de RAG com NotebookLM

## 📑 Contexto e Objetivos
Este projeto foi desenvolvido para a aplicação prática dos conhecimentos adquiridos no **Santander Bootcamp** na plataforma **DIO (Digital Innovation One)**. O objetivo central é observar na prática o poder da Inteligência Artificial Generativa para a obtenção de conhecimento confiável e com baixa taxa de alucinações. 

O assunto escolhido aborda conceitos do próprio curso para aprofundar ainda mais o conteúdo ministrado. Para isso, utilizamos o **NotebookLM** como ferramenta de suporte, adicionando informações profundas sobre **RAG (Retrieval-Augmented Generation)** — a tecnologia exata em que essa ferramenta é baseada, criando uma experiência de aprendizado prático e metalinguístico.

---

## 📚 Curadoria de Fontes
As seguintes fontes foram selecionadas e carregadas no NotebookLM para compor a base de dados deste projeto:

1. **ChatGPT e Engenharia de Prompt: Técnicas para o Prompt Perfeito** - *Vídeo introdutório da Alura sobre geração de respostas* - [[Link do vídeo]](https://www.youtube.com/watch?v=NsXfldreSPQ)
2. **Engenharia de Prompt: Guia para Iniciantes** - *Definindo a engenharia de Prompt* - [[Link do vídeo]](https://www.youtube.com/watch?v=fNZcG-Ya168)
3. **Engenharia de Prompt: O Guia Definitivo** - *Abordagem prática para extrair o máximo potencial dos modelos de linguagem* - [[Link do vídeo]](https://www.youtube.com/watch?v=1VDcke66TRE)
4. **Engenharia de prompt, Fine-Tuning ou RAG, o que é e qual usar** - *Abordagens para otimizar o uso de IA em projetos práticos* - [[Link do vídeo]](https://www.youtube.com/watch?v=rNdINgxhHWc)
5. **Fine Tuning, RAG e Prompt Engineering: Qual é melhor? e Quando Usar?** - *Distinção entre Prompt Engineering, RAG e Fine-Tuning* - [[Link do vídeo]](https://www.youtube.com/watch?v=SFpzAWu_qs0)
6. **O que é engenharia de prompts?** - *Guia sobre a engenharia de prompt* - [[Link do site]](https://www.ibm.com/br-pt/think/topics/prompt-engineering)
7. **O que é engenharia de prompts?** - *Artigo técnico da AWS que define a engenharia de prompts* - [[Link do site]](https://aws.amazon.com/pt/what-is/prompt-engineering/)
8. **RAG (Retrieval-Augmented Generation) // Dicionário do Programador** - *Explicação didática do conceito de RAG* - [[Link do vídeo]](https://www.youtube.com/watch?v=CuPKOGdA46Q)
9. **RAG vs. ajuste fino vs. engenharia de prompts** - *Texto da IBM como um guia técnico que compara as três principais metodologias* - [[Link do site]](https://www.ibm.com/br-pt/think/topics/rag-vs-fine-tuning-vs-prompt-engineering)
10. **Retrieval Augmented Generation (RAG)** - *Um guia abrangente sobre a técnica de Geração Aumentada de Recuperação (RAG)* - [[Link do site]](https://www.promptingguide.ai/techniques/rag)

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Para extrair o conhecimento factual das fontes sem dar margem a alucinações, foram realizados testes estruturados de prompts dentro do NotebookLM.

### 🔬 Teste de Prompt 1: Análise Conceitual de RAG
* **Prompt Inicial:** *"Me explica o que é RAG."*
* **Resultado/Problema:** A resposta foi correta e bastante aprofundada por conta do conteúdo que foi disponibilizado, apresentando contexto, funcionamento e os motivos para utilizar o RAG de forma didática, porém o texto final ficou muito longo.
* **Prompt Otimizado (Solução):** *"Me explique o que é RAG de forma mais sucinta, em no máximo 100 palavras."*
* **Cicatriz/Aprendizado:** Ao estipular um limite de palavras, o modelo compreendeu a necessidade de síntese e gerou uma resposta direta e de rápida leitura.

### 🔬 Teste de Prompt 2: Conexão entre RAG e Engenharia de Prompt
* **Prompt Inicial:** *"Como o RAG está ligado à engenharia de prompt?"*
* **Resultado/Problema:** O modelo trouxe definições prontas da internet, misturando conceitos genéricos que não estavam destacados nos links selecionados na base.
* **Prompt Otimizado (Solução):** *"Com base nas fontes anexadas, explique como a Engenharia de Prompt atua na estruturação do contexto recuperado pelo sistema RAG para guiar a resposta final do LLM."*
* **Cicatriz/Aprendizado:** Quando a pergunta foi especificada delimitando a relação técnica entre os dois conceitos dentro da base de dados, o modelo soube trazer e solucionar todas as dúvidas de forma precisa.

### 🔬 Teste de Prompt 3: Diferenciação de Abordagens (RAG x Fine-Tuning)
* **Prompt Inicial:** *"Qual a diferença entre RAG e Fine-Tuning?"*
* **Resultado/Problema:** O modelo entregou uma resposta útil para a questão utilizando a base fornecida, mas o formato de texto corrido dificultava a comparação rápida.
* **Prompt Otimizado (Solução):** *"Utilizando as tabelas e guias comparativos da IBM e da AWS que foram carregados, monte uma tabela comparando RAG, Fine-Tuning e Engenharia de Prompt. Foque nos critérios de Custo, Necessidade de Dados e Casos de Uso."*
* **Cicatriz/Aprendizado:** Ao solicitar um formato de saída específico (tabela) e amarrar os critérios de comparação, a IA organiza o pensamento de forma muito mais analítica, facilitando o nosso estudo visual.

### 🔬 Teste de Prompt 4: Conceitos Técnicos (Embeddings e Bancos de Vetores)
* **Prompt Inicial:** *"O que são bancos de dados vetoriais e embeddings?"*
* **Resultado/Problema:** O prompt (sugerido pelo próprio modelo) abordou conceitos importantes, mas a resposta gerada foi excessivamente técnica e complexa.
* **Prompt Otimizado (Solução):** *"O que são bancos de dados vetoriais e embeddings? Explique de forma mais intuitiva e voltada para iniciantes, fornecendo exemplos do dia a dia."*
* **Cicatriz/Aprendizado:** Ao calibrar a persona do prompt para focar em "iniciantes" e pedir analogias do cotidiano, a IA conseguiu traduzir conceitos complexos de engenharia de dados em uma explicação simples e compreensível.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados
* **O que é RAG?** É o processo de otimizar a saída de um modelo de linguagem grande (LLM), fazendo-o consultar uma base de conhecimento externa confiável antes de responder ao usuário. Isso garante respostas atualizadas, factuais e livres de alucinações.
* **Engenharia de Prompt:** É a prática de projetar, refinar e estruturar textos de entrada (prompts) para guiar os modelos de IA generativa a produzirem os resultados desejados com a máxima precisão e no formato correto.
* **Embeddings e Bancos de Vetores:** São conceitos fundamentais que trabalham juntos para permitir que a máquina "entenda" o significado das informações.

### 🔤 Glossário de Conceitos Aprendidos
* **Alucinação:** Respostas geradas por IA que parecem perfeitamente corretas e coerentes, mas que são factualmente falsas.
* **Fine-Tuning (Ajuste Fino):** Processo de treinar adicionalmente um modelo de IA já existente em um conjunto de dados específico para adaptá-lo a uma tarefa ou estilo muito específico.
* **A Conexão entre RAG e Engenharia de Prompt:** Enquanto o RAG recupera os documentos certos e confiáveis do banco de dados, a Engenharia de Prompt entra em ação para organizar esse contexto recuperado de forma estratégica dentro do comando enviado ao LLM. É a engenharia de prompt que dita as regras de como a IA deve usar os dados do RAG (ex: "responda apenas com base no texto", "formate como tabela"), unindo a busca factual à geração de texto precisa.
* **Grounding (Ancoragem):** Técnica de vincular as respostas da IA a fontes de dados do mundo real para garantir a veracidade das informações.
* **Embeddings:** Representações numéricas de palavras ou frases que permitem que os computadores entendam o significado e o contexto semântico dos textos.
* **Banco de Vetores:** Um banco de dados vetorial (ou Vector Store) é um sistema de armazenamento especializado para guardar e gerenciar esses embeddings.

### 🤖 Prompts Reutilizáveis para Revisão
Copie e cole estes prompts no seu NotebookLM para revisar o conteúdo futuramente:

1. **Simulador de Entrevista Técnica:**
"Atue como um Engenheiro de IA Sênior realizando uma entrevista técnica de Ciência de Dados. Com base exclusivamente nas fontes fornecidas, me faça uma pergunta complexa sobre a diferença prática entre RAG e Fine-Tuning. Aguarde a minha resposta antes de fazer a próxima ou de me avaliar."

2. **Gerador de Flashcards de Fixação:**
"Extraia das fontes os 5 conceitos mais cruciais sobre Engenharia de Prompt e crie uma estrutura de Flashcards, apresentando o 'Conceito' na frente e a 'Definição Prática/Exemplo' no verso, ideal para memorização ativa."

3. **Análise de Casos de Uso:**
"Atue como um Arquiteto de Soluções de IA. Vou te dar um cenário de negócio hipotético e você deve utilizar os guias da AWS e IBM anexados para me recomendar se devo usar Engenharia de Prompt, RAG ou Fine-Tuning, justificando com base nos critérios de custo e dados."
