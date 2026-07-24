# Product Review Sentiment Analysis

## Project Overview

This project performs multiclass sentiment analysis on product reviews using Natural Language Processing (NLP) and Machine Learning. The objective is to classify reviews into Positive, Neutral, and Negative sentiments. Multiple machine learning models were trained and compared to identify the best-performing classifier.

---

## Dataset

- Product Reviews Dataset
- Source: Kaggle

---

## Workflow

1. Data Loading
2. Data Cleaning
3. Text Preprocessing
4. Tokenization
5. Stopword Removal
6. Lemmatization
7. Feature Extraction using CountVectorizer and TF-IDF
8. Model Training
9. Model Evaluation
10. Confusion Matrix
11. Model Comparison

---

## Models Used

- Naive Bayes
- Logistic Regression
- Linear Support Vector Machine (SVM)

---

## Model Performance

| Model | Vectorizer | Accuracy |
|--------|------------|----------|
| Naive Bayes | CountVectorizer | 91.75% |
| Logistic Regression | TF-IDF | 92.47% |
| Linear SVM | TF-IDF | **92.78%** |

**Best Performing Model:** Linear SVM with TF-IDF (92.78%)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Jupyter Notebook

---

## Project Structure

```
Product-Review-Sentiment-Analysis
│
├── Product Review Sentiment Analysis.ipynb
├── Product_Reviews.csv
├── README.md
├── requirements.txt
└── .gitignore
```