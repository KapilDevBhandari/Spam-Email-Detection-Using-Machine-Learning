# 📧 Spam Email Detection Using Machine Learning

## 🧠 Project Overview

This project is a spam email classifier built using **Natural Language Processing (NLP)** and **Machine Learning** techniques. It identifies whether a given email (or SMS message) is **spam** or **ham (not spam)**.

## 🔍 Problem Statement

Spam emails pose a threat to user privacy and system security. Detecting spam effectively helps protect users from fraud, phishing attacks, and information overload.

## 🗃️ Dataset

- **Source**: UCI SMS Spam Collection
- **Size**: ~5,500 messages
- **Features**: 
  - `label` — spam or ham
  - `text` — message content

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- Scikit-learn
- NLTK
- TfidfVectorizer
- Naive Bayes Classifier
- Joblib

## 🔄 Workflow

1. **Data Cleaning & Preprocessing**
   - Lowercasing, Tokenization
   - Stopword and Punctuation removal

2. **Feature Extraction**
   - TF-IDF Vectorization

3. **Model Training**
   - Multinomial Naive Bayes Classifier
   - 80/20 Train-Test Split

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score

5. **Model Saving**
   - Reusable `.pkl` files for model and vectorizer

## 📊 Results

- **Accuracy**: ~97.6%
- **F1-Score** (Spam): 0.95

## 💾 Output Files

- `spam_classifier_model.pkl`
- `tfidf_vectorizer.pkl`

## 🚀 Future Improvements

- Web app / Streamlit frontend
- Deep learning (e.g., LSTM/BERT)
- Multi-language spam detection

---

## 🧑‍💻 Developed by

**Kapil Dev Bhandari**  
AI & ML Enthusiast | Computer Science @ Taylor's University 


---
