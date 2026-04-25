# PDF Intelligence Bot 📄🤖
A Retrieval-Augmented Generation (RAG) system built with LangChain and Groq.

## 🌟 Overview
This project allows users to upload complex PDFs and ask specific questions about the content. It uses a **RAG architecture** to ensure the AI only answers based on the provided document, reducing hallucinations.

## 🛠️ Tech Stack
- **Orchestration:** LangChain (Modular v1+)
- **LLM:** Llama 3.1-8B (via Groq Cloud)
- **Vector Database:** ChromaDB
- **Embeddings:** HuggingFace `all-MiniLM-L6-v2` (Local/Open Source)
- **Environment:** Google Colab

## 🚀 Key Features
- **Semantic Search:** Uses vector embeddings to find relevant document sections.
- **LPU Inference:** Leverages Groq's hardware for near-instant responses.
- **Modular Design:** Implements modern LangChain-classic chains for stable retrieval.

## 📸 Sample Output
> **Question:** Summarize the main points of this document.
> **Answer:** [Paste a high-quality response you got from your code here!]
