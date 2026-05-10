# 🤖 AI-Agent-With-Python-Ollama-Langchain-RAG

An AI-powered Restaurant Review Question Answering System built using **Python**, **LangChain**, **Ollama**, and **ChromaDB** with Retrieval-Augmented Generation (RAG).

This project allows users to ask questions about restaurant reviews and receive intelligent AI-generated responses using semantic search and local LLMs.

---

# 🚀 Features

* 🔍 Semantic search using vector embeddings
* 🧠 Retrieval-Augmented Generation (RAG)
* 🍕 Restaurant review question answering system
* 🗂️ ChromaDB vector database integration
* 🤖 Local LLM support with Ollama
* 📊 CSV-based restaurant review dataset
* ⚡ Fast retrieval using embeddings
* 🐍 Fully built with Python and LangChain

---

# 🛠️ Tech Stack

* Python
* LangChain
* Ollama
* ChromaDB
* Pandas
* Llama 3.2
* mxbai-embed-large embeddings

---

# 📂 Project Structure

```bash
AI-Agent-With-Python-Ollama-Langchain-RAG/
│
├── main.py
├── vector.py
├── realistic_restaurant_reviews.csv
├── requirements.txt
├── README.md
└── chroma_langchain_db/
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/AI-Agent-With-Python-Ollama-Langchain-RAG.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd AI-Agent-With-Python-Ollama-Langchain-RAG
```

---

## 3️⃣ Create Virtual Environment

# Windows

```bash
python -m venv myenv
myenv\Scripts\activate
```

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🦙 Install Ollama

Download and install Ollama:

https://ollama.com/

Pull required models:

```bash
ollama pull llama3.2
ollama pull mxbai-embed-large
```

---

# ▶️ Run the Project

```bash
python main.py
```

---

# 💬 Example Questions

```bash
Ask your question(q to quit): Which pizza has the best reviews?

Ask your question(q to quit): What do customers say about service quality?

Ask your question(q to quit): Which restaurant has the highest ratings?
```

---

# 🧠 How It Works

1. Restaurant reviews are loaded from CSV
2. Reviews are converted into embeddings
3. ChromaDB stores vector embeddings
4. User asks a question
5. Relevant reviews are retrieved
6. LangChain sends context to Ollama LLM
7. AI generates intelligent response

---

# 📸 Future Improvements

* Streamlit Web UI
* Multi-restaurant support
* Real-time review upload
* Deployment support
* Authentication system
* Sentiment analysis dashboard

---

# 📊 Learning Outcomes

Through this project, I learned:

* Retrieval-Augmented Generation (RAG)
* Vector databases
* Semantic search
* Embedding models
* LangChain pipelines
* Local LLM integration
* AI workflow development

---



