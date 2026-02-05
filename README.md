# HR & Compliance RAG System (LangChain)
### XDT AI — XavierDataTech  
AI‑powered document intelligence for HR, PRL/OHS & Compliance

This project demonstrates how Retrieval‑Augmented Generation (RAG) can be applied to HR, Workforce, and Occupational Safety (PRL/OHS) documentation.  
It provides a modular, production‑ready architecture for building intelligent assistants capable of answering policy questions, summarizing regulations, and extracting structured insights from unstructured HR documents.

---

## 🚀 Project Overview
HR and compliance teams manage large volumes of documents:

- Policies & procedures  
- PRL/OHS manuals  
- Risk assessments  
- Contracts & labor regulations  
- Internal communications  
- Training materials  

This project uses **LangChain** to create an AI assistant that can:

- Retrieve relevant sections from large documents  
- Generate accurate, context‑aware answers  
- Summarize policies and regulations  
- Extract key entities and obligations  
- Support HR and Safety teams with instant knowledge access  

---

## 🧱 Architecture
The system follows a clean, modular RAG pipeline:

### **1. Document Ingestion**
- PDF, DOCX, TXT ingestion  
- Chunking with semantic boundaries  
- Metadata extraction (source, section, category)

### **2. Embeddings & Vector Store**
- Sentence‑level embeddings  
- Vector database (FAISS or Chroma)  
- Metadata‑aware retrieval  

### **3. Retrieval Pipeline**
- Hybrid search (semantic + keyword)  
- Re-ranking for HR/PRL context  
- Source‑grounded context windows  

### **4. LLM Reasoning Layer**
- Context‑aware generation  
- Policy‑aligned responses  
- Safety filters for compliance‑sensitive content  

### **5. Optional Extensions**
- Multi‑document QA  
- Policy comparison  
- Automated compliance summaries  
- Integration with HRIS or SharePoint  

---

## 📂 Repository Structure

---

## 🧰 Tech Stack
- **LangChain**  
- **Python** (pandas, pydantic, PyPDF)  
- **Vector DB:** FAISS / Chroma  
- **LLM orchestration**  
- **Optional:** Azure OpenAI / AWS Bedrock  

---

## 🔍 Example Use Cases
- “What does our PRL manual say about ergonomic risks?”  
- “Summarize the onboarding policy for new hires.”  
- “What are the mandatory training requirements for warehouse staff?”  
- “Compare the 2023 and 2024 safety procedures.”  

---

## 🎯 Objectives
- Provide a **reference RAG architecture** for HR & Compliance  
- Demonstrate best practices for document intelligence  
- Enable fast, accurate access to critical policies  
- Build a foundation for future **AI‑driven HR automation**  

---

## 📫 Contact
**Author:** Xavier Mareca  
**Brand:** XDT AI — XavierDataTech  
**LinkedIn:** https://www.linkedin.com/in/xaviermareca  
**Email:** xavierdatatech@outlook.com  

---

### ✨ XDT AI — Data with Purpose
