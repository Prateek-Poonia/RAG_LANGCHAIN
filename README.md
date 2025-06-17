🔹 RAG (Retrieval-Augmented Generation)
RAG is a method that combines retrieval (fetching relevant documents or information) with generation (using language models like GPT to generate responses). Instead of relying only on pre-trained knowledge, RAG allows models to look up and use external documents in real time.

How it works:
A user asks a question.
Relevant documents are retrieved from a knowledge base (like PDFs, websites, or databases).
The documents + the user query are passed to a language model to generate a more accurate and informed answer.

Use Cases:
Chatbots with domain-specific knowledge
Customer support using company documents
Academic assistants referencing textbooks or notes
Legal/medical assistants using trusted documents

🔹 LangChain
Definition:
LangChain is an open-source framework for building applications using language models like GPT, especially when those apps need:
external data sources
tools (e.g., calculators, web search)
multi-step workflows (called "chains")

Key Components:
Document Loaders: Load PDFs, Notion pages, websites, etc.
Text Splitters: Break large documents into chunks.
Embeddings + Vector Stores: For semantic search in RAG.
Chains/Agents: Define how the model processes user input step-by-step.
Tools: Plug in functions like web search or database queries.

Use Cases:
1. Building RAG pipelines
2. Creating chatbots that can use tools (like calculators or Google search)
3.Making AI tutors that refer to specific course materials
4. Powering custom LLM apps (e.g., financial advisors, resume reviewers)

🔹 Example: Using RAG with LangChain
Let’s say you're building a medical assistant:

Use LangChain to:
1. Load and chunk medical textbooks
2.Store embeddings in a vector database like FAISS
3.Retrieve relevant text based on a question
4.Pass it all to GPT for a detailed answer
5. This entire setup is a RAG system, and LangChain helps you build it easily.

Here in this repo im going to use rag and langchain for text retrieval. In this jupyter notebook i will be giving my introduction as input and after that 
i will be asking question based on the text given on me.
