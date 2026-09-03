# 🤖 MACHINE LEARNING

### 🚀 A Hands-On Journey from Fundamentals to Practical Machine Learning

Welcome to my **Machine Learning journey**!

This repository documents my hands-on learning experience with **Machine Learning algorithms, data preprocessing techniques, feature engineering, model evaluation, and practical ML workflows**.

Each project focuses on understanding concepts practically by implementing them using **Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn**.

---

# 📌 ABOUT THIS REPOSITORY

This repository is a collection of my **Machine Learning practice projects and implementations**.

My approach is to learn Machine Learning step-by-step:

> **Understand the Concept → Preprocess the Data → Build the Model → Evaluate the Model → Analyze the Results**

The repository is continuously updated as I learn and implement new concepts.

---

# 🛠️ TECHNOLOGY STACK

| Technology          | Purpose                       |
| ------------------- | ----------------------------- |
| 🐍 Python           | Programming Language          |
| 🔢 NumPy            | Numerical Computing           |
| 🐼 Pandas           | Data Manipulation & Analysis  |
| 📊 Matplotlib       | Data Visualization            |
| 📈 Seaborn          | Statistical Visualization     |
| 🤖 Scikit-learn     | Machine Learning              |
| 📓 Jupyter Notebook | Development & Experimentation |
| 🔧 Git & GitHub     | Version Control & Portfolio   |

---

# 📂 REPOSITORY STRUCTURE

```text
Machine-Learning
│
├── Linear-Regression
│
├── Polynomial-Regression
│
├── Multiple-Linear-Regression
│
├── StandardScaler
│
├── MinMaxScaler
│
├── Label-Encoding
│
├── One-Hot-Encoding
│
├── Ordinal-Encoding
│
├── Target-Encoding
│
├── Column-Transformer
│
├── Column-Transformer-Multiple-Transformers
│
├── Pipeline-ColumnTransformer-LogisticRegression
│
├── Missing-Value-Imputation
│
├── Logistic-Regression-Loan-Approval
│
├── Classification-Metrics-Loan-Data
│
├── Loan-Default-Risk-Classification-Metrics
│   ├── Loan_Default_Risk.ipynb
│   ├── loan_default_risk_dataset.csv
│   └── README.md
│
├── Decision-Tree
│   ├── Decision_Tree_Classifier.ipynb
│   ├── Decision_Tree_Regressor.ipynb
│   ├── spam_email_dataset.csv
│   ├── winequality-red.csv
│   └── README.md
│
└── README.md
```

---

# 📚 MACHINE LEARNING PROJECTS

## 📈 01 — LINEAR REGRESSION

Implemented the fundamentals of **Linear Regression** to understand the relationship between independent and dependent variables.

### Concepts Covered

* Simple Linear Regression
* Independent and Dependent Variables
* Train-Test Split
* Model Training
* Predictions
* Model Evaluation
* R² Score

---

## 📊 02 — POLYNOMIAL REGRESSION

Explored **Polynomial Regression** to understand how Machine Learning models can capture non-linear relationships.

### Concepts Covered

* Polynomial Features
* Different Polynomial Degrees
* Model Training
* Predictions
* Train vs Test Performance
* Underfitting
* Overfitting
* R² Score

---

## 📈 03 — MULTIPLE LINEAR REGRESSION

Implemented **Multiple Linear Regression** using multiple independent variables to predict a target variable.

### Concepts Covered

* Multiple Features
* Train-Test Split
* Model Training
* Prediction
* Model Evaluation
* R² Score

---

# ⚙️ DATA PREPROCESSING

Machine Learning models require properly prepared data.

The following preprocessing techniques have been implemented:

---

## 🔹 04 — STANDARD SCALER

Implemented feature scaling using **Standardization** with `StandardScaler`.

### Concepts Covered

* Feature Scaling
* Standardization
* Mean
* Standard Deviation
* Transformation of Numerical Features

---

## 🔹 05 — MINMAX SCALER

Implemented feature scaling using **Min-Max Normalization** with `MinMaxScaler`.

### Concepts Covered

* Feature Scaling
* Normalization
* Minimum and Maximum Values
* Transformation of Numerical Features

---

## 🔹 06 — LABEL ENCODING

Implemented **Label Encoding** to convert categorical labels into numerical values.

### Concepts Covered

* Categorical Data
* Numerical Representation
* `LabelEncoder`
* Encoding Categories

---

## 🔹 07 — ONE-HOT ENCODING

Implemented **One-Hot Encoding** to convert categorical variables into binary indicator columns.

### Concepts Covered

* Categorical Features
* Dummy Variables
* `OneHotEncoder`
* Handling Multiple Categories

---

## 🔹 08 — ORDINAL ENCODING

Implemented **Ordinal Encoding** for categorical variables where the categories have a meaningful order.

### Concepts Covered

* Ordered Categories
* `OrdinalEncoder`
* Mapping Categories to Numerical Values

---

## 🔹 09 — TARGET ENCODING

Explored **Target Encoding**, where categorical variables are represented using information derived from the target variable.

### Concepts Covered

* Categorical Variables
* Target-Based Encoding
* Numerical Representation of Categories

---

# 🔧 COLUMN TRANSFORMER & PIPELINES

## 🔹 10 — COLUMN TRANSFORMER

Learned how to apply different preprocessing techniques to different columns within a dataset using `ColumnTransformer`.

### Concepts Covered

* ColumnTransformer
* Numerical Feature Transformation
* Categorical Feature Transformation
* Multiple Preprocessing Steps

---

## 🔹 11 — COLUMN TRANSFORMER — MULTIPLE TRANSFORMERS

Implemented multiple preprocessing transformations together for handling different types of features.

### Concepts Covered

* Multiple Transformers
* Numerical Preprocessing
* Categorical Preprocessing
* ColumnTransformer
* Efficient Data Preparation

---

## 🔹 12 — PIPELINE WITH COLUMNTRANSFORMER & LOGISTIC REGRESSION

Combined preprocessing and Machine Learning into a single workflow using:

* `Pipeline`
* `ColumnTransformer`
* `LogisticRegression`

This project helped understand how to build a **clean and organized Machine Learning workflow**.

---

# 🧹 MISSING VALUE HANDLING

## 🔹 13 — MISSING VALUE IMPUTATION

Implemented missing-value handling using:

### `SimpleImputer`

Learned how missing values can be replaced using appropriate statistical strategies before training a Machine Learning model.

### Concepts Covered

* Missing Data
* Data Cleaning
* SimpleImputer
* Mean Imputation
* Median Imputation
* Handling Missing Values Before Model Training

---

# 🏦 CLASSIFICATION PROJECTS

## 🔹 14 — LOGISTIC REGRESSION — LOAN APPROVAL PREDICTION

Implemented **Logistic Regression** for predicting loan approval.

### Concepts Covered

* Binary Classification
* Logistic Regression
* Feature Preprocessing
* Train-Test Split
* Model Training
* Predictions
* Classification Evaluation

---

# 📊 CLASSIFICATION METRICS

## 🔹 15 — CLASSIFICATION METRICS — LOAN DATA

Explored important classification evaluation metrics to understand how well a classification model performs.

### Metrics Covered

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

Understanding different metrics is important because **accuracy alone may not always provide a complete picture of model performance**.

---

# 🏦 LOAN DEFAULT RISK

## 🔹 16 — LOAN DEFAULT RISK — CLASSIFICATION METRICS

Applied classification evaluation techniques to a **Loan Default Risk** dataset.

### Focus Areas

* Classification Model Evaluation
* Confusion Matrix
* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

This project helped strengthen my understanding of evaluating classification models in a practical Machine Learning problem.

---

# 🌳 DECISION TREE

## 🔹 17 — DECISION TREE — CLASSIFICATION & REGRESSION

Implemented **Decision Tree Machine Learning workflows** for classification and regression problems.

---

## 📧 DECISION TREE CLASSIFICATION — SPAM EMAIL DETECTION

Built a Decision Tree classification workflow using a **Spam Email dataset**.

### Concepts Covered

* `DecisionTreeClassifier`
* Entropy
* Maximum Tree Depth
* One-Hot Encoding
* `ColumnTransformer`
* `Pipeline`
* Classification Report
* Model Evaluation

### Model Configuration

```python
DecisionTreeClassifier(
    random_state=42,
    criterion='entropy',
    max_depth=4
)
```

The preprocessing workflow includes:

```text
Categorical Features
        ↓
One-Hot Encoding
        ↓
ColumnTransformer
        ↓
Pipeline
        ↓
DecisionTreeClassifier
        ↓
Classification Report
```

---

## 🍷 DECISION TREE REGRESSION — WINE QUALITY

Explored a regression workflow using the **Wine Quality dataset**.

### Regression Evaluation Metrics

* R² Score
* MAE
* MSE
* RMSE

### Classification vs Regression

| Classification              | Regression                |
| --------------------------- | ------------------------- |
| Predicts categories/classes | Predicts numerical values |
| Example: Spam / Not Spam    | Example: Wine Quality     |
| Uses classification metrics | Uses regression metrics   |
| Classification model        | Regression model          |

---

# 🗺️ MY MACHINE LEARNING JOURNEY

| Day | Topic                                                 | Status          |
| --- | ----------------------------------------------------- | --------------- |
| 01  | 📈 Linear Regression                                  | ✅ Completed     |
| 02  | 📊 Polynomial Regression                              | ✅ Completed     |
| 03  | 📈 Multiple Linear Regression                         | ✅ Completed     |
| 04  | ⚙️ StandardScaler                                     | ✅ Completed     |
| 05  | ⚙️ MinMaxScaler                                       | ✅ Completed     |
| 06  | 🔤 Label Encoding                                     | ✅ Completed     |
| 07  | 🔢 One-Hot Encoding                                   | ✅ Completed     |
| 08  | 🔢 Ordinal Encoding                                   | ✅ Completed     |
| 09  | 🎯 Target Encoding                                    | ✅ Completed     |
| 10  | 🔧 Column Transformer                                 | ✅ Completed     |
| 11  | 🔧 Column Transformer — Multiple Transformers         | ✅ Completed     |
| 12  | 🔄 Pipeline + ColumnTransformer + Logistic Regression | ✅ Completed     |
| 13  | 🧹 Missing Value Imputation — SimpleImputer           | ✅ Completed     |
| 14  | 🏦 Logistic Regression — Loan Approval Prediction     | ✅ Completed     |
| 15  | 📊 Classification Metrics — Loan Data                 | ✅ Completed     |
| 16  | 🏦 Loan Default Risk — Classification Metrics         | ✅ Completed     |
| 17  | 🌳 Decision Tree — Classification & Regression        | ⭐ **Completed** |

---

# 🧠 KEY LEARNING AREAS

Through these projects, I have gained hands-on experience with:

## 📌 Regression

* Linear Regression
* Polynomial Regression
* Multiple Linear Regression
* Regression Model Evaluation

## 📌 Classification

* Logistic Regression
* Decision Tree Classification
* Binary Classification
* Classification Model Evaluation

## 📌 Data Preprocessing

* Standardization
* Normalization
* Label Encoding
* One-Hot Encoding
* Ordinal Encoding
* Target Encoding
* Missing Value Imputation

## 📌 Feature Transformation

* ColumnTransformer
* Multiple Transformers
* Pipelines

## 📌 Model Evaluation

### Regression Metrics

* R² Score
* MAE
* MSE
* RMSE

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

# 🔄 MACHINE LEARNING WORKFLOW

My projects follow a structured Machine Learning workflow:

```text
             📂 Dataset
                 ↓
        🔍 Understand Data
                 ↓
          🧹 Data Cleaning
                 ↓
       ⚙️ Data Preprocessing
                 ↓
        🔄 Feature Engineering
                 ↓
          ✂️ Train-Test Split
                 ↓
          🤖 Model Selection
                 ↓
           🏋️ Model Training
                 ↓
           🔮 Predictions
                 ↓
          📊 Model Evaluation
                 ↓
          🔍 Result Analysis
```

---

# 📈 LEARNING PROGRESS

```text
Machine Learning Fundamentals
            ↓
       Regression
            ↓
  Data Preprocessing
            ↓
   Feature Encoding
            ↓
 Feature Transformation
            ↓
        Pipelines
            ↓
      Classification
            ↓
 Classification Metrics
            ↓
      Decision Trees
            ↓
     🚀 Continuing...
```

---

# 🎯 CURRENT PROGRESS

## ⭐ DAY 17 COMPLETED

I have progressed from basic regression algorithms to:

* Regression Algorithms
* Data Preprocessing
* Feature Scaling
* Categorical Encoding
* Feature Transformation
* ColumnTransformer
* Pipelines
* Logistic Regression
* Classification
* Classification Metrics
* Practical Prediction Problems
* Decision Tree Classification
* Decision Tree Regression Workflows

The goal is to continue building a strong foundation through **hands-on implementation rather than only theoretical learning**.

---

# 🚀 REPOSITORY GOALS

The main goals of this repository are:

* Build a strong Machine Learning foundation
* Implement concepts using Python
* Practice data preprocessing
* Understand feature engineering
* Understand model evaluation
* Work with practical datasets
* Develop Machine Learning problem-solving skills
* Maintain a consistent learning record
* Build a professional Machine Learning portfolio

---

# 📌 WHY THIS REPOSITORY?

This repository represents my **continuous Machine Learning learning journey**.

Instead of learning algorithms only theoretically, I am implementing each concept through practical notebooks and datasets.

My learning philosophy:

> **Learn → Implement → Evaluate → Improve → Repeat**

---

# 🔮 NEXT STEPS

I will continue expanding this repository with new:

* Machine Learning Algorithms
* Data Preprocessing Techniques
* Feature Engineering Methods
* Model Evaluation Techniques
* Classification Algorithms
* Regression Algorithms
* Practical Machine Learning Projects

The goal is to gradually move from **Machine Learning fundamentals to more advanced and real-world applications**.

---

# 👩‍💻 ABOUT ME

I am a **Computer Science & Engineering graduate** building my skills in:

* Python
* Machine Learning
* Data Science
* Artificial Intelligence

I am developing my technical skills through **continuous hands-on learning, practical implementation, and project-based learning**.

This repository represents my ongoing journey toward becoming a strong **Machine Learning / Python professional**.

---

# ⭐ SUPPORT

If you find this repository useful or interesting, feel free to ⭐ **Star** the repository!

---

# 🚀 LEARNING. BUILDING. IMPROVING.

### **Day 17 — Decision Tree completed.**

### **The journey continues... 🤖**

