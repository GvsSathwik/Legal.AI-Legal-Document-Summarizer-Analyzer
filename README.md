# ⚖️ LegalAI – AI-Powered Legal Document Summarizer & Analyzer

<p align="center">
  <img src="./screenshots/banner.png" alt="LegalAI Banner" width="100%">
</p>

<p align="center">
  <b>Transform complex legal documents into actionable insights using Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and AI-powered legal analysis.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-LLM%20Powered-blue">
  <img src="https://img.shields.io/badge/RAG-Enabled-green">
  <img src="https://img.shields.io/badge/Next.js-15-black">
  <img src="https://img.shields.io/badge/FastAPI-Python-teal">
  <img src="https://img.shields.io/badge/Supabase-Backend-success">
</p>

---

## 🚀 Overview

LegalAI is an advanced LegalTech platform that leverages modern Large Language Models (LLMs) to analyze contracts, agreements, and legal documents.

The system automatically extracts key clauses, identifies risks, summarizes lengthy documents, enables document-based conversational AI, and generates comprehensive legal reports.

Designed for lawyers, law students, businesses, and compliance teams, LegalAI simplifies legal document understanding through Generative AI.

---

## ✨ Key AI Features

### 📄 AI Legal Document Summarization

Generate concise executive summaries from lengthy legal contracts and agreements.

### ⚠️ Risk Assessment Engine

Automatically identify:

* High-risk clauses
* Missing obligations
* Compliance concerns
* Potential liabilities

### 📝 Clause & Obligation Extraction

Extract:

* Payment clauses
* Confidentiality clauses
* Termination clauses
* Legal obligations
* Important deadlines

### 🤖 RAG-Based Document Chat

Ask questions about uploaded documents:

Examples:

* "What are the termination conditions?"
* "Who is responsible for payment?"
* "What are the penalties for breach?"

### 🔍 Semantic Search

Context-aware retrieval using document chunking and semantic similarity search.

### 📊 Contract Comparison

Compare two legal documents side-by-side and identify:

* Added clauses
* Removed clauses
* Modified terms
* Risk differences

### 🌐 Multi-Language Support

Supports:

* English
* Hindi
* Telugu

### 📑 PDF Report Generation

Export:

* Executive Summaries
* Risk Reports
* Full Legal Analysis

---

## 🧠 AI Architecture

```text
Document Upload
       │
       ▼
Document Parsing & OCR
       │
       ▼
Text Chunking
       │
       ▼
Embedding & Retrieval
       │
       ▼
RAG Pipeline
       │
       ▼
LLM Analysis
       │
       ▼
Summary | Risk Analysis | Chat | Reports
```

### AI Components

* Large Language Models (LLMs)
* Retrieval-Augmented Generation (RAG)
* Semantic Search
* Prompt Engineering
* OCR Processing
* Legal Clause Detection
* Information Extraction
* Multi-Provider AI Routing

---

## 🏗️ Tech Stack

### AI & Machine Learning

* Google Gemini 2.0 Flash
* Groq Llama 3.3 70B
* Hugging Face Inference API
* Retrieval-Augmented Generation (RAG)
* NLP Pipelines
* OCR Processing

### Frontend

* Next.js 15
* React
* TypeScript
* Tailwind CSS
* Zustand

### Backend

* FastAPI
* Python
* REST APIs

### Database & Authentication

* Supabase
* PostgreSQL
* Google OAuth
* Row Level Security (RLS)

---

## 📸 Screenshots

### Dashboard

![Dashboard](./screenshots/dashboard.png)

### Document Upload

![Upload](./screenshots/upload.png)

### Legal Analysis

![Analysis](./screenshots/analysis.png)

### RAG Chat

![Chat](./screenshots/chat.png)

### Contract Comparison

![Comparison](./screenshots/comparison.png)

---

## 🔄 AI Workflow

1. Upload Legal Document
2. Extract Text (OCR if needed)
3. Parse & Structure Content
4. Generate Embeddings
5. Retrieve Relevant Context
6. Analyze Using LLM
7. Produce:

   * Summary
   * Risks
   * Clauses
   * Insights
   * Q&A Responses

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/legalai.git
cd legalai
```

### Backend Setup

```bash
cd backend

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt

uvicorn app.main:app --reload
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

## 🔑 Environment Variables

```env
GEMINI_API_KEY=
GROQ_API_KEY=
HUGGINGFACE_API_KEY=

NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

NEXT_PUBLIC_BACKEND_URL=http://localhost:8000
```

---

## 📈 Future Enhancements

* Vector Database Integration
* Fine-Tuned Legal LLM
* AI Agent Workflow
* Citation-Based Responses
* Legal Knowledge Graph
* Multi-Document RAG
* Court Case Analysis

---

## 🔒 Security

* JWT Authentication
* Supabase RLS
* Rate Limiting
* Secure File Storage
* User-Owned Data Model
* GDPR-Friendly Architecture

---

## ⚠️ Disclaimer

LegalAI provides AI-generated insights and summaries for educational and productivity purposes only.

This application does not provide legal advice. Users should consult qualified legal professionals before making legal decisions.

---

## 👨‍💻 Author

**GVS Sathwik**

AI Engineer | Full Stack Developer | Generative AI Enthusiast

If you found this project useful, please ⭐ the repository.
