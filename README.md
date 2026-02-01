# Semantic Search Engine for Movie Subtitles 🎬🔍

This project builds a **Semantic Search Engine** over a large movie subtitles database using **Sentence Transformers** and **ChromaDB**.  
Instead of keyword matching, it retrieves results based on **meaning (semantic similarity)**.

---

## 🚀 Features

- Reads subtitle data from a **SQLite database**
- Extracts & decodes compressed subtitle files
- Cleans noisy subtitle text (timestamps, ads, formatting)
- Splits subtitles into overlapping text chunks
- Converts text into embeddings using **SentenceTransformer**
- Stores vectors in **ChromaDB**
- Performs fast **semantic search** on natural language queries

---

## 🧠 Tech Stack

- Python  
- SQLite  
- Pandas & NumPy  
- NLTK  
- Sentence Transformers (`all-MiniLM-L6-v2`)  
- ChromaDB  

---

## 📁 Project Workflow

1. Load subtitles from SQLite database  
2. Decode zipped binary content  
3. Clean subtitle text  
4. Chunk long documents  
5. Generate embeddings  
6. Store in vector database  
7. Query using semantic similarity  

---

## ⚙️ Installation

```bash
pip install pandas numpy nltk tqdm sentence-transformers chromadb
