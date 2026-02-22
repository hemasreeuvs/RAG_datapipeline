
# 🤖 Project: PDF Intelligence with RAG

A Python-based system that allows you to "talk" to your documents. This project uses **Retrieval-Augmented Generation (RAG)** to ensure AI answers are based on facts, not guesses.

---

## 💡 The Big Picture

### 1. What is an LLM?
Think of an **LLM** (Large Language Model) as a genius who has read the whole internet but has a "memory cutoff." It doesn't know about your private files or things that happened today.

#  RAG(Retrieval Augumented Generation)
### 2. What is RAG? (The Upgrade) 
**RAG** gives that genius an "Open Book." 
* **Without RAG:** The AI might hallucinate (make things up) when asked about your specific data.
* **With RAG:** The AI searches your files first, finds the facts, and then answers.

---

## 🛠️ How it Works (The Workflow)

1.  **Ingest:** We load your PDFs (like `Hema_Resume.pdf`).
2.  **Chunk:** We break the text into small, digestible pieces.
3.  **Embed:** We turn those pieces into "Math Vectors" so the computer understands the meaning.
4.  **Retrieve:** When you ask a question, we find the most relevant math matches.
5.  **Answer:** The LLM summarizes those matches into a human response.

---

## Quick Start

1. **Install everything you need:**
   ```bash
   pip install -r requirement.txt

---
