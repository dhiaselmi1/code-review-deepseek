# 🔍 Code Review Assistant (DeepSeek-Coder via Ollama)

This tool provides smart code reviews powered by the [DeepSeek-Coder](https://deepseek.com/) model running locally with [Ollama](https://ollama.com/). You can paste any code into the app and get helpful feedback on bugs, best practices, or optimization tips.

---

## 🚀 Features

- 🧠 AI-powered code review using DeepSeek-Coder
- ⚡ FastAPI backend to process code review requests
- 🌐 Streamlit frontend for a user-friendly interface
- 🖥️ Runs locally — no API key or cloud dependency

---

## 📦 Tech Stack

- Python 3.10+
- FastAPI
- Streamlit
- Requests
- Ollama (for local model inference)

---

## 🛠️ How to Use

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/code-review-deepseek.git
cd code-review-deepseek
```
### 2. Create and activate a Python virtual environment**:
    ```bash
    python -m venv venv
    # On macOS/Linux:
    source venv/bin/activate
    # On Windows (PowerShell):
    .\venv\Scripts\Activate.ps1
    # Or Windows (CMD):
    .\venv\Scripts/activate.bat
    ```

      ## ▶️ Running the Application

1.  **Start the FastAPI backend server**:
    ```bash
    uvicorn backend.main:app --reload
    ```

2.  **In a new terminal, start the Streamlit frontend**:
    ```bash
    streamlit run frontend/app.py
    ```
    Open your browser to `http://localhost:8501`.

---
