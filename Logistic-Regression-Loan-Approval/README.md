# 📅 Day 14 — Logistic Regression: Loan Approval Prediction

> **A binary classification project using Logistic Regression, feature preprocessing, and model evaluation**

---

## 📌 Project Overview

This project focuses on implementing **Logistic Regression** for a binary classification problem using a loan approval dataset.

The project demonstrates a complete Machine Learning workflow:

```text
Dataset
   ↓
Data Inspection
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Feature Identification
   ↓
Data Preprocessing
   ↓
ColumnTransformer
   ↓
Machine Learning Pipeline
   ↓
Logistic Regression
   ↓
Prediction
   ↓
Classification Metrics
```

---

## 🎯 Objective

The main objective of this project is to understand how **Logistic Regression** can be used to classify loan applications into different approval categories.

The project also demonstrates how numerical and categorical features can be preprocessed before being passed to a classification model.

---

## 📊 Dataset

The project uses a **loan approval dataset** containing numerical and categorical features.

The target variable is:

```text
loan_status
```

The target is used to determine whether a loan application belongs to an approval or rejection category.

---

## 🔍 Data Exploration

The dataset is loaded using Pandas:

```python
df = pd.read_csv('loan_approval_dataset.csv')
```

The notebook uses:

```python
df.info()
```

to inspect the structure and data types of the dataset.

---

## 🎯 Feature & Target Separation

The target column is separated from the input features:

```python
x = df.drop(columns=[' loan_status'])
y = df[' loan_status']
```

Where:

- `X` → Input features
- `y` → Target variable

---

## ✂️ Train-Test Split

The dataset is divided into training and testing data using:

```python
train_test_split()
```

The notebook uses:

```python
train_size=0.8
```

with:

```python
random_state=42
```

This creates separate datasets for model training and evaluation.

---

# 🧹 Data Preprocessing

The dataset contains both **numerical** and **categorical** features.

Therefore, different preprocessing techniques are applied to each type of feature.

---

## 🔢 Numerical Features

Numerical columns are identified using:

```python
num_cols = x.select_dtypes(
    include='number'
).columns
```

The numerical features are scaled using:

```python
MinMaxScaler()
```

This transforms numerical features into a common scale.

---

## 🔤 Categorical Features

Categorical columns are identified using:

```python
cat_cols = x.select_dtypes(
    include='object'
).columns
```

Categorical features are encoded using:

```python
OneHotEncoder(
    handle_unknown='ignore'
)
```

This converts categorical values into numerical representations suitable for Machine Learning.

---

# 🔄 ColumnTransformer

Different transformations are combined using Scikit-learn's `ColumnTransformer`.

```python
preprocessing = ColumnTransformer(
    transformers=[
        (
            'scaling',
            MinMaxScaler(),
            num_cols
        ),
        (
            'encoder',
            OneHotEncoder(
                handle_unknown='ignore'
            ),
            cat_cols
        )
    ]
)
```

This allows numerical and categorical features to be processed differently within the same preprocessing workflow.

---

# 🔗 Machine Learning Pipeline

The preprocessing stage and Logistic Regression model are combined using Scikit-learn's `Pipeline`.

```python
main_pipeline = Pipeline(
    steps=[
        ('pre', preprocessing),
        (
            'model',
            LogisticRegression(
                penalty='l1',
                solver='liblinear'
            )
        )
    ]
)
```

The complete workflow becomes:

```text
Raw Features
     ↓
ColumnTransformer
     ↓
 ┌───────────────┐
 │               │
 ▼               ▼
Numerical     Categorical
 │               │
 ▼               ▼
MinMaxScaler  OneHotEncoder
 │               │
 └───────┬───────┘
         ▼
Logistic Regression
         ↓
    Prediction
```

---

# 🤖 Logistic Regression

The classification model used in this project is:

```python
LogisticRegression(
    penalty='l1',
    solver='liblinear'
)
```

The notebook also explores different combinations of Logistic Regression penalties and solvers and notes cases where particular combinations result in errors.

This helped me understand that **not every solver supports every regularization penalty**.

---

# 📈 Model Evaluation

The project evaluates the classification model using several metrics.

### Confusion Matrix

```python
confusion_matrix()
```

The confusion matrix is calculated separately for:

- Training predictions
- Testing predictions

---

### Precision Score

```python
precision_score()
```

Precision is evaluated for both:

```text
Approved
Rejected
```

classes.

---

### Additional Metrics

The notebook imports:

```python
accuracy_score
precision_score
recall_score
f1_score
```

These metrics can be used to evaluate classification performance from different perspectives.

---

# 🧠 Concepts Learned

Through this project, I practiced:

- ✅ Logistic Regression
- ✅ Binary Classification
- ✅ Train-Test Split
- ✅ Numerical Feature Identification
- ✅ Categorical Feature Identification
- ✅ MinMaxScaler
- ✅ OneHotEncoder
- ✅ ColumnTransformer
- ✅ Machine Learning Pipeline
- ✅ L1 Regularization
- ✅ Logistic Regression Solvers
- ✅ Confusion Matrix
- ✅ Precision Score
- ✅ Recall
- ✅ F1 Score
- ✅ Model Evaluation

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming |
| 🐼 Pandas | Data loading and manipulation |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 📈 Seaborn | Visualization |
| 🤖 Scikit-learn | Preprocessing, Pipeline, Logistic Regression and evaluation |
| 📓 Jupyter Notebook | Development and experimentation |
| 🎯 category_encoders | Encoding utilities |

---

# 📁 Project Structure

```text
Logistic-Regression-Loan-Approval
│
├── Logistic-Regression-Loan-Approval.ipynb
├── loan_approval_dataset.csv
└── README.md
```

---

# 🔄 End-to-End Workflow

```text
                  Loan Dataset
                       │
                       ▼
                 Data Inspection
                       │
                       ▼
               Feature / Target Split
                       │
                       ▼
                 Train-Test Split
                       │
                       ▼
              Identify Feature Types
                 /             \
                /               \
               ▼                 ▼
        Numerical Features   Categorical Features
               │                 │
               ▼                 ▼
         MinMaxScaler       OneHotEncoder
               │                 │
               └────────┬────────┘
                        ▼
                 ColumnTransformer
                        │
                        ▼
                    Pipeline
                        │
                        ▼
               Logistic Regression
                        │
                        ▼
                   Predictions
                        │
                        ▼
               Model Evaluation
                        │
             ┌──────────┼──────────┐
             ▼          ▼          ▼
        Confusion    Precision    Other
         Matrix        Score      Metrics
```

---

# 💡 Key Takeaways

This project helped me understand that Logistic Regression is not just about creating a model.

A complete classification workflow also requires:

```text
Data Preparation
       +
Feature Preprocessing
       +
ColumnTransformer
       +
Pipeline
       +
Model Training
       +
Model Evaluation
```

I also learned how different preprocessing techniques can be integrated into a single Machine Learning pipeline.

---

# 🎯 Learning Outcome

After completing this project, I gained practical experience in:

- Building a Logistic Regression classification model
- Preparing numerical and categorical features
- Scaling numerical data
- Encoding categorical data
- Combining preprocessing techniques using `ColumnTransformer`
- Creating an end-to-end Machine Learning `Pipeline`
- Understanding Logistic Regression regularization and solvers
- Evaluating classification models using different metrics

---

# 📌 Project Information

| Category | Details |
|---|---|
| 📅 Day | 14 |
| 🤖 Algorithm | Logistic Regression |
| 🎯 Problem Type | Classification |
| 📊 Dataset | Loan Approval Dataset |
| ⚙️ Preprocessing | MinMaxScaler + OneHotEncoder |
| 🔄 Transformer | ColumnTransformer |
| 🔗 Workflow | Scikit-learn Pipeline |
| 📈 Evaluation | Confusion Matrix, Precision, Recall, F1 Score |
| ✅ Status | Completed |

---

# 🚀 Machine Learning Journey

This project is part of my ongoing Machine Learning journey, where I am learning and implementing concepts step-by-step through practical projects.

### Progress

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
Day 14 → Logistic Regression — Loan Approval Prediction ⭐
```

---

## ⭐ Project Status

**Completed — Day 14**

More Machine Learning concepts and projects coming soon. 🚀