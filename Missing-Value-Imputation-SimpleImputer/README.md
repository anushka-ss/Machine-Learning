# 🧹 Day 13 — Missing Value Imputation using SimpleImputer

> **Handling missing values in Machine Learning using Scikit-learn**

---

## 📌 Project Overview

Missing values are common in real-world datasets and can affect the performance of Machine Learning models.

In this project, I explored **Missing Value Imputation** using Scikit-learn's `SimpleImputer`.

The notebook demonstrates how missing values can be replaced using different imputation strategies.

---

## 🎯 Objective

The main objectives of this project are:

- Understand what missing values are
- Identify missing values in a dataset
- Learn different imputation strategies
- Use Scikit-learn's `SimpleImputer`
- Handle missing values in numerical and categorical data
- Understand why different data types may require different imputation strategies

---

## 📊 Sample Dataset

A small sample DataFrame is created with three columns:

| Column | Type | Missing Values |
|---|---|---|
| `col1` | Numerical | Yes |
| `col2` | Numerical | Yes |
| `col3` | Categorical | Yes |

Example structure:

```text
col1    col2    col3
1       20      A
0       25      B
NaN     NaN     NaN
3       NaN     C
7       30      D
```

---

## 🧩 SimpleImputer

Scikit-learn's `SimpleImputer` is used to replace missing values with a specified strategy.

```python
from sklearn.impute import SimpleImputer
```

---

## 🔧 Imputation Strategies Explored

### 1. Mean

```python
SimpleImputer(strategy="mean")
```

Replaces missing numerical values with the mean of the column.

In this notebook, applying `mean` directly to the complete mixed-type DataFrame results in an error because the DataFrame also contains categorical/string data.

---

### 2. Median

```python
SimpleImputer(strategy="median")
```

Replaces missing numerical values with the median of the column.

Similar to the mean strategy, it is not directly suitable for the mixed-type DataFrame used in this practice example.

---

### 3. Constant

```python
SimpleImputer(
    strategy="constant",
    fill_value=0
)
```

Replaces missing values with a specified constant value.

---

### 4. Most Frequent

```python
SimpleImputer(strategy="most_frequent")
```

Replaces missing values with the most frequently occurring value.

This is the strategy used in the final implementation of this notebook.

---

## 💻 Implementation

The final imputer used in the notebook is:

```python
imputer = SimpleImputer(strategy="most_frequent")
```

The transformation is then performed using:

```python
imputer.fit_transform(df)
```

For practice with numerical columns:

```python
imputer.fit_transform(df[['col1', 'col2']])
```

---

## 🔄 Workflow

```text
Dataset
   ↓
Identify Missing Values
   ↓
Select Imputation Strategy
   ↓
Create SimpleImputer
   ↓
Fit & Transform
   ↓
Replace Missing Values
   ↓
Use Cleaned Data for Machine Learning
```

---

## 📚 Concepts Learned

- Missing Values
- Missing Value Handling
- Data Imputation
- `SimpleImputer`
- Mean Imputation
- Median Imputation
- Constant Imputation
- Most Frequent Imputation
- `fit_transform()`
- Numerical Data Imputation
- Categorical Data Imputation

---

## 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 🤖 Scikit-learn
- 📓 Jupyter Notebook

---

## 📁 Project Structure

```text
Missing-Value-Imputation-SimpleImputer
│
├── SimpleImputer-Missing-Value-Imputation.ipynb
└── README.md
```

---

## 🎯 Learning Outcome

Through this project, I learned how missing values can be handled using `SimpleImputer`.

I also learned that the choice of imputation strategy depends on the type of data and that numerical and categorical features may require different approaches.

---

## 📌 Project Status

**Day:** 13

**Topic:** Missing Value Imputation

**Technique:** SimpleImputer

**Status:** ✅ Completed

---

## 🚀 Machine Learning Journey

This project is part of my ongoing Machine Learning learning journey, where I am building concepts step-by-step through hands-on implementation.

**Day 13 completed! 🎯**

More Machine Learning concepts coming soon. 🚀