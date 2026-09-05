# LangChain Models

A collection of practical examples demonstrating how to work with different **LLM, Chat Model, and Embedding Model providers using LangChain and Python**.

## 📚 Project Structure

```text
LangChain Models/
│
├── 1.LLM/
│   └── llm_demo.py
│
├── 2.ChatModels/
│   ├── 1_chatmodel_openai.py
│   ├── 2_chatmodel_anthropic.py
│   ├── 3_chatmodel_google.py
│   ├── 4_chatmodel_hf_api.py
│   └── 5_chatmodel_hf_local.py
│
├── 3.EmbeddedModels/
│   ├── 1_embedding_openai_query.py
│   ├── 2_embedding_openai_docs.py
│   ├── 3_embedding_hf_local.py
│   └── 4_document_similarity.py
│
├── requirements.txt
└── test.py
```

## 🚀 Topics Covered

### 1. LLMs

Examples of working with Large Language Models through LangChain.

### 2. Chat Models

Examples using different providers:

* OpenAI
* Anthropic
* Google Gemini
* Hugging Face API
* Hugging Face Local Models

### 3. Embedding Models

Examples covering:

* OpenAI embeddings
* Hugging Face local embeddings
* Query embeddings
* Document embeddings
* Document similarity

## 🛠️ Technologies

* Python
* LangChain
* LangChain Integrations
* OpenAI
* Anthropic
* Google Gemini
* Hugging Face
* Transformers
* PyTorch

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/vivekraq/langchain-models.git
```

Navigate to the project:

```bash
cd langchain-models
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🔑 API Keys

Some examples require API keys from external providers.

Set your API keys as environment variables instead of writing them directly in your Python files.

Example:

```text
OPENAI_API_KEY=your_api_key
HF_TOKEN=your_huggingface_token
```

**Never commit API keys or other secrets to GitHub.**

## ▶️ Running the Examples

For example:

```bash
python 1.LLM/llm_demo.py
```

Chat model examples:

```bash
python 2.ChatModels/1_chatmodel_openai.py
```

Embedding examples:

```bash
python 3.EmbeddedModels/1_embedding_openai_query.py
```

## 🎯 Purpose

This repository is created for learning and practicing **LangChain model integrations**, including LLMs, chat models, and embedding models, as a foundation for building GenAI applications such as **RAG systems, AI assistants, and AI agents**.

## 👨‍💻 Author

**Vivek Rawat**

GitHub: https://github.com/vivekraq
