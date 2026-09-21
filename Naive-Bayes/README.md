# 📍 DAY 21 — NAIVE BAYES

### 🤖 Naive Bayes Classification — Multinomial Naive Bayes

---

## 📌 OVERVIEW

In Day 21, I explored the **Naive Bayes** family of Machine Learning algorithms.

This project focuses on **Multinomial Naive Bayes** for a text classification problem using a Spam dataset.

The implementation uses:

- TfidfVectorizer
- MultinomialNB
- Pipeline
- Train-Test Split
- Classification Report

---

# 🎯 OBJECTIVES

The main objectives of this project are:

- Understand the Naive Bayes algorithm
- Understand different Naive Bayes classifiers
- Understand Multinomial Naive Bayes
- Perform text classification
- Convert text into numerical features
- Build a Machine Learning Pipeline
- Train a Naive Bayes classifier
- Evaluate the classification model

---

# 🧠 WHAT IS NAIVE BAYES?

**Naive Bayes** is a supervised Machine Learning algorithm based on **Bayes' Theorem**.

It is commonly used for classification problems, especially text classification.

The algorithm is called "Naive" because it assumes that the features are conditionally independent given the class.

### Basic Workflow

```text
Input Data
    ↓
Calculate Probabilities
    ↓
Apply Bayes' Theorem
    ↓
Compare Class Probabilities
    ↓
Predict Class