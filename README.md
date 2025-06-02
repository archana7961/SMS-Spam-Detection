# 📱 SMS Spam Detection 🔍

A machine learning project that detects whether an SMS message is spam or not. The goal is to automatically classify incoming text messages to help users avoid unwanted spam.

## 🚀 Project Overview

This project uses natural language processing (NLP) and machine learning to classify SMS messages as **"Spam"** or **"Ham"** (legitimate).

### 🎯 Key Objectives

- Build a binary classifier for SMS messages.
- Clean and preprocess textual data.
- Apply machine learning models for classification.
- Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.

---

## 📂 Dataset

The project uses the **SMS Spam Collection Dataset** from the UCI repository:

- 📁 Format: `.csv`
- 📊 Size: ~5,500 messages
- 🏷️ Labels: `ham`, `spam`

Download link: [SMS Spam Dataset - UCI](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Libraries:**
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `nltk` or `spaCy`
  - `matplotlib` / `seaborn` (for visualizations)
  - `joblib` or `pickle` (for model saving)

---

## 🔄 Workflow

```plaintext
1. Data Loading
2. Text Preprocessing:
    - Lowercasing
    - Stopword removal
    - Punctuation removal
    - Lemmatization
3. Feature Extraction:
    - TF-IDF / CountVectorizer
4. Model Training:
    - Naive Bayes / Logistic Regression / SVM
5. Evaluation:
    - Confusion Matrix
    - Accuracy, Precision, Recall, F1
6. Deployment (Optional):
    - Streamlit / Flask Web App
