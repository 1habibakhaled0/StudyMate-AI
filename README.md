# 📚 StudyMate AI

An AI-powered study assistant that uses Retrieval-Augmented Generation (RAG) and Large Language Models to answer questions from educational materials.

---

## 👤 Participant

| Field | Value |
|---|---|
| **Full Name** | Habiba Khalid Shaban Mohamed Maray |
| **Project Name** | StudyMate AI |
| **GitHub Username** | HabibaKhaled |
| **Internship Batch** | August–October 2026 |
| **Training Program** | Large Language Models (LLMs) Program |
| **Organization** | Edrak for AI |

---

# 📖 Project Overview

**StudyMate AI** is an AI-powered study assistant designed to help students understand and ask questions about educational lecture materials.

The project uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from educational PDF materials and use it as context for a Large Language Model.

The project was developed and tested using **Kaggle Notebooks**, with **Streamlit** used for the user interface and **Ngrok** used to expose the application.

---

# ✨ Features

- PDF-based Question Answering
- Semantic Search
- LLM-powered Answers
- Retrieval-Augmented Generation (RAG)
- FAISS Vector Search
- Interactive Study Assistant
- Streamlit User Interface
- Ngrok for application access

---

# 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- Qwen/Qwen2.5-1.5B-Instruct
- LangChain
- Sentence Transformers
- FAISS
- PyPDFLoader
- Streamlit
- Ngrok
- Kaggle Notebooks

---

# ⚙️ Installation

Install the required libraries:

```bash
pip install transformers
pip install sentence-transformers
pip install faiss-cpu
pip install langchain
pip install langchain-community
pip install pypdf
pip install streamlit
pip install pyngrok

🚀 Usage

The project follows this pipeline:

PDF → Text Extraction → Text Chunking → Embeddings → FAISS → Retrieval → Qwen LLM → Generated Answer

The user asks a question about the educational material, and the system retrieves relevant information before generating the answer.

📸 Demo
🖥️ Stre
amlit Interface

![Streamlit Interface](demo_interface.png)

💬 Asking a Question

![Asking a Question](demo_question.png)

🤖 Generated Answer

![Generated Answer](demo_answer.png)

---

# 📈 Results

The project demonstrates how RAG and Large Language Models can be used to build an educational question-answering system.

The system can process educational PDF material, retrieve relevant information, and generate answers using an LLM.

---

# 🔮 Future Improvements

- Support multiple educational PDFs.
- Add conversation memory.
- Improve retrieval accuracy.
- Add automatic MCQ and quiz generation.
- Add student progress tracking.
- Deploy the application as a web application.

---

# 📚 About the Internship

This project was developed as part of the **Tips Hindawi Internship (August–October 2026)** in the **Large Language Models (LLMs) Program**.

The internship provides practical training in Large Language Models and encourages participants to develop real-world AI projects.

---

# 📄 License

This project is shared for educational and portfolio purposes.
