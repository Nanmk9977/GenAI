# 🚀 RAG-Based Customer Support Assistant

A **Retrieval-Augmented Generation (RAG)** system that answers user queries from a PDF using embeddings and a Large Language Model.

## 🔹 Features
- PDF-based knowledge retrieval  
- Context-aware answer generation  
- LangGraph workflow for routing  
- Human-in-the-Loop (HITL) escalation  
- Prevents hallucination  

## ⚙️ Tech Stack
Python, LangChain, LangGraph, ChromaDB, Streamlit

## 🔄 Workflow
PDF → Chunking → Embeddings → Vector DB → Retrieval → LLM → Response / HITL

## 🚨 HITL
Escalates queries when:
- No relevant context  
- Low confidence  
- Out-of-domain questions  

## ▶️ Run
```bash
pip install -r requirements.txt
streamlit run app.py
