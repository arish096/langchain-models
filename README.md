🦜🔗 LangChain Models
<p align="center"> <b>Practical & Structured Examples of LLMs, Chat Models and Embedding Models with LangChain</b> </p> <p align="center"> <a href="https://github.com/arish096/langchain-models"> <img src="https://img.shields.io/github/stars/arish096/langchain-models?style=for-the-badge&logo=github" alt="GitHub Stars"> </a> <a href="https://github.com/arish096/langchain-models"> <img src="https://img.shields.io/github/forks/arish096/langchain-models?style=for-the-badge&logo=github" alt="GitHub Forks"> </a> <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python" alt="Python"> <img src="https://img.shields.io/badge/LangChain-Framework-green?style=for-the-badge" alt="LangChain"> </p>
📖 About

LangChain Models is a practical repository created by Arish Islam to explore and understand the core model abstractions used in modern Generative AI applications with LangChain.

The repository focuses on three fundamental areas:

🤖 LLMs — Large Language Models for text generation

💬 Chat Models — Message-based conversational AI

🔢 Embedding Models — Converting text into vector representations

The examples are intentionally organized and easy to follow, making this repository useful for developers who are learning LangChain, LLM application development, and Generative AI.

🎯 What You'll Learn

By exploring this repository, you will understand:

How to work with LLMs using LangChain

How Chat Models differ from traditional LLMs

How messages are handled in conversational AI

How Embedding Models represent text as vectors

How model abstractions fit into AI applications

The foundation behind semantic search and RAG

How these components can be combined to build GenAI applications

📂 Project Structure
langchain-models/
│
├── 📁 1.LLMs/
│   └── LLM examples
│
├── 📁 2.ChatModels/
│   └── Chat Model examples
│
├── 📁 3.EmbeddingModels/
│   └── Embedding Model examples
│
├── 📄 requirements.txt
├── 📄 test.py
└── 📄 README.md

🧠 Core Concepts
🤖 1. LLMs

Large Language Models (LLMs) generate text based on a given input or prompt.

Prompt
   ↓
  LLM
   ↓
Generated Response


LLMs can be used for:

Text generation

Text completion

Summarization

Question answering

Content generation

Natural Language Processing

The 1.LLMs directory contains examples for understanding basic LLM interactions with LangChain.

💬 2. Chat Models

Chat Models are designed specifically for conversational interactions and work with structured messages.

System Message
       ↓
Human Message
       ↓
   Chat Model
       ↓
  AI Response


They are commonly used for:

AI chatbots

Conversational assistants

Multi-turn conversations

Tool calling

Agent workflows

Instruction-based applications

Examples and experiments can be found inside the 2.ChatModels directory.

🔢 3. Embedding Models

Embedding Models convert text into numerical vectors that represent the semantic meaning of the text.

Text
 ↓
Embedding Model
 ↓
Vector Representation
 ↓
Similarity / Retrieval


Embeddings are widely used in:

Semantic Search

RAG (Retrieval-Augmented Generation)

Document Similarity

Recommendation Systems

Clustering

Vector Databases

Knowledge Retrieval

The 3.EmbeddingModels directory contains examples related to embedding models.

🔄 How Everything Connects

These model types are important building blocks of modern AI applications.

                         AI APPLICATION
                               │
                ┌──────────────┴──────────────┐
                │                             │
             LLMs                        Chat Models
                │                             │
                └──────────────┬──────────────┘
                               │
                         AI Response


                         DOCUMENTS
                             │
                             ▼
                    Embedding Model
                             │
                             ▼
                       Vector Store
                             │
                             ▼
                     Semantic Search
                             │
                             ▼
                            RAG
                             │
                             ▼
                       Chat Model
                             │
                             ▼
                       AI Response


Understanding these individual components provides a strong foundation for building complete LLM-powered applications.

🛠️ Tech Stack
Technology	Purpose
🐍 Python	Programming Language
🦜🔗 LangChain	LLM Application Framework
🤖 LLMs	Text Generation
💬 Chat Models	Conversational AI
🔢 Embeddings	Semantic Vector Representation
🗄️ Vector Databases	Similarity Search
🔐 Model APIs	Access to AI Models
🚀 Getting Started
Prerequisites

Make sure you have the following installed:

Python 3.10+

Git

pip

API key for the model provider used by the examples

1. Clone the Repository
git clone https://github.com/arish096/langchain-models.git

2. Navigate to the Project
cd langchain-models

3. Create a Virtual Environment
Windows
python -m venv .venv
.venv\Scripts\activate

macOS / Linux
python3 -m venv .venv
source .venv/bin/activate

4. Install Dependencies
pip install -r requirements.txt

🔐 Environment Variables

Some examples may require API credentials from an external model provider.

Create a .env file in the project root:

OPENAI_API_KEY=your_api_key_here


Or configure the required environment variable according to the provider used by the example.

⚠️ Important

Never commit API keys, passwords, tokens, or other secrets to GitHub.

Add the following to .gitignore:

.env
.venv/
__pycache__/
*.pyc

▶️ Running the Examples

After installing the dependencies, navigate to the relevant directory and run the Python file.

For example:

python test.py


You can also run individual examples:

python <example-file>.py


Each directory focuses on a specific model concept, allowing you to learn and experiment step by step.

🗺️ Learning Roadmap

A recommended learning path:

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
Production AI Apps

💡 What Can You Build Next?

Once you understand the concepts in this repository, you can extend them into real-world projects such as:

🤖 AI Chatbot

📚 PDF Question Answering System

🔎 Semantic Search Engine

🧠 RAG Application

🗃️ Vector Database Search

💬 Context-Aware AI Assistant

🛠️ Tool-Using AI Agent

📄 Document Intelligence System

🤝 Contributing

Contributions, improvements, and new examples are welcome.

Contribution Steps
# Fork the repository

# Create a new branch
git checkout -b feature/new-example

# Make your changes

# Stage changes
git add .

# Commit changes
git commit -m "Add new LangChain example"

# Push the branch
git push origin feature/new-example


Then open a Pull Request.

Contribution Guidelines

Please make sure your contributions are:

Clean and readable

Properly documented

Easy to understand

Focused on a specific concept

Consistent with the existing project structure

👨‍💻 Author
Arish Islam

Developer • AI/ML Enthusiast • LangChain Learner

GitHub:
https://github.com/arish096

This repository is created and maintained by Arish Islam as a practical learning resource for exploring LangChain and Generative AI.

📄 License

This project can be distributed under the MIT License.

If you choose to use the MIT License, add a LICENSE file containing the official MIT License text and update this section accordingly.

⭐ Support

If you found this repository useful, consider giving it a ⭐ on GitHub.

It helps support the project and encourages further development.

<p align="center"> <b>🦜🔗 Learn • Experiment • Build • Ship</b> </p> <p align="center"> Made with ❤️ by <b>Arish Islam</b> </p>
