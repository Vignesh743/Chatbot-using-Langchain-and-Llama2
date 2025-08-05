# Chatbot-using-Langchain-and-Llama2
## ✅ Setup Instructions

### Step 1: Create and Activate Conda Environment

```bash
conda create -n venv python=3.10 -y
conda activate venv
```

---

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Step 3: Configure Environment Variables

Create a `.env` file in the root directory and add your LangChain API key:

```env
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=Tutos
```

---

### Step 4: Install and Run Ollama

1. Download Ollama: https://ollama.com/download
2. Open terminal or CMD and run:
```bash
ollama run llama2
```

> This command downloads the LLaMA2 model and starts it locally.

---

### Step 5: Run the Streamlit App

Make sure Ollama is running, then launch the chatbot:

```bash
streamlit run app.py
```
