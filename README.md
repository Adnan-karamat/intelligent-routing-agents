# intelligent-routing-agents
A Python-based multimodal Agentic RAG system with QA, Task, and Analysis agents coordinated by a Mistral-style manager. Integrates FAISS for memory, BLIP for image captioning, and a domain-specific knowledge base for scalable, interpretable, and context-aware AI decision-making.
# Agentic-RAG-System

## Overview
This repository implements a Python-based multimodal **Agentic RAG (Retrieval-Augmented Generation) system**, featuring specialized **QA**, **Task**, and **Analysis** agents coordinated by a **Mistral-style manager**.  
The system integrates **FAISS** for semantic memory, **BLIP** for image captioning, and a domain-specific knowledge base for context-aware, interpretable, and scalable AI decision-making.

---

## Features
- Multimodal input support (text & images)
- Dynamic query routing via a Mistral-style manager
- Specialized agents for QA, Task, and Analysis
- Semantic memory integration using FAISS
- Image captioning with BLIP
- Context-aware, explainable AI decisions

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/Agentic-RAG-System.git
cd Agentic-RAG-System
pip install transformers accelerate torch sentence-transformers faiss-cpu blip requests pandas numpy
pip install fais
pip install Pillow

Agentic-RAG-System/
│
├─ Agentic-RAG-System.ipynb        # Main notebook
├─ README.md                       # Project documentation
├─ requirements.txt                # Python dependencies (optional)
└─ data/                           # Input data files (if applicable)
