# 📅 Day 16 — Loan Default Risk Classification Metrics

> **Applying Classification Metrics to a Loan Default Risk Prediction Problem**

---

## 📌 Project Overview

This project focuses on evaluating a Logistic Regression classification model for predicting **Loan Default Risk**.

This project is a continuation of Day 15, where I learned and practiced different classification evaluation metrics.

In Day 16, I applied these concepts to a Loan Default Risk dataset.

---

## 🎯 Objective

The main objective of this project is to:

- Prepare the loan default risk dataset
- Handle missing values
- Identify and preprocess numerical features
- Apply feature scaling
- Build a Machine Learning pipeline
- Train a Logistic Regression model
- Generate predictions
- Evaluate the model using classification metrics

---

# 📊 Dataset

The dataset used in this project is:

```text
loan_default_risk_dataset.csv
```

The target variable is:

```text
Loan_Default_Risk
```

The target is separated from the input features using:

```python
x = df.drop(columns='Loan_Default_Risk')
y = df['Loan_Default_Risk']
```

---

# 🔍 Data Inspection

The dataset is inspected using Pandas operations such as:

```python
df
```

```python
df.duplicated().any()
```

```python
df.isnull().any()
```

These operations help identify duplicate records and missing values.

---

# ✂️ Train-Test Split

The dataset is divided into training and testing sets using:

```python
train_test_split()
```

The project uses:

```python
train_size=0.8
```

and:

```python
random_state=42
```

This creates separate datasets for model training and evaluation.

---

# 🧹 Missing Value Handling

Missing numerical values are handled using:

```python
SimpleImputer(strategy='mean')
```

This replaces missing values with the mean value of the corresponding feature.

---

# ⚖️ Feature Scaling

Two different scaling techniques are used in the preprocessing pipelines.

### RobustScaler

`RobustScaler` is applied to:

```text
Debt_Amount
```

### StandardScaler

`StandardScaler` is applied to:

```text
Retirement_Age
Monthly_Savings
```

---

# 🔄 ColumnTransformer

The different preprocessing pipelines are combined using:

```python
ColumnTransformer()
```

The preprocessing workflow is:

```text
Debt_Amount
     ↓
SimpleImputer
     ↓
RobustScaler


Retirement_Age
Monthly_Savings
     ↓
SimpleImputer
     ↓
StandardScaler
```

These transformations are combined using `ColumnTransformer`.

---

# 🔗 Machine Learning Pipeline

The preprocessing and Logistic Regression model are combined using Scikit-learn's `Pipeline`.

```python
main_pipeline = Pipeline(
    steps=[
        ('pre1', preprocessing),
        ('model', LogisticRegression(
            penalty=None,
            solver='lbfgs'
        ))
    ]
)
```

The complete workflow becomes:

```text
Raw Dataset
     ↓
Train-Test Split
     ↓
ColumnTransformer
     ↓
Missing Value Imputation
     ↓
Feature Scaling
     ↓
Logistic Regression
     ↓
Predictions
     ↓
Classification Evaluation
```

---

# 🤖 Logistic Regression

The classification algorithm used in this project is:

```python
LogisticRegression(
    penalty=None,
    solver='lbfgs'
)
```

The model is trained using:

```python
main_pipeline.fit(xtrain, ytrain)
```

---

# 🔮 Predictions

Predictions are generated separately for training and testing datasets:

```python
ytrain_pred = main_pipeline.predict(xtrain)
```

```python
ytest_pred = main_pipeline.predict(xtest)
```

This allows the model's performance to be evaluated on both training and unseen testing data.

---

# 📊 Classification Metrics

The project evaluates the model using several classification metrics.

## 🔲 Confusion Matrix

The confusion matrix is calculated for both training and testing predictions.

```python
confusion_matrix(ytrain, ytrain_pred)
```

```python
confusion_matrix(ytest, ytest_pred)
```

The Confusion Matrix helps understand:

- True Positives
- True Negatives
- False Positives
- False Negatives

---

## 🎯 Precision Score

Precision is calculated using:

```python
precision_score(
    ytrain,
    ytrain_pred,
    pos_label=0
)
```

Precision helps measure how accurately the model identifies a particular positive class.

---

## 📈 Accuracy Score

Training accuracy is calculated using:

```python
accuracy_score(
    ytrain,
    ytrain_pred
)
```

The project also compares training and testing performance.

---

## 📋 Classification Report

A complete classification report is generated for both training and testing data:

```python
print(classification_report(
    ytrain,
    ytrain_pred
))
```

```python
print(classification_report(
    ytest,
    ytest_pred
))
```

The classification report provides metrics such as:

- Precision
- Recall
- F1 Score
- Support

---

# 📈 Model Performance

According to the notebook's final observation:

```text
Train Score → 100%
Test Score  → 98%
```

The notebook concludes that the model demonstrates good performance based on these results.

---

# 🧠 Concepts Learned

Through this project, I practiced:

- ✅ Train-Test Split
- ✅ Missing Value Handling
- ✅ SimpleImputer
- ✅ RobustScaler
- ✅ StandardScaler
- ✅ ColumnTransformer
- ✅ Pipeline
- ✅ Logistic Regression
- ✅ Model Prediction
- ✅ Confusion Matrix
- ✅ Accuracy Score
- ✅ Precision Score
- ✅ Classification Report
- ✅ Precision
- ✅ Recall
- ✅ F1 Score
- ✅ Model Performance Analysis

---

# 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 📊 Seaborn
- 🤖 Scikit-learn
- 📓 Jupyter Notebook

---

# 📁 Project Structure

```text
Loan-Default-Risk-Classification-Metrics
│
├── Loan_Default_Risk.ipynb
├── loan_default_risk_dataset.csv
└── README.md
```

---

# 🔄 End-to-End Workflow

```text
              Loan Default Dataset
                       ↓
                 Data Inspection
                       ↓
              Check Missing Values
                       ↓
               Feature / Target Split
                       ↓
                 Train-Test Split
                       ↓
              ┌────────┴─────────┐
              ↓                  ↓
        Debt_Amount       Retirement_Age
              ↓            Monthly_Savings
       SimpleImputer            ↓
              ↓          SimpleImputer
        RobustScaler            ↓
              │          StandardScaler
              └────────┬─────────┘
                       ↓
                ColumnTransformer
                       ↓
                    Pipeline
                       ↓
               Logistic Regression
                       ↓
                   Predictions
                       ↓
              Model Evaluation
                       ↓
          ┌────────────┼────────────┐
          ↓            ↓            ↓
     Confusion      Accuracy    Classification
      Matrix                       Report
                       ↓
              Model Performance
```

---

# 🎯 Learning Outcome

Through this project, I learned how classification metrics can be applied to a practical Loan Default Risk prediction problem.

I also learned how preprocessing, feature scaling, ColumnTransformer, Pipeline, Logistic Regression, and classification evaluation can be combined into a complete Machine Learning workflow.

---

# 📌 Project Information

| Category | Details |
|---|---|
| 📅 Day | 16 |
| 🎯 Topic | Classification Metrics |
| 🏦 Problem | Loan Default Risk |
| 🤖 Algorithm | Logistic Regression |
| 🔄 Preprocessing | SimpleImputer + Scaling |
| ⚙️ Transformer | ColumnTransformer |
| 🔗 Workflow | Pipeline |
| 📊 Evaluation | Confusion Matrix, Accuracy, Precision, Classification Report |
| ✅ Status | Completed |

---

# 🚀 Machine Learning Journey

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
Day 16 → Loan Default Risk — Classification Metrics ⭐
```

---

## ⭐ Project Status

**Day 16 — Completed**

> Learn → Implement → Evaluate → Analyze → Improve 🚀