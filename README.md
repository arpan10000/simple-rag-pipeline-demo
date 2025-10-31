# 🌌 Simple RAG Pipeline (Chroma DB + Grok LLM)

This project showcases a **minimal yet complete Retrieval-Augmented Generation (RAG)** pipeline using **Chroma DB** for vector storage and **Grok LLM** for intelligent, context-aware answers.

It’s built to **demystify RAG systems** — showing, in a clear and modular way, how data moves from raw text to meaningful AI-generated responses.

---

## 🚀 What’s Inside

📂 **Sample Data**

* Two plain-text files
* Two PDF documents

📘 **Notebooks**

* `document.ipynb` — document ingestion and embedding basics
* `pdf_loader.ipynb` — PDF loading and preprocessing

🧩 **Python Modules**

* `document_loader.py` — loads and cleans text and PDF data
* `embeddings.py` — generates embeddings for text chunks
* `vector_store.py` — manages Chroma DB connection and storage
* `search.py` — performs semantic search and document retrieval
* `app.py` — integrates all modules into a complete RAG workflow

---

## ⚙️ How It Works

1. **Document Loading**
   Text and PDF files are read, cleaned, and split into manageable chunks.

2. **Embedding Creation**
   Each chunk is transformed into a high-dimensional vector representation.

3. **Vector Storage**
   These embeddings are stored in **Chroma DB** for efficient semantic retrieval.

4. **Context Retrieval**
   When a user asks a question, the most relevant chunks are fetched based on similarity.

5. **Answer Generation**
   The retrieved context and user query are passed to **Grok LLM**, which synthesizes a clear, context-rich answer.

---

## 🎯 Project Goal

The goal of this project is to **offer a simple, educational demonstration** of how a RAG pipeline works — covering every stage from:

* Document ingestion
* Text embedding
* Vector database integration
* Context-driven LLM responses

Perfect for learners and developers exploring how to connect structured data retrieval with modern LLMs.

---

## 🪄 Run It Yourself

1. Explore the Jupyter notebooks to understand each stage of the pipeline.
2. Run `app.py` to experience the **end-to-end RAG workflow** in action.

---

✨ **This project is learning-focused** — clean, modular, and designed for clarity.
It’s an ideal foundation for experimenting with your own data sources and LLM integrations.

---
