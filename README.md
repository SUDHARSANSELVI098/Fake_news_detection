 # 📰 Fake News Detection using Machine Learning

Fake News Detection is a machine learning project that classifies news articles as **Fake** or **Real** using Natural Language Processing (NLP) techniques. The goal is to reduce the spread of misinformation by automatically identifying unreliable news content.

---

## 📌 Problem Statement

With the rapid growth of digital media, fake news spreads quickly and influences public opinion. Manual fact-checking is slow and inefficient. This project builds an automated system to detect fake news using machine learning models trained on textual data.

---

## 📂 Dataset

- Labeled news articles dataset
- Columns:
  - `title`
  - `text`
  - `label` (0 = Fake, 1 = Real)
- Source: Kaggle / Open-source news datasets

---

## 🛠️ Project Workflow

1. Data Collection  
2. Exploratory Data Analysis (EDA)  
3. Text Preprocessing  
4. Feature Extraction using TF-IDF  
5. Model Training  
6. Model Evaluation  
7. Prediction  
8. Model Serialization  

---

## 🔍 Text Preprocessing Steps

- Convert text to lowercase  
- Remove punctuation and special characters  
- Remove stopwords  
- Tokenization  
- Lemmatization  

---

## 🤖 Machine Learning Models Used

- Logistic Regression (Primary)
- Multinomial Naive Bayes
- Random Forest (Optional)

TF-IDF Vectorization is used to convert text data into numerical features.

---

## 📈 Model Performance

The trained model achieves:

- Accuracy: ~90%
- Precision: High for both Fake and Real classes
- Recall and F1-score optimized using cross-validation

---

## 🧪 Example Prediction

Input News:
"Breaking news claims miracle cure discovered overnight..."

Prediction:
Fake News
