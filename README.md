#  Generative AI using LangChain.
<p align="center">
  <img src="https://registry.npmmirror.com/@lobehub/icons-static-png/latest/files/dark/langchain.png" width="180" alt="LangChain Logo"/>
</p>


<h3 align="center">
A Complete Generative AI Learning Roadmap & Practical Implementation Guide using LangChain..
</h3>

<p align="center">
  Learn • Build • Deploy AI Applications with Real-World Projects
</p>

----

<div align="center">

![GitHub Repo stars](https://img.shields.io/github/stars/Sakhawathossen04/Generative-AI-using-LangChain?style=social)
![GitHub forks](https://img.shields.io/github/forks/Sakhawathossen04/Generative-AI-using-LangChain?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/Sakhawathossen04/Generative-AI-using-LangChain)
![License](https://img.shields.io/badge/License-MIT-green)
![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![LangChain](https://img.shields.io/badge/LangChain-Framework-black)

</div>

---

#  About This Repository..

This repository is a complete roadmap for learning **Generative AI** with hands-on implementation using **LangChain**.

It contains:

- Beginner to Advanced GenAI Concepts
- LangChain Tutorials & Notes
- Prompt Engineering
- RAG Applications
- AI Agents
- Real-World Projects
- Deployment Guides
- Practical Code Examples

Whether you're a beginner or an AI enthusiast, this repo will help you build real-world AI applications step by step.

---

#  Learning Roadmap

## 1️ AI & NLP Foundations

* Machine Learning Basics
* Deep Learning Fundamentals
* Neural Networks
* NLP Basics
* Tokenization & Embeddings
* Transformers Architecture
* Attention Mechanism

---

## 2️ Generative AI Fundamentals

* Large Language Models (LLMs)
* GPT Models
* BERT & T5
* Prompt Engineering
* Fine-Tuning
* RLHF
* PEFT Techniques

---

## 3️ LangChain Mastery

* LangChain Components
* Chains & Sequential Chains
* Memory Systems
* Prompt Templates
* Output Parsers
* Tools & Agents
* Callbacks & Monitoring

---

## 4️ RAG (Retrieval-Augmented Generation)

* Document Loaders
* Text Splitters
* Embedding Models
* Vector Databases
* Semantic Search
* Context Retrieval
* Advanced RAG Pipelines

---

## 5️ AI Agents & Automation

* Autonomous Agents
* Tool Calling
* API Integration
* Multi-Agent Systems
* AI Workflow Automation

---

## 6️ Real-World Projects

* AI Chatbot
* PDF Question Answering
* AI Resume Analyzer
* Content Generator
* Research Assistant
* AI Code Assistant

---

## 7️ Deployment & Production

* FastAPI Integration
* Streamlit Apps
* Docker Deployment
* API Hosting
* Performance Optimization
* Monitoring & Scaling

---

#  Repository Structure

```bash
Generative-AI-using-LangChain/
│
├── fundamentals/
├── prompt_engineering/
├── langchain_basics/
├── rag_projects/
├── ai_agents/
├── projects/
├── deployment/
├── notebooks/
├── resources/
├── requirements.txt
└── README.md
```

---

#  Getting Started

##  Clone the Repository

```bash
git clone https://github.com/Sakhawathossen04/Generative-AI-using-LangChain.git
```

##  Navigate to Project Folder

```bash
cd Generative-AI-using-LangChain
```

##  Create Virtual Environment

```bash
python -m venv venv
```

## 🔹 Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / MacOS

```bash
source venv/bin/activate
```

---

##  Install Dependencies

```bash
pip install -r requirements.txt
```

---

#  Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key_here
```

---

#  Technologies Used

* Python
* LangChain
* OpenAI API
* Hugging Face
* ChromaDB
* FAISS
* Streamlit
* FastAPI
* Docker

---

#  Example: Simple LangChain Chain

```python
from langchain_openai import ChatOpenAI
from langchain.prompts import PromptTemplate
from langchain.chains import LLMChain

llm = ChatOpenAI(temperature=0.7)

prompt = PromptTemplate(
    input_variables=["topic"],
    template="Explain {topic} in simple words."
)

chain = LLMChain(llm=llm, prompt=prompt)

response = chain.run("Generative AI")

print(response)
```

---

#  Features

✨ Beginner Friendly.
✨ Structured Learning Path.
✨ Real Project Implementations.
✨ Practical Examples
✨ Updated GenAI Resources
✨ Clean Folder Structure
✨ Open Source Learning Repository

---

#  Best Resources

## Official Docs

* LangChain Documentation
  [https://python.langchain.com/](https://python.langchain.com/)

* OpenAI Documentation
  [https://platform.openai.com/docs](https://platform.openai.com/docs)

* Hugging Face
  [https://huggingface.co/](https://huggingface.co/)

---

#  Contributing

Contributions are welcome

If you want to improve this repository:

1. Fork the Repository
2. Create a New Branch
3. Commit Your Changes
4. Push the Branch
5. Create a Pull Request

---

#  License

This project is licensed under the **MIT License**.

---

#  Author

## Sakhawathossen

* GitHub: [https://github.com/Sakhawathossen04](https://github.com/Sakhawathossen04)

---

<div align="center">

### ⭐ If you find this repository useful, don't forget to star the repo!

</div>
