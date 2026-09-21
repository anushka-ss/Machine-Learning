# Updated `README.md`

````markdown
# 🤖 MACHINE LEARNING

### 🚀 A Hands-On Journey from Fundamentals to Practical Machine Learning

Welcome to my **Machine Learning journey**!

This repository documents my hands-on learning experience with **Machine Learning algorithms, data preprocessing techniques, feature engineering, model evaluation, hyperparameter tuning, and practical ML workflows**.

Each project focuses on understanding concepts practically by implementing them using **Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn**.

---

# 📌 ABOUT THIS REPOSITORY

This repository is a collection of my **Machine Learning practice projects and implementations**.

My approach is to learn Machine Learning step-by-step:

> **Understand the Concept → Preprocess the Data → Build the Model → Tune the Model → Evaluate the Model → Analyze the Results**

The repository is continuously updated as I learn and implement new concepts.

---

# 🛠️ TECHNOLOGY STACK

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming Language |
| 🔢 NumPy | Numerical Computing |
| 🐼 Pandas | Data Manipulation & Analysis |
| 📊 Matplotlib | Data Visualization |
| 📈 Seaborn | Statistical Visualization |
| 🤖 Scikit-learn | Machine Learning |
| 📓 Jupyter Notebook | Development & Experimentation |
| 🔧 Git & GitHub | Version Control & Portfolio |

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
├── GridSearchCV-Hyperparameter-Tuning
│   ├── GridSearchCV_Hyperparameter_Tuning.ipynb
│   ├── loan_data.csv
│   └── README.md
│
├── K-Nearest-Neighbour
│   ├── KNN_Diabetes_Classification.ipynb
│   ├── diabetes.csv
│   └── README.md
│
├── SVM
│   ├── SVM_Binary_Classification.ipynb
│   ├── loan_data.csv
│   └── README.md
│
└── README.md
````

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

### Preprocessing Workflow

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

# 🎯 18 — GRIDSEARCHCV — HYPERPARAMETER TUNING

Implemented **GridSearchCV** to understand how hyperparameter tuning can be used to find suitable configurations for a Machine Learning model.

This project uses **Decision Tree Classification** with a Loan dataset.

## 🔍 WHAT IS HYPERPARAMETER TUNING?

Hyperparameters are settings of a Machine Learning model that are defined **before the training process**.

Examples include:

* `max_depth`
* `min_samples_split`
* `min_samples_leaf`
* `criterion`
* `splitter`
* `max_features`

Hyperparameter tuning helps search for combinations of values and evaluate them using cross-validation.

## 🤖 MODEL USED

```python
DecisionTreeClassifier(random_state=42)
```

## ⚙️ GRIDSEARCHCV

The parameter grid used in this project includes:

```python
param_grid = {
    'criterion': ['gini', 'entropy'],
    'splitter': ['best', 'random'],
    'max_depth': [None, 5, 10, 20],
    'min_samples_split': [2, 3, 5, 7],
    'min_samples_leaf': [1, 3, 5, 7],
    'max_features': ['sqrt', 'log2']
}
```

## 🔢 GRID SEARCH COMBINATIONS

```text
2 × 2 × 4 × 4 × 4 × 2
= 512 combinations
```

With:

```python
cv=3
```

GridSearchCV evaluates every combination using 3-fold cross-validation.

Therefore:

```text
512 parameter combinations
        ×
3 Cross-Validation folds
        =
1536 Fits
```

## 🔄 GRIDSEARCHCV WORKFLOW

```text
                📂 Loan Dataset
                       ↓
                🔍 Data Preparation
                       ↓
                 ✂️ Train-Test Split
                       ↓
              🌳 Decision Tree
                       ↓
              ⚙️ Parameter Grid
                       ↓
                🔎 GridSearchCV
                       ↓
              🔁 3-Fold CV
                       ↓
              📊 512 Combinations
                       ↓
              🏆 Best Parameters
                       ↓
              🤖 Best Estimator
                       ↓
              📈 Model Evaluation
```

## 🧠 KEY CONCEPTS LEARNED

* Hyperparameters
* Hyperparameter Tuning
* GridSearchCV
* Cross-Validation
* Parameter Grid
* Decision Tree Optimization
* Best Parameters
* Best Estimator
* Cross-Validation Results
* Model Selection

---

# 🤖 19 — K-NEAREST NEIGHBOUR (KNN)

Implemented the **K-Nearest Neighbour (KNN)** algorithm for a classification problem using the **Diabetes dataset**.

This project focuses on understanding a distance-based Machine Learning algorithm, feature scaling, Pipeline implementation, and hyperparameter tuning using GridSearchCV.

## 🧠 WHAT IS K-NEAREST NEIGHBOUR?

**K-Nearest Neighbour (KNN)** is a supervised Machine Learning algorithm that can be used for classification and regression.

For classification, KNN predicts the class of a new data point based on the classes of its nearest neighbouring data points.

### Basic Workflow

```text
New Data Point
      ↓
Find Nearest Neighbours
      ↓
Check Their Classes
      ↓
Majority Voting
      ↓
Predicted Class
```

## 🩺 DIABETES CLASSIFICATION

The **Diabetes dataset** is used for this project.

The target variable is:

```text
Outcome
```

The features include:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

## 📏 FEATURE SCALING

KNN is a **distance-based algorithm**.

Therefore, feature scaling is important so that features with different numerical ranges do not disproportionately affect distance calculations.

This project uses:

```python
RobustScaler()
```

## 🔄 MACHINE LEARNING PIPELINE

The KNN workflow uses a Scikit-learn `Pipeline`.

```python
Pipeline(
    steps=[
        ('scaling', RobustScaler()),
        ('model', KNeighborsClassifier())
    ]
)
```

### Workflow

```text
📂 Diabetes Dataset
        ↓
🔍 Data Exploration
        ↓
🎯 Feature / Target Separation
        ↓
✂️ Train-Test Split
        ↓
📏 RobustScaler
        ↓
🤖 KNeighborsClassifier
        ↓
🔎 GridSearchCV
        ↓
📊 Model Evaluation
```

## ⚙️ HYPERPARAMETER TUNING

The parameter grid includes:

```python
param_grid = {
    'model__n_neighbors': [5, 21, 23, 25, 27],
    'model__metric': ['euclidean', 'manhattan']
}
```

This gives:

```text
5 neighbour values
×
2 distance metrics
=
10 combinations
```

## 🔁 CROSS-VALIDATION

The GridSearchCV configuration uses:

```python
cv=20
```

Therefore:

```text
10 parameter combinations
        ×
20 Cross-Validation folds
        =
200 Fits
```

## 🏆 BEST PARAMETERS

The GridSearchCV execution identified:

```python
{
    'model__metric': 'euclidean',
    'model__n_neighbors': 21
}
```

Therefore, the selected KNN configuration uses:

```text
Number of Neighbours = 21
Distance Metric      = Euclidean
```

The GridSearchCV scoring metric used was:

```python
scoring='f1'
```

## 📊 MODEL EVALUATION

The final model is evaluated using:

```python
classification_report()
```

The classification report provides:

* Precision
* Recall
* F1-Score
* Support
* Accuracy

## 🧠 KEY CONCEPTS LEARNED

* K-Nearest Neighbour
* Distance-Based Classification
* Choosing the value of K
* Euclidean Distance
* Manhattan Distance
* Feature Scaling
* RobustScaler
* Pipeline
* GridSearchCV
* Cross-Validation
* Hyperparameter Tuning
* Classification Report
* Precision
* Recall
* F1-Score
* Accuracy

## 🔄 END-TO-END KNN WORKFLOW

```text
              📂 Dataset
                   ↓
            🔍 Data Exploration
                   ↓
          🎯 Feature / Target Split
                   ↓
            ✂️ Train-Test Split
                   ↓
             📏 RobustScaler
                   ↓
          🤖 KNN Classifier
                   ↓
             ⚙️ Parameter Grid
                   ↓
             🔎 GridSearchCV
                   ↓
            🔁 20-Fold CV
                   ↓
             🏆 Best Model
                   ↓
            🔮 Predictions
                   ↓
           📊 Classification Report
```

---

# 🤖 20 — SUPPORT VECTOR MACHINE (SVM)

Implemented **Support Vector Machine (SVM)** using `SVC` for a **binary classification** problem.

This project focuses on understanding how SVM can separate two classes using a decision boundary and how preprocessing, pipelines, and hyperparameter tuning can be combined in a Machine Learning workflow.

## 📌 PROJECT FOCUS

The Day 20 project covers:

* Support Vector Machine
* Support Vector Classifier
* Binary Classification
* Decision Boundary
* Support Vectors
* SVM Kernels
* One-Hot Encoding
* StandardScaler
* ColumnTransformer
* Pipeline
* GridSearchCV
* Hyperparameter Tuning
* Classification Evaluation

## 🧠 WHAT IS SVM?

**Support Vector Machine (SVM)** is a supervised Machine Learning algorithm used for classification and regression.

For classification, SVM attempts to find a decision boundary that separates different classes while maximizing the margin between them.

```text
Class 0                    Class 1

● ● ● ●                  ○ ○ ○ ○
 ● ● ●                    ○ ○
     ●                  ○
          |       |
          |       |
       Decision Boundary
```

## 🎯 BINARY CLASSIFICATION

This project uses SVM for **binary classification**.

The target variable is:

```text
loan_status
```

The target contains two classes:

```text
0
1
```

The SVM model learns a decision boundary to separate the two classes.

> **Note:** Day 20 currently demonstrates binary SVM classification. Multiclass SVM will be added as a separate implementation when executed.

## 📂 DATASET

The project uses a **Loan dataset**.

The target column is:

```text
loan_status
```

The dataset contains numerical and categorical features that require preprocessing before model training.

## 🔄 DATA PREPROCESSING

The project applies different preprocessing techniques to numerical and categorical features.

### 🔤 Categorical Features

Categorical features are transformed using:

```python
OneHotEncoder()
```

### 📏 Numerical Features

Numerical features are scaled using:

```python
StandardScaler()
```

## 🔧 COLUMN TRANSFORMER

`ColumnTransformer` is used to apply the appropriate preprocessing technique to each type of feature.

```python
preprocessing = ColumnTransformer(
    transformers=[
        ('encoder', OneHotEncoder(), cat_cols),
        ('scaling', StandardScaler(), num_cols)
    ]
)
```

## 🔄 MACHINE LEARNING PIPELINE

The preprocessing steps and SVM model are combined using a Scikit-learn Pipeline.

```python
main_pipeline = Pipeline(
    steps=[
        ('pre', preprocessing),
        ('model', SVC())
    ]
)
```

### Workflow

```text
📂 Loan Dataset
      ↓
🔍 Data Preparation
      ↓
🎯 Feature / Target Separation
      ↓
✂️ Train-Test Split
      ↓
🔤 One-Hot Encoding
      ↓
📏 StandardScaler
      ↓
🔧 ColumnTransformer
      ↓
🔄 Pipeline
      ↓
🤖 SVC
      ↓
🔎 GridSearchCV
      ↓
📊 Model Evaluation
```

## ⚙️ SVM HYPERPARAMETERS

The project uses GridSearchCV to search different SVM configurations.

### `C`

The `C` parameter controls the trade-off between the margin and classification errors.

### `kernel`

The project searches the following kernels:

```text
rbf
linear
sigmoid
poly
```

### `degree`

For the polynomial kernel, different polynomial degrees are tested:

```text
2
3
5
```

## 🔎 GRIDSEARCHCV

The parameter grid used is:

```python
param_grid = {
    'model__C': [0.001, 0.01, 0.1, 1, 10, 100],
    'model__kernel': ['rbf', 'linear', 'sigmoid', 'poly'],
    'model__degree': [2, 3, 5]
}
```

GridSearchCV searches through the specified combinations to identify a suitable SVM configuration.

## 📊 MODEL EVALUATION

The final SVM model is evaluated using:

```python
classification_report()
```

The classification report provides:

* Accuracy
* Precision
* Recall
* F1-Score
* Support

## 🧠 KEY CONCEPTS LEARNED

Through this project, I learned:

* Support Vector Machine
* Support Vector Classifier
* Binary Classification
* Decision Boundary
* Maximum Margin
* Support Vectors
* C Parameter
* SVM Kernels
* RBF Kernel
* Linear Kernel
* Polynomial Kernel
* Sigmoid Kernel
* Polynomial Degree
* One-Hot Encoding
* StandardScaler
* ColumnTransformer
* Pipeline
* GridSearchCV
* Hyperparameter Tuning
* Classification Report

## 🔄 END-TO-END SVM WORKFLOW

```text
              📂 Loan Dataset
                    ↓
             🔍 Data Preparation
                    ↓
          🎯 Feature / Target Split
                    ↓
             ✂️ Train-Test Split
                    ↓
          🔤 One-Hot Encoding
                    ↓
             📏 StandardScaler
                    ↓
            🔧 ColumnTransformer
                    ↓
                🔄 Pipeline
                    ↓
                 🤖 SVC
                    ↓
             ⚙️ Parameter Grid
                    ↓
              🔎 GridSearchCV
                    ↓
              🏆 Best Model
                    ↓
             🔮 Predictions
                    ↓
          📊 Classification Report
```

## 📌 IMPORTANT TAKEAWAY

SVM is a powerful supervised Machine Learning algorithm that can be used to separate classes by finding an appropriate decision boundary.

This project helped me understand how **SVC, feature preprocessing, pipelines, and GridSearchCV** can be combined into a complete Machine Learning classification workflow.

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
* K-Nearest Neighbour Classification
* Support Vector Machine Classification
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
* Robust Scaling

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

## 📌 Model Optimization

* Hyperparameters
* Parameter Grid
* GridSearchCV
* Cross-Validation
* Best Estimator Selection
* Decision Tree Hyperparameter Tuning
* KNN Hyperparameter Tuning
* SVM Hyperparameter Tuning
* Model Optimization

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
        ⚙️ Hyperparameter Tuning
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
 Hyperparameter Tuning
            ↓
 K-Nearest Neighbour
            ↓
Distance-Based Classification
            ↓
 Support Vector Machine
            ↓
 Binary Classification
            ↓
      SVM Kernels
            ↓
        🚀 Continuing...
```

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
| 17  | 🌳 Decision Tree — Classification & Regression        | ✅ Completed     |
| 18  | 🎯 GridSearchCV — Hyperparameter Tuning               | ✅ Completed     |
| 19  | 🤖 K-Nearest Neighbour — Diabetes Classification      | ✅ Completed     |
| 20  | 🤖 Support Vector Machine — Binary Classification     | ⭐ **Completed** |

---

# 🎯 CURRENT PROGRESS

## ⭐ DAY 20 COMPLETED

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
* Hyperparameter Tuning
* GridSearchCV
* Cross-Validation
* K-Nearest Neighbour
* Distance-Based Classification
* RobustScaler
* KNN Hyperparameter Tuning
* Support Vector Machine
* SVC
* Binary Classification
* SVM Kernels
* SVM Hyperparameter Tuning

The goal is to continue building a strong foundation through **hands-on implementation rather than only theoretical learning**.

---

# 🚀 REPOSITORY GOALS

The main goals of this repository are:

* Build a strong Machine Learning foundation
* Implement concepts using Python
* Practice data preprocessing
* Understand feature engineering
* Understand model evaluation
* Learn model optimization techniques
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
* Hyperparameter Tuning Techniques
* Classification Algorithms
* Regression Algorithms
* Practical Machine Learning Projects
* Multiclass Classification
* Advanced Machine Learning Concepts

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

### **Day 20 — Support Vector Machine completed.**

### **The journey continues... 🤖**

```
```
