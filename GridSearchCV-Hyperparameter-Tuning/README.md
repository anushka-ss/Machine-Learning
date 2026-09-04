# 🎯 DAY 18 — GRIDSEARCHCV

## Hyperparameter Tuning in Machine Learning

This project focuses on **Hyperparameter Tuning using GridSearchCV** with a Decision Tree Classifier.

The objective is to systematically search through different combinations of hyperparameters and identify the combination that provides the best cross-validation performance.

---

## 📌 What is Hyperparameter Tuning?

Hyperparameters are settings that are defined before training a Machine Learning model.

Examples for a Decision Tree include:

- `criterion`
- `max_depth`
- `splitter`
- `min_samples_split`
- `min_samples_leaf`
- `max_features`

Instead of manually trying different values, **GridSearchCV** evaluates multiple combinations automatically.

---

## 🔍 What is GridSearchCV?

`GridSearchCV` performs an exhaustive search over a predefined set of hyperparameter values.

It combines:

- Grid Search
- Cross-Validation
- Model Evaluation

### Workflow

```text
Hyperparameter Grid
        ↓
Generate Parameter Combinations
        ↓
Cross-Validation
        ↓
Train & Evaluate Models
        ↓
Compare Results
        ↓
Select Best Parameters
        ↓
Best Estimator