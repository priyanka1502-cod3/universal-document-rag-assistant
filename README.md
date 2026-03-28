# Universal Document RAG Assistant

A general-purpose Retrieval-Augmented Generation (RAG) system that allows users to upload documents (PDF/TXT) and ask questions using semantic search and LLMs.

---

## 🚀 Overview

This project enables users to interact with their own documents using a RAG pipeline:

* Upload documents
* Extract and chunk text
* Retrieve relevant sections
* Generate answers using FLAN-T5
* Display sources and confidence

---

## ✨ Features

* 📄 Upload PDF and TXT files
* 🔍 Semantic search using FAISS
* 🧠 LLM-based answers (FLAN-T5)
* 🧩 Chunking with overlap
* 📚 Multi-document support
* 📝 Summarization + QA
* ⚠️ Confidence scoring
* 💻 Gradio UI

---

## 🏗️ Architecture

```
Upload → Extract → Chunk → Embed → FAISS → Retrieve → LLM → Answer + Confidence
```

---

## 🧠 Tech Stack

* Python
* Sentence Transformers
* FAISS
* Transformers (FLAN-T5)
* Gradio
* PyTorch

---

## 💡 Example Questions

* Summarize the uploaded documents
* What are the main topics discussed?
* What conclusions are given?
* Compare the uploaded documents

---

## 📊 Evaluation

* Grounding score (hallucination detection)
* Manual QA testing
* Confidence scoring

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

Run the notebook in Google Colab or Jupyter.

---

## ⚠️ Limitations

* Only PDF and TXT supported
* No reranking yet
* No persistent database

---

## 🚀 Future Improvements

* DOCX support
* Chat memory
* Reranking
* Deployment

---

## 💼 Resume Highlight

Built a universal document RAG assistant using FAISS and FLAN-T5 with source-backed answers and confidence scoring.

---

## 👤 Author

Priyanka
