# 📰 Fake News Detection Using Machine Learning

## 📌 Project Overview

This project focuses on detecting Fake News using Machine Learning and Natural Language Processing (NLP).

The system classifies news articles into:

- **0 → Fake News**
- **1 → Real News**

The project follows a complete end-to-end Machine Learning pipeline including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Text Preprocessing
- TF-IDF Feature Extraction
- Model Training & Evaluation
- Cross-Validation
- Model Comparison
- Model Saving using Pickle

After comparing multiple models, **Logistic Regression** was selected as the final model due to its high accuracy and stable performance.

---

## 🎯 Problem Statement

Fake news spreads misinformation and can negatively impact society.  
The objective of this project is to automatically classify news articles as Fake or Real using supervised machine learning techniques.

---

## 🧠 Machine Learning Models Used

The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report
- 5-Fold Cross-Validation

---

## 📊 Feature Engineering

Text data was converted into numerical format using:

### TF-IDF Vectorization (max_features = 5000)

Text preprocessing steps included:

- Converting text to lowercase
- Removing special characters
- Removing stopwords
- Lemmatization

---

## 🏆 Final Model Selection

Based on accuracy and cross-validation results:

✅ Logistic Regression performed best.

Reason:
- Performs well on high-dimensional sparse TF-IDF features
- Provides stable and consistent results
- Generalizes well on unseen test data

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Pickle

---

## 📂 Project Structure

    fake-news-detection/
    │
    ├── Fake_News_Detection.ipynb
    ├── vectorizer.pkl
    ├── fake_news_model.pkl
    ├── requirements.txt
    └── README.md

---

## 🚀 Instructions to Run the Project

### 1️⃣ Clone the Repository

    git clone https://github.com/nehachandele/Fake_News_Detection_Wisdom.git
    cd fake-news-detection

---

### 2️⃣ Install Dependencies

    pip install -r requirements.txt

If `requirements.txt` is not available, install manually:

    pip install pandas numpy scikit-learn nltk matplotlib seaborn

---

### 3️⃣ Run the Notebook

Open Jupyter Notebook:

    jupyter notebook

Then open:

    Fake_News_Detection.ipynb

Run all cells step by step.

---
