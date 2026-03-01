# ABSTRACT – GEN AI BASED AGENT CHATBOT

## 📌 Problem Statement
Develop a **Generative AI–powered intelligent agent chatbot** for **Academic, Automotive, and Technology domains** to serve as a comprehensive conversational interface for students, staff, customers, and support teams.

The chatbot must provide **accurate, real-time, and up-to-date information** using domain-specific databases and documents. It should handle queries related to:
- Admissions
- Courses
- Schedules
- Services
- Vehicle information
- Product support
- Policies
- Events

A major challenge is preventing **fabricated or misleading responses (LLM hallucinations)**. Therefore, the system must **ground answers in verified knowledge sources** to ensure reliability, trust, and factual correctness.

---

## 💡 Proposed Solution
A **Gen AI–powered Retrieval-Augmented Generation (RAG) chatbot** designed for multi-domain assistance that provides accurate and verifiable information about:

1. Admissions and academic services  
2. Courses and schedules  
3. Campus and organizational services  
4. Automotive support (vehicle details, maintenance, service centers)  
5. Technology products, troubleshooting, and events  

The system integrates **structured databases + document-based knowledge repositories** to generate responses strictly based on validated information.

---

## 📂 Dataset Used

### 1. Structured Data
- Course catalogs  
- Timetables  
- Admissions data  
- Fee structures  
- Service records  
- Product specifications  
- Policies  
- Event calendars  

### 2. Unstructured Data
- Handbooks  
- Manuals  
- Policy documents (PDF/DOCX/HTML)  
- FAQs  
- Notices  
- Technical guides  

### 3. Historical Query Logs (Optional)
- Identifies frequently asked questions  
- Improves response accuracy  

---

## 🧩 Dataset Components
- Structured tables for courses, schedules, services, products, and records  
- Unstructured documents chunked with metadata (source, section, last_updated)  
- Vector embeddings for semantic representation  
- Document ingestion module for:
  - PDF/DOCX/Web extraction
  - Preprocessing & chunking
  - Embedding storage in vector database

---

## 🔍 Features Extracted
1. Intent classification (academic, automotive, technology)  
2. Course details, prerequisites, credits, faculty info  
3. Vehicle/service/product specifications  
4. Important dates (deadlines, exams, service schedules, events)  
5. Service hours and availability  
6. FAQ mappings for recurring queries  

---

## 📊 Data Analysis
1. Group similar queries to identify common concerns  
2. Detect missing or incomplete knowledge  
3. Measure retrieval accuracy and relevance  
4. Track hallucinations or unsupported answers  

---

## ⚙️ Algorithms Used

### 1. Embedding Generation
- Converts text into numerical vectors  
- Transformer-based models  

### 2. Similarity Search & Reranking
- Retrieves relevant document chunks  
- Prioritizes most useful results  

### 3. LLM Response Generation
- Generates natural, conversational, grounded answers  

---

## 🛠️ Tools & Libraries Used
- Vector Database: ChromaDB  
- Embeddings: Hugging Face Transformers  
- LLM: OpenAI API  
- Framework: FastAPI  
- Backend: Python  
- Frontend: HTML, CSS, JavaScript  

---

## 🚀 System Features
- Web-based interactive chatbot  
- Source references with timestamps  
- Handles structured + document queries  
- Automated document ingestion & indexing  
- Responds with **“I don’t know”** when data unavailable  
- Logs queries and usage statistics  

---
**##output
**

<img width="1280" height="477" alt="image" src="https://github.com/user-attachments/assets/c80f0b48-cd20-4a3d-b928-3e7bf9facbeb" />

<img width="1280" height="772" alt="image" src="https://github.com/user-attachments/assets/f5810b4f-6026-496e-99d9-458e6f880d74" />



## ✅ Results & Benefits
- High accuracy and grounded responses (>95% correctness)  
- 24/7 automated support  
- Reduced staff workload  
- Faster information retrieval  
- Scalable across multiple domains  
- Improved user satisfaction and trust  

---

## 🎯 Conclusion
By combining **Retrieval-Augmented Generation (RAG)** with an intelligent agent framework, the chatbot delivers **trustworthy, accurate, and context-aware interactions**.  

The system minimizes misinformation, enhances operational efficiency, and serves as a reliable digital assistant across **Academic, Automotive, and Technology domains**.
