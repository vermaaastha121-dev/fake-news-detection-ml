# 📰 Fake News Detection using Machine Learning

## 📌 Problem Statement
Fake news spreads misinformation rapidly across digital platforms. Manual verification is slow and difficult. This project builds an AI/ML model that automatically classifies news articles as REAL or FAKE using Natural Language Processing.

---

## 🎯 Objective
To develop a text classification model that can detect fake news based on article content.

---

## 🧠 Approach / Methodology

1. Data loading from Fake.csv and True.csv
2. Data labeling (Fake = 0, Real = 1)
3. Text preprocessing
   - Lowercasing
   - Removing punctuation
   - Removing stopwords
4. Feature extraction using TF-IDF Vectorizer
5. Model training using Logistic Regression
6. Model evaluation using accuracy and classification report

---

## 📂 Dataset
Kaggle Fake & True News Dataset  
Contains real and fake news articles used for supervised training.

---

## 🛠 Tech Stack

- Python
- Google Colab
- Pandas
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- Logistic Regression

---

## 📊 Model Performance

Accuracy: ~95% (may vary slightly depending on train/test split)

Metrics used:
- Accuracy score
- Precision
- Recall
- F1-score

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload dataset files (fake.csv, true.csv)
3. Run all cells step-by-step
4. Use the function:

```python
predict_news("your news text here")
