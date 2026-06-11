# Twitter Hate Speech Detection using NLP and Machine Learning

## Overview

This project detects racist and sexist tweets using Natural Language Processing (NLP) and Machine Learning techniques.

The workflow includes:

- Text preprocessing
- Stopword removal
- Lemmatization
- TF-IDF feature extraction
- Model training and evaluation

---

## Dataset

The dataset contains tweets labeled as:

| Label | Description |
|---------|-------------|
| 0 | No Racism/Sexism |
| 1 | Racism/Sexism |

**Total Tweets:** 31,962

---

## Preprocessing

The following text preprocessing techniques were applied:

- Lowercasing
- URL removal
- User mention removal
- Punctuation removal
- Stopword removal
- Lemmatization

---

## Feature Extraction

Text data was converted into numerical features using:

- **TF-IDF (Term Frequency - Inverse Document Frequency)**

---

## Models Tested

The following machine learning models were trained and evaluated:

1. Logistic Regression
2. Multinomial Naive Bayes
3. Linear Support Vector Machine (SVM)

---

## Final Results

| Metric | Value |
|----------|--------|
| Accuracy | **92.35%** |
| Precision (Class 1) | **47%** |
| Recall (Class 1) | **78%** |
| F1 Score (Class 1) | **59%** |

---

## Key Insight

The dataset was highly imbalanced, containing approximately:

- **93% Non-Hate Speech**
- **7% Hate Speech**

To improve the detection of harmful tweets, class balancing techniques were applied during model training. This significantly improved the model's ability to identify racist and sexist content while maintaining high overall accuracy.

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Google Colab

---

## Project Objective

The goal of this project is to build an automated hate speech detection system capable of identifying racist and sexist tweets, helping social media platforms moderate harmful content more effectively.
