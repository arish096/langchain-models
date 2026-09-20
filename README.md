🦜🔗 LangChain Models

A structured collection of practical examples demonstrating LLMs, Chat Models, and Embedding Models with LangChain.

Author & Maintainer: Arish Islam

📌 About The Project

LangChain Models is a learning-focused repository created to explore and understand how different types of AI models can be integrated with LangChain.

The repository provides simple, focused examples covering three fundamental model abstractions:

LLMs — Text completion and generation

Chat Models — Conversational and message-based AI

Embedding Models — Text-to-vector representations for semantic applications

The goal is to provide a clean starting point for developers who want to understand the foundations of modern LLM-powered applications before moving into advanced concepts such as RAG, Vector Databases, Agents, and Tool Calling.

🎯 Objectives

This project focuses on building a strong conceptual and practical understanding of LangChain's model ecosystem.

Key objectives

Understand how LangChain interacts with AI models.

Learn the difference between LLMs and Chat Models.

Work with embedding models and vector representations.

Understand model invocation and response generation.

Experiment with different model providers.

Build a foundation for RAG and other GenAI applications.

Keep examples simple enough for learning and experimentation.

🏗️ Repository Structure
langchain-models/
│
├── 📁 1.LLMs/
│   └── LLM examples and experiments
│
├── 📁 2.ChatModels/
│   └── Chat Model examples and experiments
│
├── 📁 3.EmbeddingModels/
│   └── Embedding Model examples and experiments
│
├── 📄 requirements.txt
├── 📄 test.py
└── 📄 README.md

🧠 Core Concepts
1. LLMs

Large Language Models (LLMs) generate text based on a given prompt.

They are useful for understanding the basic:

Prompt → Model → Generated Text


Common applications include:

Text generation

Text completion

Summarization

Question answering

Content generation

NLP experimentation

The 1.LLMs directory contains examples focused on understanding this fundamental interaction.

2. Chat Models

Chat Models are designed around structured conversations rather than simple text prompts.

A typical interaction can be represented as:

System Message
       ↓
Human Message
       ↓
   Chat Model
       ↓
AI Response


They are particularly useful for:

Conversational applications

AI assistants

Multi-turn conversations

Tool calling

Agent-based workflows

Instruction-following applications

The 2.ChatModels directory explores this message-oriented approach.

3. Embedding Models

Embedding Models convert text into numerical vectors that capture semantic information.

Conceptually:

Text
 ↓
Embedding Model
 ↓
Vector Representation
 ↓
Similarity / Retrieval


Embeddings are commonly used in:

Semantic search

Document similarity

Retrieval-Augmented Generation (RAG)

Recommendation systems

Clustering

Vector databases

Knowledge-base search

The 3.EmbeddingModels directory contains examples for understanding this important component of modern AI systems.

🔄 How These Concepts Connect

These three model types form important building blocks for modern Generative AI systems.

                    AI Application
                         │
          ┌──────────────┴──────────────┐
          │                             │
       Chat Model                    LLM
          │                             │
          └──────────────┬──────────────┘
                         │
                    AI Response
                         
                         
                    Documents
                         │
                         ▼
                Embedding Model
                         │
                         ▼
                  Vector Store
                         │
                         ▼
                  Retrieval / Search
                         │
                         ▼
                    RAG System
                         │
                         ▼
                   Chat Model


Understanding these individual components makes it easier to build complete AI applications.

🛠️ Tech Stack
Technology	Purpose
🐍 Python	Programming language
🦜🔗 LangChain	LLM application framework
🤖 LLMs	Text generation
💬 Chat Models	Conversational AI
🔢 Embeddings	Semantic vector representations
🔐 API Providers	Access to external AI models
🚀 Getting Started
Prerequisites

Make sure you have the following installed:

Python 3.10+

pip

Git

API credentials for the model provider used by an example

1. Clone the Repository
git clone https://github.com/arish096/langchain-models.git

cd langchain-models

2. Create a Virtual Environment
Windows
python -m venv .venv
.venv\Scripts\activate

macOS / Linux
python3 -m venv .venv
source .venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

🔐 Environment Configuration

If an example requires an API key, configure it through an environment variable.

For example:

OPENAI_API_KEY=your_api_key_here


For local development, you may use a .env file if the corresponding example loads environment variables.

OPENAI_API_KEY=your_api_key_here

⚠️ Security

Never commit API keys or other secrets to GitHub.

Add sensitive files such as .env to .gitignore:

.env
.venv/
__pycache__/
*.pyc

▶️ Running The Examples

After installing the dependencies, navigate to the relevant directory and run the desired Python file.

For example:

python test.py


Or:

python <example-file>.py


Each directory is organized around a specific model concept, making it easy to experiment with individual components.

📚 Learning Roadmap

A recommended learning path for this repository:

LLMs
 │
 ▼
Chat Models
 │
 ▼
Embedding Models
 │
 ▼
Vector Databases
 │
 ▼
Retrieval
 │
 ▼
RAG
 │
 ▼
Agents & Tools
 │
 ▼
Production AI Applications


This progression helps build understanding from basic model interaction to complete AI application architectures.

💡 What You Can Build Next

After understanding the examples in this repository, you can extend the concepts into projects such as:

🤖 AI Chatbot

📚 Document Q&A System

🔎 Semantic Search Engine

🧠 RAG Application

🗃️ Vector Database Search

🛠️ Tool-Using AI Agent

📄 PDF Question Answering System

💬 Context-Aware AI Assistant

🤝 Contributing

Contributions and improvements are welcome.

If you would like to contribute:

Fork the repository.

Create a new feature branch.

Add or improve an example.

Test your changes.

Commit your changes.

Open a Pull Request.

git checkout -b feature/new-example
git add .
git commit -m "Add new LangChain example"
git push origin feature/new-example


Please keep contributions:

Simple and focused

Well documented

Easy to understand

Consistent with the existing project structure

👨‍💻 Author
Arish Islam

Developer & Maintainer

GitHub:
https://github.com/arish096

This repository is maintained by Arish Islam as a practical learning resource for exploring LangChain and modern Generative AI development.

📄 License

If you plan to distribute this project as open source, add an appropriate license such as the MIT License.

Example:

MIT License

Copyright (c) 2026 Arish Islam

⭐ Show Your Support

If you find this repository useful for learning LangChain or Generative AI, consider giving it a ⭐ on GitHub.

Your support helps improve and expand the project.

<div align="center">
🦜🔗 Learn. Build. Experiment. Ship.

Built and maintained by Arish Islam

</div>
