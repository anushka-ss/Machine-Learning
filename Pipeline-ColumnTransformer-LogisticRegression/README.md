# 🔗 Day 12 — Machine Learning Pipeline with ColumnTransformer & Logistic Regression

> **Building an end-to-end preprocessing and classification pipeline using Scikit-learn**

---

## 📌 Project Overview

This project demonstrates how to build a complete **Machine Learning Pipeline** using **Scikit-learn**.

The main objective is to combine:

- Multiple preprocessing techniques
- `ColumnTransformer`
- `Pipeline`
- `LogisticRegression`
- Model evaluation

into a single structured Machine Learning workflow.

Instead of preprocessing each feature separately, this project demonstrates how different transformations can be automatically applied to the appropriate columns and then passed directly to a Machine Learning model.

---

## 🎯 Objective

The objective of this project is to understand how a Machine Learning pipeline can:

1. Prepare the dataset
2. Separate features and target
3. Split data into training and testing sets
4. Apply different preprocessing techniques to different columns
5. Combine all transformations using `ColumnTransformer`
6. Pass the transformed data to a Machine Learning model
7. Train the complete workflow using `Pipeline`
8. Evaluate the model's classification performance

---

## 📊 Dataset

A small employee dataset is created using Pandas.

### Features

| Feature | Description | Type |
|---|---|---|
| `salary` | Employee salary | Numerical |
| `city` | Employee's city | Categorical |
| `education` | Education level | Ordinal Categorical |
| `age` | Employee age | Numerical |
| `purchased` | Target variable | Binary |

### Target Variable

```text
purchased
```

The target represents a binary classification problem with values:

```text
0 → No
1 → Yes
```

---

## 🔄 Machine Learning Workflow

```text
                 Dataset
                    │
                    ▼
            Separate X and y
                    │
                    ▼
             Train-Test Split
                    │
                    ▼
          ┌─────────────────────┐
          │   ColumnTransformer │
          └─────────────────────┘
                    │
       ┌────────────┼────────────┐
       ▼            ▼            ▼
     Salary        City       Education
       │            │            │
       ▼            ▼            ▼
 MinMaxScaler  TargetEncoder  OrdinalEncoder
       │            │            │
       └────────────┼────────────┘
                    │
                    ▼
             Remaining Columns
                Passthrough
                    │
                    ▼
              Preprocessed Data
                    │
                    ▼
          ┌─────────────────────┐
          │       Pipeline      │
          │                     │
          │  Preprocessor       │
          │        ↓            │
          │  LogisticRegression │
          └─────────────────────┘
                    │
                    ▼
              Model Prediction
                    │
                    ▼
             Model Evaluation
```

---

# 🧹 Data Preprocessing

Different preprocessing techniques are applied to different features.

### 1. Numerical Feature — `salary`

`MinMaxScaler` is applied to the salary column.

```python
MinMaxScaler()
```

This scales the salary values before they are passed to the model.

---

### 2. Categorical Feature — `city`

`TargetEncoder` is applied to the city column.

```python
TargetEncoder()
```

This encodes the categorical feature using information from the target variable.

---

### 3. Ordinal Feature — `education`

`OrdinalEncoder` is used with an explicitly defined order:

```text
12th < Graduate < Postgraduate
```

The notebook specifies this category ordering directly.

```python
OrdinalEncoder(
    categories=[
        ['12th', 'Graduate', 'Postgraduate']
    ]
)
```

---

### 4. Remaining Features

The remaining columns are kept using:

```python
remainder='passthrough'
```

This allows columns that are not explicitly transformed to pass through the `ColumnTransformer`.

---

# 🔄 ColumnTransformer

The preprocessing steps are combined using Scikit-learn's `ColumnTransformer`.

```python
preprocessor = ColumnTransformer(
    transformers=[
        ('scaling', MinMaxScaler(), ['salary']),
        ('encoder', TargetEncoder(), ['city']),
        ('encoder_1',
         OrdinalEncoder(
             categories=[
                 ['12th', 'Graduate', 'Postgraduate']
             ]
         ),
         ['education'])
    ],
    remainder='passthrough'
)
```

This allows different preprocessing techniques to be applied to different columns within the same preprocessing object. :contentReference[oaicite:2]{index=2}

---

# 🔗 Machine Learning Pipeline

The preprocessing stage and Machine Learning model are combined using Scikit-learn's `Pipeline`.

```python
pipeline = Pipeline(
    steps=[
        ('preprocessor', preprocessor),
        ('model', LogisticRegression())
    ]
)
```

The workflow becomes:

```text
Raw Data
   ↓
ColumnTransformer
   ↓
Feature Transformation
   ↓
Logistic Regression
   ↓
Prediction
```

This creates a structured workflow where preprocessing and model training are handled together. :contentReference[oaicite:3]{index=3}

---

# 🤖 Machine Learning Model

## Logistic Regression

The final Machine Learning algorithm used in this project is:

```python
LogisticRegression()
```

Logistic Regression is a classification algorithm used to predict categorical outcomes.

In this project, it is used to predict the binary target:

```text
purchased → 0 / 1
```

---

# 📈 Model Evaluation

The notebook imports and uses the following evaluation techniques:

### Accuracy Score

```python
accuracy_score()
```

Measures the proportion of correct predictions.

### Confusion Matrix

```python
confusion_matrix()
```

Provides a breakdown of correct and incorrect classification predictions.

### Classification Report

```python
classification_report()
```

Provides classification metrics such as:

- Precision
- Recall
- F1-score
- Support

---

# 🧠 Concepts Learned

Through this project, I practiced:

- ✅ Train-Test Split
- ✅ Numerical Feature Scaling
- ✅ Categorical Feature Encoding
- ✅ Ordinal Encoding
- ✅ Target Encoding
- ✅ `ColumnTransformer`
- ✅ `Pipeline`
- ✅ Logistic Regression
- ✅ Model Training
- ✅ Model Prediction
- ✅ Accuracy Score
- ✅ Confusion Matrix
- ✅ Classification Report

---

# 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming language |
| 🐼 Pandas | DataFrame creation and data manipulation |
| 🤖 Scikit-learn | Preprocessing, pipeline, model, and evaluation |
| 📓 Jupyter Notebook | Development and experimentation |
| 🎯 Target Encoding | Categorical feature transformation |

---

# 📁 Project Structure

```text
Pipeline-ColumnTransformer-LogisticRegression
│
├── Pipeline-ColumnTransformer-LogisticRegression.ipynb
│
└── README.md
```

---

# 💡 Key Takeaways

### Before this project

Different preprocessing techniques could be applied manually to individual columns.

### After this project

I learned how to organize the complete preprocessing workflow using:

```text
ColumnTransformer
       ↓
    Pipeline
       ↓
Logistic Regression
       ↓
   Evaluation
```

This makes the Machine Learning workflow more structured and easier to manage.

---

# 🚀 Learning Progress

| Day | Topic | Status |
|---|---|---|
| ✅ Day 1 | Linear Regression | Completed |
| ✅ Day 2 | Polynomial Regression | Completed |
| ✅ Day 3 | Multiple Linear Regression | Completed |
| ✅ Day 4 | Feature Scaling — StandardScaler | Completed |
| ✅ Day 5 | Feature Scaling — MinMaxScaler | Completed |
| ✅ Day 6 | Label Encoding | Completed |
| ✅ Day 7 | One-Hot Encoding | Completed |
| ✅ Day 8 | Ordinal Encoding | Completed |
| ✅ Day 9 | Target Encoding | Completed |
| ✅ Day 10 | Column Transformer | Completed |
| ✅ Day 11 | Column Transformer — Multiple Transformers | Completed |
| ⭐ Day 12 | Pipeline with ColumnTransformer & Logistic Regression | **Completed** |

---

# 🎯 Learning Outcome

By completing this project, I gained practical experience in building a structured Machine Learning workflow that combines:

```text
Data
 ↓
Train-Test Split
 ↓
ColumnTransformer
 ↓
Multiple Preprocessing Techniques
 ↓
Pipeline
 ↓
Logistic Regression
 ↓
Predictions
 ↓
Model Evaluation
```

This project helped me understand how preprocessing and model training can be integrated into a single Machine Learning pipeline.

---

# 📌 Project Status

**Status:** ✅ Completed

**Day:** 12

**Category:** Machine Learning / Data Preprocessing / Classification

**Model:** Logistic Regression

**Primary Concepts:** `ColumnTransformer` + `Pipeline`

---

## ⭐ Thank You

Thank you for visiting this project!

This repository is part of my ongoing **Machine Learning learning journey**, where I am building concepts step-by-step through hands-on implementation.

⭐ Feel free to explore the repository and follow my progress.

**More Machine Learning projects coming soon! 🚀**
