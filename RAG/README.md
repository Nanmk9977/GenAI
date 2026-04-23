# 🚀 RAG-Based Customer Support Assistant

A **Retrieval-Augmented Generation (RAG)** system that answers user queries from a PDF using embeddings and a Large Language Model.

## 🔹 Features
- PDF-based knowledge retrieval  
- Context-aware answer generation  
- LangGraph workflow for routing  
- Human-in-the-Loop (HITL) escalation  
- Prevents hallucination
  
## 🔹vedio demo: https://drive.google.com/file/d/1HgvpfLnpuORPNHjMGI8hbdCCkF2eWdkk/view?usp=drive_link

## ⚙️ Tech Stack
Python, LangChain, LangGraph, ChromaDB, Google Colab

## 🔄 Workflow
PDF → Chunking → Embeddings → Vector DB → Retrieval → LLM → Decision → Response / HITL

## ▶️ Run (Colab)
- Open the notebook in Google Colab  
- Upload PDF  
- Run all cells step-by-step  
- Test using sample queries  

## 📌 Conclusion
This project demonstrates an effective implementation of a RAG-based system for intelligent query answering.  
It improves accuracy by retrieving relevant context instead of relying only on generation.  
The use of LangGraph enables structured workflow and decision-making.  

HITL ensures safe handling of uncertain or out-of-domain queries.  
Overall, it presents a scalable and reliable approach for real-world AI applications.  

## 🙏 Acknowledgment
Thanks to **Innomatics Research Labs** for guidance.
