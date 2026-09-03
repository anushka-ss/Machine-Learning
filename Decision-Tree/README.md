# 🌳 DAY 17 — DECISION TREE

### Classification & Regression using Decision Tree Algorithms

---

## 📌 PROJECT OVERVIEW

This project focuses on understanding and implementing **Decision Tree algorithms** for both Classification and Regression problems.

The project demonstrates how Decision Trees can be used for:

- 🏷️ Classification
- 📈 Regression
- 🔄 Data Preprocessing
- 🔗 Machine Learning Pipelines
- 📊 Model Evaluation

Two practical datasets are used to understand the difference between Decision Tree Classification and Regression.

---

# 🎯 OBJECTIVES

The main objectives of this project are to:

- Understand the Decision Tree algorithm
- Implement `DecisionTreeClassifier`
- Implement a Decision Tree-based regression workflow
- Perform train-test splitting
- Handle categorical features
- Apply One-Hot Encoding
- Build preprocessing pipelines
- Train Machine Learning models
- Generate predictions
- Evaluate model performance

---

# 🌳 WHAT IS A DECISION TREE?

A Decision Tree is a supervised Machine Learning algorithm that makes predictions by learning a sequence of decision rules from the data.

It represents decisions in a tree-like structure:

```text
                    Root
                     │
              ┌──────┴──────┐
              │             │
            Rule          Rule
              │             │
         ┌────┴────┐   ┌────┴────┐
         │         │   │         │
       Leaf      Leaf Leaf      Leaf
```

The tree contains:

- 🌱 Root Node
- 🔀 Decision Nodes
- 🌿 Branches
- 🍃 Leaf Nodes

---

# 🏷️ DECISION TREE CLASSIFICATION

## 📧 Dataset

The classification notebook uses:

```text
spam_email_dataset.csv
```

The target variable is:

```text
label
```

The objective is to classify emails based on their available features.

---

## 🔄 Classification Workflow

```text
Spam Email Dataset
        ↓
Data Inspection
        ↓
Feature / Target Separation
        ↓
Train-Test Split
        ↓
Identify Categorical Features
        ↓
One-Hot Encoding
        ↓
ColumnTransformer
        ↓
Pipeline
        ↓
DecisionTreeClassifier
        ↓
Predictions
        ↓
Classification Report
```

---

## ⚙️ Decision Tree Classifier

The classifier is implemented using:

```python
DecisionTreeClassifier(
    random_state=42,
    criterion='entropy',
    max_depth=4
)
```

### Parameters practiced

- `criterion='entropy'`
- `max_depth=4`
- `random_state=42`

The `max_depth` parameter is used to control the maximum depth of the tree.

---

## 🔄 Preprocessing

Categorical features are identified and transformed using:

```python
OneHotEncoder(
    handle_unknown='ignore',
    sparse_output=False
)
```

The transformation is integrated with:

```python
ColumnTransformer()
```

and then combined with the Decision Tree model using:

```python
Pipeline()
```

---

## 📊 Classification Evaluation

The classification model is evaluated using:

```python
classification_report()
```

The report provides:

- Precision
- Recall
- F1 Score
- Support

Performance is checked on both:

- Training Data
- Testing Data

---

# 📈 DECISION TREE REGRESSION

## 🍷 Dataset

The regression notebook uses:

```text
winequality-red.csv
```

The target variable is:

```text
quality
```

The objective is to predict the wine quality value from the available features.

---

## 🔄 Regression Workflow

```text
Wine Quality Dataset
        ↓
Data Inspection
        ↓
Feature / Target Separation
        ↓
Train-Test Split
        ↓
Decision Tree / Regression Workflow
        ↓
Model Training
        ↓
Predictions
        ↓
Regression Evaluation
```

---

# 📊 REGRESSION EVALUATION

The project explores regression evaluation metrics including:

### R² Score

Measures how well the model explains the variation in the target variable.

```python
r2_score()
```

### Mean Absolute Error

Measures the average absolute difference between actual and predicted values.

```python
mean_absolute_error()
```

### Mean Squared Error

Measures the average squared difference between actual and predicted values.

```python
mean_squared_error()
```

### Root Mean Squared Error

Measures the square root of Mean Squared Error.

```python
root_mean_squared_error()
```

---

# 🧠 KEY CONCEPTS LEARNED

Through this project, I practiced:

- ✅ Decision Tree
- ✅ Decision Tree Classification
- ✅ Decision Tree Regression
- ✅ Train-Test Split
- ✅ Categorical Feature Detection
- ✅ One-Hot Encoding
- ✅ ColumnTransformer
- ✅ Pipeline
- ✅ Entropy
- ✅ Maximum Tree Depth
- ✅ Classification Report
- ✅ Precision
- ✅ Recall
- ✅ F1 Score
- ✅ R² Score
- ✅ MAE
- ✅ MSE
- ✅ RMSE
- ✅ Model Evaluation

---

# 🔀 CLASSIFICATION vs REGRESSION

| Feature | Classification | Regression |
|---|---|---|
| 🎯 Output | Class / Category | Continuous Value |
| 🤖 Model | Decision Tree Classifier | Regression Model |
| 📊 Example | Spam / Not Spam | Wine Quality |
| 📈 Evaluation | Precision, Recall, F1 | R², MAE, MSE, RMSE |
| 📌 Target | Categorical | Numerical |

---

# 🛠️ TECHNOLOGIES USED

- 🐍 Python
- 🐼 Pandas
- 📊 Seaborn
- 🤖 Scikit-learn
- 🎯 category_encoders
- 📓 Jupyter Notebook

---

# 📁 PROJECT STRUCTURE

```text
Decision-Tree
│
├── Decision_Tree_Classifier.ipynb
├── Decision_Tree_Regressor.ipynb
├── spam_email_dataset.csv
├── winequality-red.csv
└── README.md
```

---

# 🔗 END-TO-END MACHINE LEARNING WORKFLOW

```text
                DATASET
                   ↓
          DATA UNDERSTANDING
                   ↓
          FEATURE / TARGET SPLIT
                   ↓
             TRAIN-TEST SPLIT
                   ↓
           DATA PREPROCESSING
                   ↓
          ┌────────┴─────────┐
          ↓                  ↓
   CLASSIFICATION        REGRESSION
          ↓                  ↓
Decision Tree Model    Regression Model
          ↓                  ↓
    Predictions         Predictions
          ↓                  ↓
Classification         Regression
   Metrics              Metrics
          ↓                  ↓
     Performance Analysis
```

---

# 🎯 LEARNING OUTCOME

This project helped me understand how Decision Tree-based approaches can be applied to different types of supervised Machine Learning problems.

I learned how the workflow changes depending on whether the target variable represents a **category** or a **continuous numerical value**.

---

# 📌 PROJECT INFORMATION

| Category | Details |
|---|---|
| 📅 Day | 17 |
| 🎯 Topic | Decision Tree |
| 🏷️ Classification | Decision Tree Classifier |
| 📈 Regression | Regression Workflow |
| 📊 Classification Dataset | Spam Email Dataset |
| 🍷 Regression Dataset | Wine Quality Dataset |
| ⚙️ Preprocessing | One-Hot Encoding, ColumnTransformer, Pipeline |
| 📊 Classification Metrics | Precision, Recall, F1 Score |
| 📈 Regression Metrics | R², MAE, MSE, RMSE |
| ✅ Status | Completed |

---

# 🚀 MACHINE LEARNING JOURNEY

```text
Day 1  → Linear Regression
Day 2  → Polynomial Regression
Day 3  → Multiple Linear Regression
Day 4  → Feature Scaling — StandardScaler
Day 5  → Feature Scaling — MinMaxScaler
Day 6  → Label Encoding
Day 7  → One-Hot Encoding
Day 8  → Ordinal Encoding
Day 9  → Target Encoding
Day 10 → Column Transformer
Day 11 → Column Transformer — Multiple Transformers
Day 12 → Pipeline with ColumnTransformer & Logistic Regression
Day 13 → Missing Value Imputation — SimpleImputer
Day 14 → Logistic Regression — Loan Approval Prediction
Day 15 → Classification Metrics — Loan Data
Day 16 → Loan Default Risk — Classification Metrics
Day 17 → Decision Tree — Classification & Regression ⭐
```

---

# ⭐ PROJECT STATUS

### DAY 17 — COMPLETED

> **Learn → Implement → Evaluate → Analyze → Improve 🚀**