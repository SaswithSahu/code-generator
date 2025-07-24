Absolutely! Here's the **complete and professional `README.md` file**, all at once, ready to paste into your project:

---

````markdown
# 💡 Gemini Code Generator

A Streamlit-based web app that uses **Google Gemini (via LangChain)** to dynamically generate clean, well-commented code for programming tasks in **Python, Java, JavaScript, or C++** — with the option to get a detailed step-by-step explanation of the generated code.

---

## 🚀 Features

- 🔹 Code generation using Gemini (`gemini-1.5-flash`)
- 🔹 Step-by-step explanation of generated code
- 🔹 Support for multiple languages: Python, JavaScript, Java, C++
- 🔹 Streamlit UI for simple and interactive usage
- 🔹 `.env`-based secure API key management

---

## 🧠 Tech Stack

- [Streamlit](https://streamlit.io/) – UI and deployment
- [LangChain](https://www.langchain.com/) – LLM orchestration
- [Google Generative AI](https://ai.google.dev/) – via `langchain-google-genai`
- [python-dotenv](https://pypi.org/project/python-dotenv/) – for `.env` API key loading

---

## 📦 Installation

> ✅ Requires **Python 3.9 or above**

### 1. Clone the repository

```bash
git clone https://github.com/SaswithSahu/code-generator.git
cd code-generator
````

### 2. Create and activate virtual environment

```bash
python -m venv venv
# For Windows:
venv\Scripts\activate
# For Mac/Linux:
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install streamlit langchain_google_genai python-dotenv
```

---

## 🔐 Environment Setup

Create a `.env` file in the root directory and add your Gemini API key:

```env
GOOGLE_API_KEY=your_gemini_api_key_here
```

---

## ▶️ Running the App

```bash
streamlit run cod.py
```

Visit `http://localhost:8501` in your browser to use the app.

---

## ✍️ Usage

1. Select a programming language (Python, Java, etc.)
2. Describe what your code should do (e.g., "sort a list", "check for palindrome")
3. Click **"Generate Code"** to view the Gemini-generated code
4. Click **"📘 Explain Code"** for step-by-step explanation
5. *(Coming soon)* Provide test inputs and execute the code for Python

---

## 🧪 Example Tasks

* Add two numbers
* Reverse a string
* Sort a list using bubble sort
* Check if a number is prime
* Implement a calculator class in Java

---


## 🙌 Author

Built by [Saswith Sahu](https://github.com/SaswithSahu)


