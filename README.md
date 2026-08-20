🤖 MACHINE LEARNING

🚀 A Hands-On Journey from Fundamentals to Practical Machine Learning

Learn → Implement → Analyze → Improve → Repeat

A structured collection of Machine Learning concepts and practical projects developed through continuous hands-on learning.

This repository documents my progression from regression and data preprocessing to classification, model evaluation, and real-world prediction problems using Python and Scikit-learn.

📖 ABOUT THIS REPOSITORY

This repository represents my practical Machine Learning learning journey.

Each project is designed to understand not only the algorithm, but the complete Machine Learning workflow:

Data
  ↓
Data Understanding
  ↓
Data Preprocessing
  ↓
Feature Engineering
  ↓
Feature Transformation
  ↓
Model Building
  ↓
Prediction
  ↓
Model Evaluation
  ↓
Performance Analysis

Core areas covered

📥 Data Loading & Inspection

🧹 Data Cleaning & Preprocessing

🧩 Missing Value Handling

🏷️ Categorical Encoding

⚖️ Feature Scaling

🔄 Column-wise Transformation

🔗 Machine Learning Pipelines

🏗️ Feature Engineering

🤖 Model Training

🎯 Classification

📊 Model Evaluation

📈 Visualization

📉 Performance Analysis

🛠️ TECHNOLOGY STACK

Technology

Purpose

🐍 Python

Programming & Machine Learning

🔢 NumPy

Numerical Computing

🐼 Pandas

Data Manipulation & Analysis

📊 Matplotlib

Data Visualization

📈 Seaborn

Statistical Visualization

🤖 Scikit-learn

Machine Learning & Preprocessing

🎯 category_encoders

Advanced Categorical Encoding

📓 Jupyter Notebook

Interactive Development

📂 REPOSITORY STRUCTURE

Machine-Learning
│
├── Linear-Regression
├── Polynomial-Regression
├── Multiple-Linear-Regression
│
├── Feature-Scaling-StandardScaler
├── Feature-Scaling-MinMaxScaler
│
├── Label-Encoding
├── OneHot-Encoding
├── Ordinal-Encoding
├── Target-Encoding
│
├── Column-Transformer
├── Column-Transformer-Multiple-Transformers
├── Pipeline-ColumnTransformer-LogisticRegression
├── Missing-Value-Imputation-SimpleImputer
│
├── Logistic-Regression-Loan-Approval
├── Classification-Metrics-Loan-Data
│
├── Loan-Default-Risk-Classification-Metrics
│   ├── Loan_Default_Risk.ipynb
│   ├── loan_default_risk_dataset.csv
│   └── README.md
│
└── README.md

📚 PROJECT PORTFOLIO

#

Project

Key Concept

01

📈 Linear Regression

Continuous Value Prediction

02

📊 Polynomial Regression

Non-Linear Relationships

03

📉 Multiple Linear Regression

Multiple Features

04

⚖️ Feature Scaling — StandardScaler

Standardization

05

📏 Feature Scaling — MinMaxScaler

Normalization

06

🏷️ Label Encoding

Categorical Encoding

07

🔢 One-Hot Encoding

Dummy Variables

08

🔠 Ordinal Encoding

Ordered Categories

09

🎯 Target Encoding

Target-Based Encoding

10

🔄 Column Transformer

Column-Wise Preprocessing

11

⚙️ Column Transformer — Multiple Transformers

Combined Transformations

12

🔗 Pipeline with ColumnTransformer & Logistic Regression

End-to-End Pipeline

13

🧹 Missing Value Imputation — SimpleImputer

Missing Data Handling

14

🤖 Logistic Regression — Loan Approval

Binary Classification

15

📊 Classification Metrics — Loan Data

Model Evaluation

16

🏦 Loan Default Risk — Classification Metrics

Practical Classification

🚀 WHAT YOU'LL FIND IN EACH PROJECT

Depending on the project, the implementation may include:

📄 Dataset

📓 Jupyter Notebook

📘 Project README

🔍 Data Exploration

🧹 Data Preprocessing

🏷️ Encoding

⚖️ Feature Scaling

🔄 Feature Transformation

🔗 Pipeline Construction

🤖 Model Training

🔮 Prediction

📊 Evaluation

📈 Visualization

🧠 Performance Analysis

🎯 LEARNING ROADMAP

01 — 📈 REGRESSION

Linear Regression

Polynomial Regression

Multiple Linear Regression

02 — 🧹 DATA PREPROCESSING

Data Cleaning

Missing Value Handling

SimpleImputer

Numerical Data Preprocessing

Categorical Data Preprocessing

03 — ⚖️ FEATURE SCALING

StandardScaler

MinMaxScaler

RobustScaler

04 — 🏷️ CATEGORICAL ENCODING

Label Encoding

One-Hot Encoding

Ordinal Encoding

Target Encoding

05 — 🔄 FEATURE TRANSFORMATION

ColumnTransformer

Multiple Column Transformations

Numerical Feature Transformation

Categorical Feature Transformation

06 — 🔗 MACHINE LEARNING PIPELINES

Train-Test Split

Pipeline

Preprocessing Pipeline

Combining Preprocessing and Models

07 — 🤖 CLASSIFICATION

Logistic Regression

Binary Classification

Classification Prediction

08 — 📊 MODEL EVALUATION

Confusion Matrix

Accuracy

Precision

Recall

F1 Score

Classification Report

Performance Analysis

📅 16-DAY MACHINE LEARNING JOURNEY

Day

Topic

Status

01

📈 Linear Regression

✅ Completed

02

📊 Polynomial Regression

✅ Completed

03

📉 Multiple Linear Regression

✅ Completed

04

⚖️ Feature Scaling — StandardScaler

✅ Completed

05

📏 Feature Scaling — MinMaxScaler

✅ Completed

06

🏷️ Label Encoding

✅ Completed

07

🔢 One-Hot Encoding

✅ Completed

08

🔠 Ordinal Encoding

✅ Completed

09

🎯 Target Encoding

✅ Completed

10

🔄 Column Transformer

✅ Completed

11

⚙️ Column Transformer — Multiple Transformers

✅ Completed

12

🔗 Pipeline with ColumnTransformer & Logistic Regression

✅ Completed

13

🧹 Missing Value Imputation — SimpleImputer

✅ Completed

14

🤖 Logistic Regression — Loan Approval Prediction

✅ Completed

15

📊 Classification Metrics — Loan Data

✅ Completed

16

🏦 Loan Default Risk — Classification Metrics

⭐ Completed

📊 CLASSIFICATION METRICS

A classification model should not always be evaluated using Accuracy alone.

Different metrics provide different perspectives on model performance.

🔲 CONFUSION MATRIX

A Confusion Matrix summarizes classification predictions into:



Predicted Positive

Predicted Negative

Actual Positive

True Positive (TP)

False Negative (FN)

Actual Negative

False Positive (FP)

True Negative (TN)

Four fundamental outcomes

TP — True Positive

TN — True Negative

FP — False Positive

FN — False Negative

🎯 ACCURACY

Measures the proportion of total predictions that are correct.

Accuracy =
(TP + TN) / (TP + TN + FP + FN)

🎯 PRECISION

Answers:

Of all samples predicted as positive, how many were actually positive?

Precision =
TP / (TP + FP)

🎯 RECALL

Answers:

Of all actual positive samples, how many were correctly identified?

Recall =
TP / (TP + FN)

🎯 F1 SCORE

F1 Score provides a balance between Precision and Recall.

F1 Score =
2 × (Precision × Recall)
/
(Precision + Recall)

🏦 LOAN DEFAULT RISK — DAY 16

Day 16 applies the classification evaluation concepts to a practical Loan Default Risk prediction problem.

The project combines:

Loan Default Risk Dataset
          ↓
    Data Inspection
          ↓
    Train-Test Split
          ↓
    Missing Value Handling
          ↓
      Feature Scaling
          ↓
    ColumnTransformer
          ↓
        Pipeline
          ↓
  Logistic Regression
          ↓
       Prediction
          ↓
 Classification Metrics

Techniques practiced

SimpleImputer

RobustScaler

StandardScaler

ColumnTransformer

Pipeline

Logistic Regression

Confusion Matrix

Accuracy

Precision

Classification Report

🧠 LEARNING PROGRESS

My learning progression has developed from basic predictive algorithms into a structured Machine Learning workflow:

REGRESSION
    ↓
DATA PREPROCESSING
    ↓
FEATURE SCALING
    ↓
CATEGORICAL ENCODING
    ↓
COLUMN TRANSFORMATION
    ↓
MACHINE LEARNING PIPELINES
    ↓
LOGISTIC REGRESSION
    ↓
CLASSIFICATION
    ↓
CLASSIFICATION METRICS
    ↓
LOAN DEFAULT RISK CLASSIFICATION
    ↓
ADVANCED MACHINE LEARNING

🎯 REPOSITORY GOALS

The main goals of this repository are to:

Build a strong foundation in Machine Learning

Understand algorithms through implementation

Develop practical data preprocessing skills

Understand feature transformation techniques

Learn how to handle missing values

Build reusable Machine Learning pipelines

Understand classification problems

Learn appropriate model evaluation techniques

Improve Python and Scikit-learn skills

Strengthen analytical and problem-solving abilities

Maintain clean and organized project documentation

Build a professional Machine Learning portfolio

🌟 UPCOMING LEARNING TOPICS

The next stages of my Machine Learning journey will include:

🌳 Decision Tree

🌲 Random Forest

📍 K-Nearest Neighbors (KNN)

📐 Support Vector Machine (SVM)

🎲 Naive Bayes

🔁 Cross Validation

🎛️ Hyperparameter Tuning

📊 Advanced Model Evaluation

🤝 Ensemble Learning

🧩 Clustering

🔵 K-Means

📉 Principal Component Analysis (PCA)

🚀 Real-World Machine Learning Projects

💡 KEY LEARNING

There is no single classification metric that is best for every problem.

The appropriate evaluation metric depends on:

Class distribution

Business requirements

Cost of False Positives

Cost of False Negatives

Importance of Precision vs Recall

A complete evaluation should therefore consider multiple metrics.

                 CLASSIFICATION MODEL
                         ↓
                    PREDICTIONS
                         ↓
                  CONFUSION MATRIX
                         ↓
              ┌──────────┴──────────┐
              ↓                     ↓
          ACCURACY            OTHER METRICS
                                    ↓
                         ┌──────────┼──────────┐
                         ↓          ↓          ↓
                    PRECISION     RECALL    F1 SCORE
                         └──────────┼──────────┘
                                    ↓
                         MODEL PERFORMANCE

⭐ WHY THIS REPOSITORY?

This repository represents my Machine Learning journey through consistent practice and implementation.

Instead of learning algorithms only theoretically, I am building projects to understand how different Machine Learning techniques fit together in an end-to-end workflow.

The journey so far:

Regression → Preprocessing → Feature Transformation → Pipelines → Classification → Model Evaluation → Loan Default Risk

The repository will continue to grow as I learn more advanced Machine Learning concepts and work on practical projects.

📈 CURRENT PROGRESS

🟢 16 Days Completed

████████████████████████████████████████
16 Days of Machine Learning

Status: 🚀 Continuously Learning

📬 CONNECT

Thank you for visiting my Machine Learning repository! 🤖

If you find these projects useful or interesting, feel free to ⭐ Star the repository.

🚀 Keep Learning. Keep Building. Keep Improving.

Learn → Implement → Analyze → Improve → Repeat
