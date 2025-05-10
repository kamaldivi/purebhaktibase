# 🤖 AI Agent – PureBhaktiBase

This package is responsible for the **AI-driven core functionality** of PureBhaktiBase, which enables intelligent search, retrieval, and response generation based on Śrīla Gurudev’s teachings.

---

## ✨ Purpose

The `ai-agent` module powers:

- 📄 **Retrieval-Augmented Generation (RAG):**
  - Connects the user's query to relevant content using embeddings and context-aware search.

- 🌐 **Language Support:**
  - Translates or provides responses in multiple languages (e.g., English, Hindi, Tamil, Telugu).

- 🧠 **Advanced Features:**
  - Enables **chapter/page/keyword-based search**
  - Supports **summaries, correlations, and thematic insights**

---

## 🛠️ Tech Stack

| 🔧 **Tool/Library**      | 📄 **Usage**                                       |
|--------------------------|---------------------------------------------------|
| Python (or Node.js)      | Core development language                        |
| LangChain / Haystack     | RAG pipeline framework (if Python)               |
| OpenAI / Hugging Face    | LLM APIs for text generation                     |
| Sentence Transformers    | Embedding models                                 |
| FastAPI / Flask / Express| Expose AI as an API (if applicable)              |
| Translation API          | Multi-language response (Google/Azure/others)    |

---

## 📑 Folder Structure

| 📁 **Folder/File**       | 📄 **Description**                                              |
|--------------------------|-----------------------------------------------------------------|
| `/src/`                  | Source code for AI pipelines, handlers, and utilities          |
| `/models/`               | Pre-trained models, custom fine-tuned models (if any)           |
| `/tests/`                | Unit tests for AI components                                   |
| `requirements.txt`       | Python dependencies (if applicable)                            |
| `README.md`              | This documentation file                                        |

---

## 🚀 Getting Started (Python Example)

1️⃣ **Set up virtual environment:**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate