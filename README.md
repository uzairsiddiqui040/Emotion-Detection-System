# Emotion Detection System

NLP-based text classification system that detects emotions from text input using TF-IDF vectorization and machine learning.

---

## What it does

- Classifies text into emotional categories (happy, sad, angry, neutral)
- Converts text into numerical features using TF-IDF
- Compares two classification models
- Identifies the better performing model

---

## Models Compared

- K-Nearest Neighbors (KNN)
- Logistic Regression

---

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (TfidfVectorizer, KNN, Logistic Regression)
- NLTK (text preprocessing)

---

## Workflow

- Loaded and explored text dataset
- Preprocessed text (lowercasing, stopword removal, tokenization)
- Applied TF-IDF vectorization
- Split data into train and test sets
- Trained KNN and Logistic Regression models
- Compared accuracy scores
- Determined best model

---

## Key Results

- Logistic Regression – 86%
- KNN – 66%

Best model: Logistic Regression (handles sparse TF-IDF data better)

---
