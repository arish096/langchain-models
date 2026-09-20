<div align="center">

# 🦜🔗 LangChain Models
### **Practical & Structured Examples of LLMs, Chat Models, and Embedding Models with LangChain**

[![GitHub Stars](https://img.shields.io/github/stars/arish096/langchain-models?style=for-the-badge&logo=github)](https://github.com/arish096/langchain-models/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/arish096/langchain-models?style=for-the-badge&logo=github)](https://github.com/arish096/langchain-models/network/members)
[![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![LangChain Framework](https://img.shields.io/badge/LangChain-Framework-green?style=for-the-badge)](https://www.langchain.com/)

</div>

---

## 📖 About

**LangChain Models** is a hands-on, practical repository created by **Arish Islam** to help developers explore and master the core model abstractions used in modern Generative AI applications with LangChain.

This project focuses on three fundamental pillars of GenAI:
* **🤖 LLMs:** Large Language Models for text generation and completion.
* **💬 Chat Models:** Message-based conversational AI and agents.
* **🔢 Embedding Models:** Converting text into vector representations for semantic understanding.

---

## 🎯 What You'll Learn

* How to work with core LLMs using LangChain abstractions.
* The difference between text-based LLMs and structured Chat Models.
* How conversational messages and histories are handled.
* How Embedding Models map text to vector spaces.
* The foundational concepts behind **Semantic Search**, **Vector Databases**, and **RAG (Retrieval-Augmented Generation)**.

---

## 📂 Project Structure

```text
langchain-models/
│
├── 📁 1.LLMs/              # LLM generation and completion examples
├── 📁 2.ChatModels/        # Chat models, prompts, and message handling
├── 📁 3.EmbeddingModels/   # Text embeddings and vector representations
│
├── 📄 requirements.txt     # Project dependencies
├── 📄 test.py              # Quick test/experimentation script
└── 📄 README.md            # Project documentation

---

## 🧠 Core Concepts

### 🤖 1. LLMs

Large Language Models generate text based on an input prompt. Ideal for text completion, summarization, and content generation.

```text
Prompt ──> [ LLM ] ──> Generated Response

```

### 💬 2. Chat Models

Chat Models handle multi-turn conversations using structured messages (`SystemMessage`, `HumanMessage`, `AIMessage`). Ideal for chatbots and AI agents.

```text
System/Human Messages ──> [ Chat Model ] ──> AI Response

```

### 🔢 3. Embedding Models

Embedding Models convert text into numerical vectors to capture semantic meaning, forming the foundation of vector search and RAG systems.

```text
Text ──> [ Embedding Model ] ──> Vector Representation ──> Semantic Search

```

---

## 🚀 Getting Started

### Prerequisites

* **Python 3.10+** installed on your system.
* **Git** for cloning the repository.
* An active API key from your preferred model provider (e.g., OpenAI).

### 1. Clone the Repository

```bash
git clone [https://github.com/arish096/langchain-models.git](https://github.com/arish096/langchain-models.git)
cd langchain-models

```

### 2. Create and Activate a Virtual Environment

**Windows:**

```bash
python -m venv .venv
.venv\Scripts\activate

```

**macOS / Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate

```

### 3. Install Dependencies

```bash
pip install -r requirements.txt

```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory of your project and configure your API keys securely:

```env
OPENAI_API_KEY=your_api_key_here

```

> **⚠️ Security Warning:** Never commit your `.env` file or API credentials to GitHub. Make sure `.env` and `.venv/` are included in your `.gitignore`.

---

## ▶️ Running the Examples

Navigate to any directory or run the test script to see the components in action:

```bash
python test.py

```

Or run individual component files:

```bash
python <example-file>.py

```

---

## 🗺️ Learning Roadmap

```text
LLMs ➔ Chat Models ➔ Embedding Models ➔ Vector Databases ➔ Retrieval ➔ RAG ➔ Agents & Tools ➔ Production AI Apps

```

---

## 💡 What Can You Build Next?

Once you are comfortable with these core models, you can expand them into real-world applications:

* 🤖 **AI Chatbot** with memory
* 📚 **PDF QA System** using local documents
* 🔎 **Semantic Search Engine** with vector stores
* 🧠 **RAG (Retrieval-Augmented Generation)** application
* 🛠️ **Tool-Using AI Agent**

---

## 🤝 Contributing

Contributions, feature additions, and bug fixes are always welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Arish Islam**

* Developer • AI/ML Enthusiast • LangChain Learner
* **GitHub:** [@arish096](https://github.com/arish096?utm_source=gemini)

---

### **🦜🔗 Learn • Experiment • Build • Ship**

Made with ❤️ by **Arish Islam**

If you found this repository helpful, please consider giving it a **⭐** on GitHub!
