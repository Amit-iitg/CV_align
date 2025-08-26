# 🧠 CV Evaluator Web App with RAG & AI-Powered Matching

This project is a full-stack AI-based Resume Evaluator that simulates how an intelligent recruiter assesses candidate CVs against a given job description. Using **RAG (Retrieval-Augmented Generation)** with **LangChain**, **ChromaDB**, and **Ollama**, it provides feedback, scores, and match percentages, complete with a simulated typewriter-style output.

---

## 🚀 Features

- ✅ Upload CVs (`.pdf`, `.docx`)
- ✅ Submit Job Descriptions via Recruiter Form
- ✅ AI-generated match scores and detailed feedback
- ✅ Typewriter-style animated analysis output
- ✅ Role-based front-end views (Recruiter/Admin/Candidate)
- ✅ ChromaDB Vector Store Integration
- ✅ FastAPI backend + React frontend
- ✅ Optional Streamlit interface for local development

---

## 🛠️ Tech Stack

| Layer       | Technology                                      |
|-------------|-------------------------------------------------|
| Frontend    | React, TypeScript, TailwindCSS, ShadCN UI       |
| Backend     | FastAPI, Streamlit (for dev only)               |
| Vector DB   | ChromaDB (Local/Memory-based for now)           |
| LLM / RAG   | LangChain, Ollama, FAISS                        |
| Parsing     | PyMuPDF, python-docx, pdfminer.six              |
| Dev Tools   | Vite, Axios, dotenv, Ngrok                      |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone 
cd cv_align

backend setup

