# Experimental RAG – Football Knowledge Base

This repository contains an **experimental Retrieval-Augmented Generation (RAG)** notebook on a small football-related text corpus.
It compares **two chunking configurations (A vs B)** and uses **local components**: SentenceTransformer embeddings, FAISS vector search, and a local LLM via Ollama.

## Contents
- `rag_assignment.ipynb` – main notebook
- `data/` – 10 football `.txt` documents

## Requirements
- Python 3.11+
- Ollama installed and running locally
- Model: `llama3`

## Install
```bash
pip install -U sentence-transformers faiss-cpu scikit-learn pandas requests
