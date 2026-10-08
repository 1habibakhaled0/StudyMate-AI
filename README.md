 # 📚 StudyMate AI

An AI-powered study assistant that helps students understand and ask questions about their **Mathematical Foundations** lecture material.

The system uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from the lecture PDF and generate answers using a Large Language Model.

---

## 👤 Participant

| Field                | Value                                |
| -------------------- | ------------------------------------ |
| **Full Name**        | Habiba Khalid Shaban Mohamed Maray   |
| **Project Name**     | StudyMate AI                         |
| **GitHub Username**  | 1habibakhaled0                       |
| **Internship Batch** | August–October 2026                  |
| **Training Program** | Large Language Models (LLMs) Program |
| **Organization**     | Edrak for AI                         |

---

# 📖 Project Overview

**StudyMate AI** is an AI-based educational assistant designed to help students study and understand mathematical foundations lecture materials.

The project uses a **Retrieval-Augmented Generation (RAG)** pipeline. The lecture PDF is processed, divided into smaller chunks, converted into vector embeddings, and stored in a **FAISS vector database**.

When a student asks a question, the system retrieves the most relevant sections from the lecture and provides them as context to a Large Language Model. The LLM then generates an answer based on the retrieved information.

The goal is to provide students with a simple and interactive way to ask questions about their study material instead of manually searching through the entire PDF.

---

# ✨ Features

* 📄 **PDF-based Question Answering**

  * Ask questions about the Mathematical Foundations lecture PDF.

* 🔎 **Semantic Search**

  * Retrieves the most relevant lecture sections using vector embeddings.

* 🤖 **LLM-powered Answers**

  * Uses **Qwen/Qwen2.5-1.5B-Instruct** to generate natural-language responses.

* 🧠 **Retrieval-Augmented Generation**

  * Combines document retrieval with LLM generation to provide context-aware answers.

* 💾 **FAISS Vector Database**

  * Stores document embeddings and enables efficient similarity search.

* 💬 **Interactive Study Assistant**

  * Allows students to interact with their lecture material through questions.

* 🌐 **Streamlit Interface**

  * Provides a simple graphical interface for interacting with the assistant.

---

# 🛠️ Technologies Used

### Programming Language

* Python

### AI & LLM

* Hugging Face Transformers
* Qwen/Qwen2.5-1.5B-Instruct
* Large Language Models (LLMs)

### RAG

* Retrieval-Augmented Generation (RAG)
* LangChain
* Retriever
* Output Parser

### Embeddings & Vector Search

* Sentence Transformers
* FAISS

### Document Processing

* PyPDFLoader
* PDF text extraction
* Text chunking

### Interface & Tunneling

* Streamlit
* Ngrok

### Development Environment

* Kaggle Notebooks

---

# ⚙️ Installation

The project was developed and tested using **Kaggle Notebooks**.

### 1. Install the required libraries

```bash
pip install transformers
pip install sentence-transformers
pip install faiss-cpu
pip install langchain
pip install langchain-community
pip install pypdf
pip install streamlit
pip install pyngrok
```

### 2. Load the lecture PDF

Upload or access the Mathematical Foundations lecture PDF through the Kaggle environment.

Example:

```text
AI311_W01_Lecture01_Mathematical_Foundations_45slides.pdf
```

### 3. Configure Hugging Face

A Hugging Face Access Token may be required to access the selected model.

The token should be stored securely using Kaggle Secrets or another secure environment instead of writing it directly in the notebook.

---

# 🚀 Usage

The system follows a complete RAG workflow.

### Step 1 — Load the PDF

The system loads the Mathematical Foundations lecture PDF using a PDF loader.

### Step 2 — Split the Document

The extracted text is divided into smaller chunks to make retrieval more efficient.

### Step 3 — Create Embeddings

Each text chunk is converted into a numerical vector using a Sentence Transformers embedding model.

### Step 4 — Build the FAISS Vector Store

The generated embeddings are stored in a FAISS vector store for similarity-based retrieval.

### Step 5 — Retrieve Relevant Information

When the user asks a question, the retriever searches the vector database and returns the most relevant lecture chunks.

### Step 6 — Generate the Answer

The retrieved context is passed to the **Qwen2.5-1.5B-Instruct** model, which generates the final answer.

### Overall Pipeline

```text
PDF
 ↓
Text Extraction
 ↓
Text Chunking
 ↓
Embeddings
 ↓
FAISS Vector Store
 ↓
Retriever
 ↓
Relevant Context
 ↓
Qwen LLM
 ↓
Generated Answer
```

### Step 7 — Interactive Interface

A **Streamlit** interface was created to allow the user to interact with the study assistant.

The interface was tested using **Ngrok on Kaggle Notebooks**, allowing the Streamlit application to be accessed through a temporary public URL during the demonstration.

---

# 📸 Demo

The project includes an interactive Streamlit interface that allows students to ask questions about the Mathematical Foundations lecture PDF and receive AI-generated answers based on the retrieved lecture content.

### 🖥️ Streamlit Interface

![Streamlit Interface](demo_interface.png)

### 💬 Asking a Question

![Asking a Question](demo_question.png)

### 🤖 Generated Answer

![Generated Answer](demo_answer.png)

### Demo Workflow

```text
User Question
      ↓
Retriever
      ↓
Relevant Lecture Content
      ↓
Qwen LLM
      ↓
Generated Answer
```

---

# 📈 Results

The project successfully demonstrates how **Retrieval-Augmented Generation and Large Language Models can be used to build an educational question-answering system**.

The system can:

* Process the Mathematical Foundations lecture PDF.
* Divide the lecture content into searchable chunks.
* Convert lecture content into vector representations.
* Retrieve relevant information using semantic similarity.
* Use retrieved context to support LLM-generated answers.
* Provide an interactive interface through Streamlit.

The project also provided practical experience with the complete RAG workflow, from **document processing and embeddings to retrieval and LLM generation**.

---

# 🔮 Future Improvements

* 📚 Support multiple lecture PDFs instead of a single document.
* 💬 Add conversation memory for longer study sessions.
* 🎯 Improve answer accuracy using reranking techniques.
* 📝 Add automatic quiz and MCQ generation from lecture materials.
* 📊 Add student progress and study tracking.
* 🌐 Deploy the application as a permanent web application.
* 🔊 Add optional voice-based interaction for questions and answers.

---

# 📚 About the Internship

This project was developed as part of the **Tips Hindawi Internship (August–October 2026)**.

The internship focuses on practical training in **Large Language Models (LLMs)** and encourages participants to apply their knowledge by developing real-world AI projects.

The project demonstrates practical applications of:

* Large Language Models
* Retrieval-Augmented Generation
* Vector Databases
* Semantic Search
* Prompt Engineering
* AI Application Development

The internship is organized by **Tips Hindawi**, the internships department of **Edrak for AI**.

---

# 📄 License

This project is shared for **educational and portfolio purposes**.

© 2026 Habiba Khalid Shaban Mohamed Maray

