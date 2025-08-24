# 📰 News Summarizer & Bias Detector

## 📌 Overview
This project is an **AI-powered News Summarizer & Bias Detector** that allows users to input a **news article URL** or **paste raw text**.  
The app then:
- **Summarizes the article** into simple and clear language.  
- Provides **different summary tones**:
  - 🟢 Neutral Summary  
  - 📑 Fact-only Summary  
  - 👶 Explain Like I’m 10  
- **Analyzes bias** by detecting tone and sentiment across multiple sources, highlighting whether the content leans **positive, negative, or neutral**.  

The goal is to make news more **accessible, unbiased, and easy to understand**.

---

## 🚀 Features
- ✅ Input via **URL** or **pasted text**
- ✅ Summarization in **different styles** (Neutral, Fact-only, Simplified)
- ✅ **Bias detection** using sentiment analysis
- ✅ Easy-to-read summaries for all audiences
- ✅ Web-based interactive UI (if hosted)

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript (or Streamlit/Gradio for quick UI)  
- **Backend:** Python  
- **Libraries & Tools:**
  - `requests` → Fetch news content from URLs  
  - `BeautifulSoup` → Extract article text  
  - `transformers` (Hugging Face) → Summarization model  
  - `nltk` / `textblob` / `vaderSentiment` → Sentiment & bias analysis  
  - `flask` / `fastapi` (optional) → API service  

---

## 📂 Project Structure

