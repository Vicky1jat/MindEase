# 🧠 MindMate – Your Personal Companion for Mental Well-being.

**MindMate** is a locally hosted mental health chatbot designed to provide supportive, context-aware responses to questions related to emotional well-being, stress, anxiety, depression, therapy, and more. It uses Retrieval-Augmented Generation (RAG) to reference preloaded mental health resources like therapy manuals, CBT/DBT guides, and psychology texts — ensuring reliable and private responses without an internet connection.

---

## 🔍 Features

- 💬 Ask anything related to mental health and well-being
- 🧠 Powered by **Mistral 7B**, running locally with Ollama
- 📚 Answers are grounded in preloaded trusted mental health documents
- 🔎 Uses **semantic search** to retrieve the most relevant context
- 💾 Cached vector store for faster performance
- 🛡️ Entirely offline — your data never leaves your machine

---

## 🧰 Tech Stack

| Component            | Tool / Library                                 |
|---------------------|------------------------------------------------|
| LLM Backend          | `mistral:7b` via Ollama                        |
| Document Loading     | `DirectoryLoader`, `PyPDFLoader`              |
| Text Chunking        | `RecursiveCharacterTextSplitter`              |
| Embedding Model      | `all-MiniLM-L6-v2` (HuggingFace)              |
| Vector Store         | FAISS                                          |
| Retrieval Logic      | LangChain’s `RetrievalQA`                     |
| Chat Interface       | Streamlit                                     |

## 📸 Screenshot
![Mental Health Chatbot](https://github.com/SANSKARKURUDE/Mental-Health-Chatbot/blob/main/Screenshot%202025-07-09%20010209.png)
