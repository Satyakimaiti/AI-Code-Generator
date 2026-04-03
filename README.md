# 💻 AI Code Generator (LLaMA 3 + Streamlit)

An AI-powered code assistant that can **generate, explain, and debug code** using LLaMA 3 via Groq API.
Built with a simple and clean UI using Streamlit.

---

## 🌐 Live Demo

🔗 https://ai-code-generator-s17.streamlit.app/

---

## 🚀 Features

* ✨ Generate code from natural language prompts
* 📘 Explain code step-by-step
* 🐞 Debug and fix errors in code
* ⚡ Fast responses using LLaMA 3 (Groq API)
* 🎯 Clean and structured output (no unnecessary explanations)
* 📥 Download generated code

---

## 🛠 Tech Stack

* **Frontend:** Streamlit
* **Backend Logic:** Python
* **LLM API:** Groq (LLaMA 3)
* **Libraries:** openai, python-dotenv

---

## 📁 Project Structure

```id="7r7tqf"
ai-code-generator/
│
├── app.py
├── llama_api.py
├── requirements.txt
├── .env
├── .gitignore
├── README.md
└── utils/
    └── prompt_templates.py
```

---

## ⚙️ Setup Instructions (Windows)

### 1. Clone the repository

```id="6d8r0q"
git clone https://github.com/Satyakimaiti/AI-Code-Generator.git
cd AI-Code-Generator
```

---

### 2. Create virtual environment

```id="k3z4jz"
python -m venv venv
venv\Scripts\activate
```

---

### 3. Install dependencies

```id="u6bb9q"
pip install -r requirements.txt
```

---

### 4. Add API Key

Create a `.env` file in root folder:

```id="cbz0zo"
GROQ_API_KEY=your_api_key_here
```

---

### 5. Run the application

```id="4x8q4u"
streamlit run app.py
```

---

## 🧠 How It Works

1. User enters a prompt in the UI
2. Prompt is processed using prompt engineering
3. Request is sent to LLaMA 3 via Groq API
4. AI generates structured output
5. Output is displayed in Streamlit UI

---

## 🎯 Example Prompts

* Write a Python function for binary search
* Explain this Java code
* Fix this error in C++ code

---

## 🔐 Security Note

* API keys are stored in `.env`
* `.env` is excluded using `.gitignore`
* Streamlit deployment uses secure secrets management

---

## 📌 Future Improvements

* Chat history (memory)
* Multi-language detection
* Code execution support
* UI enhancements

---
