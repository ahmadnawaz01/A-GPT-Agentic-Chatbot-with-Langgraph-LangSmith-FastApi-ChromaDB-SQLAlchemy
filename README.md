# A- GPT — Autonomous AI Agentic Chatbot

**A- GPT** is a full-stack, production-grade agentic AI application inspired by ChatGPT. Built using **LangGraph**, **FastAPI**, **Google Gemini**, **ChromaDB**, **SQLAlchemy**, and **AWS**, A- GPT supports multi-threaded conversations, real-time web search, document-based Retrieval-Augmented Generation (RAG), long-term memory persistence, voice control, and dynamic tool calling.

---

## 🌟 Key Features

* **🤖 Autonomous Agent Workflows:** Powered by **LangGraph** for cyclic state graph execution and intelligent tool selection.
* **🧠 Multi-Tier Memory Persistence:**
  * **Short-Term / State Checkpointing:** Managed via **SQLite** for smooth conversation continuation and state recovery.
  * **Long-Term Memory:** Powered by **SQLAlchemy** to store user-specific facts, key details, and preferences across sessions.
* **📄 RAG Document Search:** Upload PDFs, TXT, or markdown files to perform vector similarity searches using **ChromaDB** and **Google Gemini Embeddings**.
* **🌐 Real-Time Web Search:** Integrates **Tavily API** for up-to-date information retrieval from the web.
* **🧮 Math Calculator Tool:** Safely evaluates mathematical expressions for complex problem-solving.
* **🎤 Voice-to-Text Mode:** Direct voice input support using the browser's native Web Speech API.
* **🔀 Multi-Threaded Conversations:** Switch seamlessly between multiple chat threads with persistent history.
* **⚡ Streaming Responses:** Fast, token-by-token streaming powered by FastAPI and LangGraph events.
* **📊 Observability & Tracing:** Integrated with **LangSmith** for deep debugging and performance tracing.

---

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **LLM / AI Model** | Google Gemini (`gemini-2.5-flash`, `gemini-2.5-pro`) |
| **Orchestration** | LangGraph, LangChain Core |
| **Backend Framework** | FastAPI, Uvicorn, Jinja2 Templates |
| **Vector Database** | ChromaDB |
| **Database & ORM** | SQLite, SQLAlchemy |
| **Frontend** | HTML5, CSS3, JavaScript, Web Speech API |
| **Monitoring & Tracing** | LangSmith |

---
