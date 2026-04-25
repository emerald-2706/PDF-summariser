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
> **Answer:** --- ANSWER ---
Here's a 3-bullet point summary of the PDF:

* Candidates are expected to follow strict rules and regulations during the examination, including using only blue or black ink, not borrowing any articles, and maintaining silence in the examination hall.
* Candidates must ensure that their answer books are completed correctly, including writing their register number, name, course, and date of the examination in the correct space, and not tearing any pages out of the answer book.
* Candidates who engage in any form of misconduct, including cheating, using unfair means, or failing to follow the rules, will be liable for disciplinary action, which may include cancellation of the examination or rejection of the answer book.
