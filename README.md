
# 🧠 Coder-Buddy

**Coder-Buddy** is an AI-powered coding companion that helps developers generate, debug, and explain code instantly.
Built with **FastAPI**, powered by **Groq LLMs**, and designed for developers who want to code faster, learn smarter, and work efficiently.

---

## 🚀 Features

* 🤖 **AI Chat Interface** – Talk to an AI assistant for real-time coding help
* ⚡ **Groq-Powered LLMs** – Experience ultra-fast responses via the Groq API
* 🧩 **Multi-language Code Support** – Python, JavaScript, and more
* 🖥️ **FastAPI Backend** – Lightweight, modular, and production-ready
* 🧠 **Smart Explanations** – Understand complex code snippets easily

---

## 🛠️ Installation Guide

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Coder-Buddy.git
cd Coder-Buddy
```

### 2️⃣ Create a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate       # macOS/Linux
venv\Scripts\activate          # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Set up your Groq API key

Create a `.env` file in your project root directory and add:

```
GROQ_API_KEY=your_api_key_here
```

👉 Get your API key from [https://console.groq.com](https://console.groq.com)

---

## ▶️ Run the Application

Start the FastAPI server:

```bash
uvicorn app:app --reload
```


You’ll see **Coder-Buddy** up and running on your local system!

---

## 💬 Example Interaction

**Prompt:**

> Explain what this function does and how to optimize it.

**Coder-Buddy Output:**

> This function calculates the factorial recursively.
> Optimization: use an iterative loop or memoization to reduce stack calls.

---

## 🧩 Project Structure

```
Coder-Buddy/
│
├── app.py                # Main FastAPI application
├── requirements.txt      # Dependencies list
├── .env                  # API keys (not committed)
├── README.md             # Project documentation
└── utils/                # Helper functions (optional)
```

---

## 📦 Requirements

* Python 3.10 or higher
* pip (latest version)
* Groq API key

---

## 🧑‍💻 Contributing

We welcome contributions!
To contribute:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes and push
4. Create a pull request

---


## 💡 Credits

Developed by **Rishi Kumar Thakur**
