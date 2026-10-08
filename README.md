# 📚 Mathematical Foundations AI Study Assistant

An AI-powered educational assistant designed to answer questions from the **Mathematical Foundations lecture PDF**.

The system combines **Retrieval-Augmented Generation (RAG)**, semantic search, a Large Language Model, and an interactive Streamlit interface to provide answers grounded in the lecture material.

---

## 👤 Participant

| Field                | Value                                       |
| -------------------- | ------------------------------------------- |
| **Full Name**        | Habiba Khalid Shaban Mohamed Maray          |
| **Project Name**     | Mathematical Foundations AI Study Assistant |
| **GitHub Username**  | 1habibakhaled0                              |
| **Internship Batch** | August–October 2026                         |
| **Training Program** | Large Language Models (LLMs) Program        |
| **Organization**     | Edrak for AI                                |

---

## 📖 Project Overview

The **Mathematical Foundations AI Study Assistant** is an AI-based educational assistant designed to help students study and understand mathematical foundations lecture materials.

The project uses a **Retrieval-Augmented Generation (RAG)** pipeline. The lecture PDF is processed, divided into smaller chunks, converted into vector embeddings, and stored in a **FAISS vector database**.

When a student asks a question, the system retrieves the most relevant sections from the lecture and provides them as context to a Large Language Model. The LLM then generates an answer based on the retrieved information.

The goal is to provide a simple and interactive way for students to ask questions about their study material instead of manually searching through the entire PDF.

---

## 🔄 Project Pipeline

```text
PDF
↓
Text Chunking
↓
Embeddings
↓
FAISS Vector Database
↓
Retriever
↓
RAG
↓
Qwen2.5-1.5B-Instruct
↓
Output Parser
↓
Streamlit GUI
↓
Ngrok
```

---

## 🤖 Models

### LLM

**Qwen/Qwen2.5-1.5B-Instruct**

Used to generate answers based on the context retrieved from the lecture material.

### Embedding Model

**sentence-transformers/all-MiniLM-L6-v2**

Used to convert document chunks and queries into numerical vector representations.

### Vector Database

**FAISS**

Used to store embeddings and perform efficient similarity-based retrieval.

---

## ✨ Main Features

* 📄 **PDF Question Answering**
* 🔎 **Semantic Retrieval**
* 🧠 **Retrieval-Augmented Generation (RAG)**
* 🤖 **LLM Integration**
* 📝 **Output Parsing**
* 💬 **Conversation Memory**
* 🌐 **Streamlit GUI**
* 🔗 **Public Access Using Ngrok**
* 🧪 **Out-of-Domain Evaluation**
* 📊 **Evaluation Visualizations**
