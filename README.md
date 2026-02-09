Active link: https://1minbot.streamlit.app/

# 🏥 MediBot – AI-Powered Medical Document Assistant

MediBot is an AI-powered medical chatbot that allows users to query medical documents (PDFs) using **Retrieval-Augmented Generation (RAG)**.  
It combines **FAISS vector search**, **LangChain**, **HuggingFace embeddings**, and **Groq LLMs** for fast and accurate responses.

---

## 🚀 Features

- 📄 Load and process medical PDFs
- ✂️ Chunk documents intelligently
- 🧠 Generate embeddings using Sentence Transformers
- 📦 Store and retrieve vectors using FAISS
- 🤖 Query documents using Groq LLM (LLaMA 3)
- 🔐 Secure API key handling with `.env`

---

## 🖼️ Example Outputs

### 🔹 Example 1: Querying Medical Knowledge

<img width="1160" height="860" alt="Screenshot 2026-02-09 131523" src="https://github.com/user-attachments/assets/6e12c77f-3be8-4d15-a662-d14dfd00c72c" />


### 🔹 Example 2: Context-Based Answer Generation

<img width="1002" height="703" alt="Screenshot 2026-02-09 131536" src="https://github.com/user-attachments/assets/3d70a552-9ba4-408f-9ddf-21a0f70f0718" />

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **LangChain**
- **Groq (LLaMA-3.1-8B / 70B)**
- **FAISS**
- **HuggingFace Sentence Transformers**
- **uv / pip**

---

## 📂 How It Works

1. **PDF Ingestion**
   - Medical PDFs are loaded from the `data/` folder.

2. **Text Chunking**
   - Documents are split into overlapping chunks for better retrieval.

3. **Vector Store Creation**
   - Chunks are converted into embeddings and stored in FAISS.

4. **RAG Querying**
   - User questions retrieve relevant chunks.
   - Groq LLM generates answers grounded in document context.

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Ghalib18/mediBot.git
cd mediBot


