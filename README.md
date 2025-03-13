# RAG_AGNO_AGENT
Agent-based RAG System using LangChain, Qdrant, and Ollama

Overview
This project implements a Retrieval-Augmented Generation (RAG) system using:

LangChain for document processing and retrieval
Qdrant as a vector database for efficient similarity search
FastEmbed for embedding generation
Ollama (Llama3.1) for LLM-based response generation
Agno Agent for managing the retrieval and answer generation process
It enables intelligent question-answering over web documents by:

Fetching and chunking text from online sources.
Generating embeddings and storing them in Qdrant.
Retrieving relevant text based on user queries.
Passing retrieved content to the LLM to generate structured responses.
Features
✅ Web-based document ingestion using WebBaseLoader
✅ Text chunking using RecursiveCharacterTextSplitter
✅ Embedding generation via FastEmbed
✅ Vector storage and similarity search using Qdrant
✅ Agent-powered query handling with Ollama (llama3.1)
✅ Fully autonomous RAG pipeline

How It Works
1️⃣ Data Collection → Loads data from a web page
2️⃣ Chunking & Embedding → Splits and embeds the text
3️⃣ Storage & Retrieval → Stores embeddings in Qdrant and retrieves relevant chunks
4️⃣ LLM-based Answering → Uses Ollama to generate responses based on retrieved knowledge

How to Run
1) Install using git clone "git clone https://github.com/Harshadeep100/RAG_AGNO_AGENT.git"
2) Go to the repository and install the requirements.txt using "pip install -r requirements.txt"

Run the agent:
python your_script_name.py

Technologies Used
🟢 Python – Core implementation
🟢 LangChain – Document processing & retrieval
🟢 Qdrant – Vector database for efficient search
🟢 FastEmbed – High-performance embedding generation
🟢 Ollama – LLM-powered response generation

Future Enhancements
🚀 Add support for multiple data sources (PDFs, APIs, databases)
🚀 Implement hybrid retrieval (vector + keyword search)
🚀 Fine-tune the LLM for domain-specific knowledge
🚀 Build a frontend for interactive querying

