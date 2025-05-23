# 📰 Fake News Detection Web App

A machine learning-based web application to detect fake news using Natural Language Processing (NLP) and the PassiveAggressiveClassifier. The app is built using Streamlit and can predict whether a given news article is real or fake.

## 🚀 Demo

Try the app using ngrok (if deployed) or run locally to access at `http://localhost:8501`.

---

## 📌 Features

- Input any news text and get real-time prediction
- Detects if the article is **Real** or **Fake**
- Built-in text preprocessing (stopword removal, stemming, etc.)
- Lightweight Streamlit interface for quick access

---

## 📁 Dataset

We used a publicly available dataset:
- **Columns:** `title`, `text`, `label`
- **Labels:** `FAKE` or `REAL`

---

## 🛠️ Tools & Libraries Used

- Python
- scikit-learn
- nltk
- Streamlit
- TfidfVectorizer
- PassiveAggressiveClassifier
- pyngrok (optional for public access)

---

## 🔧 Installation

```bash
#  Clone the repo
git clone https://github.com/sreelekaa/news-fake-detection.git

  🧠 How It Works
Text Cleaning: Lowercasing, removing non-alphabetic characters

Tokenization & Stemming using NLTK

Vectorization using TfidfVectorizer

Classification using PassiveAggressiveClassifier

Output: Prediction whether the news is fake or real



📄 Project Structure

fake-news-detector/
│
├── app.py                   # Streamlit application code
├── fake_news_model.pkl      # Trained ML model
├── tfidf_vectorizer.pkl     # Trained TF-IDF vectorizer
├── requirements.txt         # Python dependencies
└── README.md                # This file

 Author
Sreeleka Manickam

