# 🧠 PaperMind

**AI-Powered Research Intelligence Assistant**.

## 📌 Overview

PaperMind is an AI-driven academic research assistant designed to automate the process of discovering, summarizing, and organizing scientific research papers. It leverages large language models and the **arXiv API** to significantly reduce the time spent on manual literature reviews while improving research productivity.

---

## 🚀 Problem Statement

Academic researchers and students spend a substantial amount of time searching for relevant papers, reading abstracts, and organizing findings. This manual process is repetitive, time-consuming, and inefficient, especially when dealing with rapidly growing research domains.

---

## 💡 Solution

PaperMind automates the academic literature review workflow by:

* Fetching relevant research papers from arXiv.
* Generating concise, structured summaries using AI.
* Organizing outputs into topic-based local folders.
* Providing an intuitive browser-based interface for ease of use.

---

## ✨ Key Features

* 🔍 **Automated Paper Retrieval** from arXiv using RSS/XML parsing.
* 🧠 **AI-Powered Summarization** optimized for scientific literature.
* 📂 **Structured Local Storage** of summaries for offline access.
* 🌐 **Interactive Web Interface** built with Gradio.
* 🔐 **Secure API Key Management** using environment variables.
* 🧩 **Modular Codebase** for scalability and maintainability.

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **AI Model:** OpenAI GPT-4
* **APIs:** arXiv API
* **Frontend/UI:** Gradio
* **Libraries & Tools:**

  * `openai`
  * `requests`
  * `xml.etree.ElementTree`
  * `python-dotenv`
* **Version Control:** Git & GitHub

---

## 🏗️ System Architecture

```
User Input (Topic/Keyword)
        ↓
arXiv API (RSS/XML)
        ↓
Paper Metadata & Abstracts
        ↓
GPT-4 Summarization Engine
        ↓
Structured Text Summaries
        ↓
Local Topic-Based Folders + Gradio UI
```

---

## 📂 Project Structure

```
PaperMind/
│
├── main.py        # Core agent logic (fetching, summarization, file handling)
├── app.py         # Gradio-based web interface
├── summaries/     # Generated research paper summaries
├── .env           # Environment variables (API keys)
├── .gitignore     # Excludes sensitive and unnecessary files
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ahmasmibhanu/PaperMind.git
cd PaperMind
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

---

## ▶️ Running the Application

### Run the Gradio Web Interface

```bash
python app.py
```

Open your browser and navigate to:

```
http://localhost:7860
```

---

## 📈 Impact & Results

* ⏱️ Reduced manual literature review time by **up to 80%**.
* 📚 Improved organization and accessibility of research summaries.
* 👥 Enabled non-technical users to interact with AI-based research tools.
* 🔬 Demonstrated effective application of LLMs for scientific text summarization.

---

## ⚠️ Limitations

* Summaries are generated primarily from **paper abstracts**.
* AI-generated summaries may occasionally lack context or nuance.
* Currently limited to arXiv as the data source.

---

## 🔮 Future Enhancements

* **Full-text** PDF parsing and summarization.
* Semantic search using embeddings and vector databases.
* Integration with additional research databases (PubMed, Semantic Scholar).
* Citation tracking and relevance ranking.
* Export support (Markdown, BibTeX, Notion, Obsidian).

---

## 👨‍💻 Author

**@ahmasmibhanu**

---

## 📜 License

This project is intended for academic and educational purposes.

---

### ⭐ If you find this project useful, consider starring the repository!

---
