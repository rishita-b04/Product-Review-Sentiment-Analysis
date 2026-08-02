# 🛍️ Product Review Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project performs sentiment analysis on Amazon product reviews using Natural Language Processing (NLP) and Machine Learning techniques. The review text is cleaned, transformed into numerical features using vectorization techniques, and classified into **Positive, Neutral, or Negative** sentiments.

The project compares multiple machine learning models and selects the best-performing model based on classification accuracy.

---

## 📂 Dataset

- **Source:** Amazon Product Reviews Dataset
- **Total Records:** 4,915
- **Features Used:**
  - Review Text
  - Overall Rating
  - Review Summary
  - Review Time
  - Day Difference

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Joblib
- Jupyter Notebook

---

## 🧹 Data Preprocessing

- Removed missing values
- Converted text to lowercase
- Removed URLs
- Removed numbers
- Removed punctuation
- Tokenization
- Stopword removal
- Lemmatization

---

## 📊 Exploratory Data Analysis

- Dataset overview
- Missing value analysis
- Duplicate value check
- Rating distribution
- Sentiment distribution
- Review length distribution

---

## 🔤 Feature Engineering

Two text vectorization techniques were used:

- CountVectorizer
- TF-IDF Vectorizer

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

| Model | Vectorizer | Accuracy |
|--------|------------|----------|
| Naive Bayes | CountVectorizer | **91.75%** |
| Logistic Regression | TF-IDF | **92.47%** |
| Linear SVM | TF-IDF | **92.78%** ✅ |

Linear SVM achieved the highest accuracy and was selected as the final model.

---

## 📈 Model Evaluation

Evaluation metrics used:

- Accuracy
- Classification Report
- Confusion Matrix
- Model Comparison

---

## 📁 Project Structure

```
Product-Review-Sentiment-Analysis/
│
├── Product Review Sentiment Analysis.ipynb
├── amazon_review_selected_columns.csv
├── sentiment_model.pkl
├── tfidf.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/rishita-b04/Product-Review-Sentiment-Analysis.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells to reproduce the results.

---

## 📌 Results

- Successfully classified Amazon product reviews into Positive, Neutral, and Negative sentiments.
- Compared multiple machine learning algorithms.
- Linear SVM achieved the best performance with **92.78% accuracy**.
- Saved the trained model and TF-IDF vectorizer for future deployment.

---

## ⚠️ Limitation

The dataset is highly imbalanced, with Positive reviews significantly outnumbering Neutral and Negative reviews. As a result, the model performs better on the Positive class than the Neutral class.

---

## 🚀 Future Improvements

- Develop a Streamlit web application for real-time sentiment prediction.
- Improve minority class prediction using advanced balancing techniques.
- Experiment with transformer-based NLP models such as BERT.

---

## 👩‍💻 Author

**Rishita Bagri**

GitHub: https://github.com/rishita-b04
