
# 🧠 BrochureFlow AI

**BrochureFlow AI** is a smart, JupyterLab-based tool that automates the creation of professional, humorous, and multilingual brochures for any business — powered by **multishot prompting**, **web scraping**, and **LLM (Large Language Model) APIs** via OpenRouter.

This project demonstrates how you can build an end-to-end AI content pipeline using modern prompting techniques in a structured, reproducible workflow.

---

## 🚀 What It Does

BrochureFlow AI uses a **three-stage pipeline**:

### 1️⃣ Smart Web Analysis
Automatically scrapes your company or product website and identifies meaningful content using AI.

### 2️⃣ Dual-Tone Brochure Generation
Uses large language models to create:
- A **professional** brochure for formal use
- A **humorous** brochure for casual or creative marketing

Both use **multishot prompting** to ensure consistent tone and structure.

### 3️⃣ Thanglish Translation
Translates the brochure into **Thanglish** (Tamil + English) — useful for culturally localized marketing.

## 🛠️ Requirements

Install the required libraries:

```

pip install -r requirements.txt

```

Contents of `requirements.txt`:
```

openai
requests
beautifulsoup4
python-dotenv
ipython

```

---

## 🔑 API Configuration (OpenRouter)

This project uses [OpenRouter](https://openrouter.ai/) to access models like Gemini:

1. Create a free account and get your API key: https://openrouter.ai/keys
2. Create a `.env` file in the same folder as your notebook:
    ```
    OPENROUTER_API_KEY="sk-or-v1-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    ```

---

## ▶️ How To Run It (Step-by-Step)

1. Clone or download this repository
2. Open `BrochureFlow-AI.ipynb` in JupyterLab
3. Create and add your API key to the `.env` file
4. Run the notebook cells in order 🔁
5. Enter the desired company website when prompted — the tool:
   - Scrapes data
   - Generates brochure copies (two tones)
   - Converts them to Thanglish ✨

---

## 💡 Example Use Case

Upload the company URL like: `https://example.com`

You’ll get:

- ✅ About, Product, Careers links automatically selected
- 📄 Two brochure versions written in different tones
- 🌍 A translated "local-flavor" Thanglish version

---

## 🧠 What You'll Learn

This project is perfect if you're learning:

- How to use **LLMs** for structured tasks
- The difference between **zero-, one-, and multishot prompts**
- How to call **OpenRouter APIs** (e.g., Google Gemini models)
- How to **scrape structured website data**
- How to build a **real-world AI content generator**

---

## 🌟 Star This Repo

If you find it helpful, please ⭐ the repo and share feedback!

Thanks

Deepak Antony
