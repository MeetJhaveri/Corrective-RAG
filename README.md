# 🔍 Corrective RAG

**Corrective Retrieval‑Augmented Generation (cRAG)** — an enhanced approach to standard RAG that improves the quality and relevance of generated answers by evaluating and refining retrieved context.

---

## 🚀 Project Overview

**RAG (Retrieval‑Augmented Generation)** combines a large language model (LLM) with a retrieval mechanism: relevant documents or knowledge chunks are retrieved from a corpus or vector store, and the model generates answers conditioned on this context.

**Corrective RAG (cRAG)** improves on this workflow by:  
- Evaluating the relevance and quality of retrieved documents  
- Filtering or refining poor context  
- Optionally supplementing retrieval with additional sources  
- Ensuring more accurate and reliable answers  

**Key difference:** Standard RAG passes retrieved documents directly to the model, whereas Corrective RAG actively assesses and corrects the context before generation, reducing hallucinations and improving answer accuracy.

---

## 🛠️ Implementation Highlights

- Implemented a **Corrective RAG pipeline** to demonstrate evaluation and refinement of retrieved context  
- Integrated with **vector stores** (FAISS/Chroma) for efficient document retrieval  
- Designed to work with any **LLM backend** (OpenAI, Llama2, etc.)  
- Modular approach for **retrieval, evaluation, and corrective steps**

---

## 📁 Repository Structure

