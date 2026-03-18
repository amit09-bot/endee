# 🧠 AI Resume Ranking System using RAG & Endee

## 📌 Project Overview

This project implements an **AI-powered Resume Ranking System** using **Retrieval Augmented Generation (RAG)** principles.
It helps match resumes with a given job description using **semantic search** instead of keyword matching.

The system leverages vector embeddings and a custom implementation inspired by **Endee (vector database)** to retrieve the most relevant resumes and generate meaningful explanations.

---

## 🎯 Key Features

* 🔍 Semantic search for intelligent resume matching
* 🤖 AI/ML-based embedding generation using transformer models
* 📊 Resume ranking based on similarity scores
* 🧾 RAG-based explanation of results
* ⚡ Fast and lightweight vector database (Endee-style)

---

## 🏗️ System Architecture

```
User Input (Job Description)
        ↓
Text Embedding (Sentence Transformer)
        ↓
Vector Database (Endee-based Storage)
        ↓
Similarity Search (Cosine Similarity)
        ↓
Top Matching Resumes
        ↓
RAG-based Explanation Output
```

---

## 🛠️ Tech Stack

* **Python**
* **Sentence Transformers**
* **NumPy**
* **Endee (Concept-based implementation)**

---

## 📂 Project Structure

```
project/
│
├── notebook.ipynb        # Main implementation
├── README.md             # Project documentation
└── data/                 # Sample resume data (optional)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2️⃣ Install Dependencies

```
pip install sentence-transformers numpy
```

### 3️⃣ Run the Project

Open the notebook in **Google Colab** or Jupyter and execute all cells.

---

## 🚀 How It Works

1. Resumes are converted into vector embeddings
2. Job description is also embedded into vector form
3. Similarity search retrieves the most relevant resumes
4. RAG generates a contextual explanation of the results

---

## 📸 Sample Output

```
Top Matching Resumes:

1. AI engineer with NLP experience
2. Data scientist with deep learning expertise
3. Python developer with ML background

Reason:
These candidates match based on semantic similarity to the job description.
```

---

## 📌 Use of Endee

The official Endee repository was forked as required.
Since it is not directly installable as a Python package, a **custom lightweight implementation inspired by Endee's vector storage concept** was used to simulate vector database functionality.

---

## 🔮 Future Enhancements

* 📄 Upload and parse PDF resumes
* 🌐 Build a web interface using Streamlit
* 🧠 Integrate advanced LLMs (like GPT) for better explanations
* ☁️ Deploy as a cloud-based API

---

## 👨‍💻 Author
Amit Dhavaleshwar

---

## ⭐ Acknowledgment

Special thanks to the **Endee project** for inspiring the vector database design used in this system.
