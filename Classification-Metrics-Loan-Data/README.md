# 📅 Day 15 — Classification Metrics with Loan Data

> Understanding and evaluating Machine Learning classification models

---

## 📌 Project Overview

This project focuses on understanding **Classification Metrics** used to evaluate Machine Learning classification models.

Using a loan dataset, I practiced evaluating classification predictions and understanding how different metrics measure model performance.

The main focus of this project is to understand:

- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1 Score

---

## 🎯 Objective

The objective of this project is to understand how to evaluate a classification model beyond simply checking its accuracy.

Different classification metrics provide different information about model performance.

---

# 📊 Classification Metrics

## 1️⃣ Confusion Matrix

A Confusion Matrix summarizes the predictions made by a classification model.

It contains:

| | Predicted Positive | Predicted Negative |
|---|---|---|
| **Actual Positive** | True Positive (TP) | False Negative (FN) |
| **Actual Negative** | False Positive (FP) | True Negative (TN) |

The four basic components are:

- **TP — True Positive**
- **TN — True Negative**
- **FP — False Positive**
- **FN — False Negative**

---

## 2️⃣ Accuracy

Accuracy measures the proportion of total predictions that were correct.

### Formula

```text
Accuracy =
(TP + TN) / (TP + TN + FP + FN)