# 📰 Financial News Research AI Agent

An AI-powered financial news research tool that allows users to input news article URLs and ask natural-language questions to retrieve accurate, source-backed insights from the stock market and financial domain.

![](rockybot.jpg)

---

## 🚀 Features

- Ingest multiple financial news article URLs
- Extract and clean unstructured article content
- Chunk and embed content using OpenAI embeddings
- Store embeddings in FAISS for fast semantic search
- Answer user questions using a Retrieval-Augmented Generation (RAG) pipeline
- Return answers with original source URLs to prevent hallucinations

---

## 🧠 How It Works

1. User provides financial news article URLs
2. Articles are loaded and cleaned using LangChain’s UnstructuredURLLoader
3. Text is split into semantic chunks
4. Embeddings are generated and stored in FAISS
5. User asks a natural-language question
6. Relevant chunks are retrieved and passed to the LLM
7. The system returns an answer along with source links

---

## 🛠 Tech Stack

- **LLM:** OpenAI (GPT-4 compatible)
- **Framework:** LangChain
- **Vector Store:** FAISS
- **UI:** Streamlit
- **Text Extraction:** Unstructured
- **Language:** Python


