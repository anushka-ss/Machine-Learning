🤖 MACHINE LEARNING

🚀 A Hands-On Journey from Fundamentals to Practical Machine Learning

Welcome to my Machine Learning journey!

This repository documents my hands-on learning experience with Machine Learning algorithms, data preprocessing techniques, feature engineering, model evaluation, hyperparameter tuning, and practical ML workflows.

Each project focuses on understanding concepts practically by implementing them using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

📌 ABOUT THIS REPOSITORY

This repository is a collection of my Machine Learning practice projects and implementations.

My approach is to learn Machine Learning step-by-step:

Understand the Concept → Preprocess the Data → Build the Model → Evaluate the Model → Analyze the Results

The repository is continuously updated as I learn and implement new concepts.

🛠️ TECHNOLOGY STACK

Technology

Purpose

🐍 Python

Programming Language

🔢 NumPy

Numerical Computing

🐼 Pandas

Data Manipulation & Analysis

📊 Matplotlib

Data Visualization

📈 Seaborn

Statistical Visualization

🤖 Scikit-learn

Machine Learning

📓 Jupyter Notebook

Development & Experimentation

🔧 Git & GitHub

Version Control & Portfolio

📂 REPOSITORY STRUCTURE

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
├── GridSearchCV
│   ├── cv1.ipynb
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
├── Naive-Bayes
│   ├── Naive_Bayes_Multinomial_Spam_Classification.ipynb
│   ├── spam.csv
│   └── README.md
│
├── Vectorization
│   ├── Vectorization_CountVectorizer_TFIDF.ipynb
│   ├── spam.csv
│   └── README.md
│
├── K-Means-Clustering
│   ├── KMeans_Clustering.ipynb
│   ├── Mall_Customers.csv
│   └── README.md
│
├── Imbalanced-Dataset
│   ├── Imbalanced_Dataset.ipynb
│   ├── spam.csv
│   └── README.md
│
├── Isolation-Forest
│   ├── Isolation_Forest_Anomaly_Detection.ipynb
│   └── README.md
│
└── README.md

📚 MACHINE LEARNING PROJECTS

📈 01 — LINEAR REGRESSION

Implemented the fundamentals of Linear Regression to understand the relationship between independent and dependent variables.

Concepts Covered

Simple Linear Regression

Independent and Dependent Variables

Train-Test Split

Model Training

Predictions

Model Evaluation

R² Score

📊 02 — POLYNOMIAL REGRESSION

Explored Polynomial Regression to understand how Machine Learning models can capture non-linear relationships.

Concepts Covered

Polynomial Features

Different Polynomial Degrees

Model Training

Predictions

Train vs Test Performance

Underfitting

Overfitting

R² Score

📈 03 — MULTIPLE LINEAR REGRESSION

Implemented Multiple Linear Regression using multiple independent variables to predict a target variable.

Concepts Covered

Multiple Features

Train-Test Split

Model Training

Prediction

Model Evaluation

R² Score

⚙️ DATA PREPROCESSING

Machine Learning models require properly prepared data.

The following preprocessing techniques have been implemented:

🔹 04 — STANDARD SCALER

Implemented feature scaling using Standardization with StandardScaler.

Concepts Covered

Feature Scaling

Standardization

Mean

Standard Deviation

Transformation of Numerical Features

🔹 05 — MINMAX SCALER

Implemented feature scaling using Min-Max Normalization with MinMaxScaler.

Concepts Covered

Feature Scaling

Normalization

Minimum and Maximum Values

Transformation of Numerical Features

🔹 06 — LABEL ENCODING

Implemented Label Encoding to convert categorical labels into numerical values.

Concepts Covered

Categorical Data

Numerical Representation

LabelEncoder

Encoding Categories

🔹 07 — ONE-HOT ENCODING

Implemented One-Hot Encoding to convert categorical variables into binary indicator columns.

Concepts Covered

Categorical Features

Dummy Variables

OneHotEncoder

Handling Multiple Categories

🔹 08 — ORDINAL ENCODING

Implemented Ordinal Encoding for categorical variables where the categories have a meaningful order.

Concepts Covered

Ordered Categories

OrdinalEncoder

Mapping Categories to Numerical Values

🔹 09 — TARGET ENCODING

Explored Target Encoding, where categorical variables are represented using information derived from the target variable.

Concepts Covered

Categorical Variables

Target-Based Encoding

Numerical Representation of Categories

🔧 COLUMN TRANSFORMER & PIPELINES

🔹 10 — COLUMN TRANSFORMER

Learned how to apply different preprocessing techniques to different columns within a dataset using ColumnTransformer.

Concepts Covered

ColumnTransformer

Numerical Feature Transformation

Categorical Feature Transformation

Multiple Preprocessing Steps

🔹 11 — COLUMN TRANSFORMER — MULTIPLE TRANSFORMERS

Implemented multiple preprocessing transformations together for handling different types of features.

Concepts Covered

Multiple Transformers

Numerical Preprocessing

Categorical Preprocessing

ColumnTransformer

Efficient Data Preparation

🔹 12 — PIPELINE WITH COLUMNTRANSFORMER & LOGISTIC REGRESSION

Combined preprocessing and Machine Learning into a single workflow using:

Pipeline

ColumnTransformer

LogisticRegression

This project helped understand how to build a clean and organized Machine Learning workflow.

🧹 MISSING VALUE HANDLING

🔹 13 — MISSING VALUE IMPUTATION

Implemented missing-value handling using:

SimpleImputer

Learned how missing values can be replaced using appropriate statistical strategies before training a Machine Learning model.

Concepts Covered

Missing Data

Data Cleaning

SimpleImputer

Mean Imputation

Median Imputation

Handling Missing Values Before Model Training

🏦 CLASSIFICATION PROJECTS

🔹 14 — LOGISTIC REGRESSION — LOAN APPROVAL PREDICTION

Implemented Logistic Regression for predicting loan approval.

Concepts Covered

Binary Classification

Logistic Regression

Feature Preprocessing

Train-Test Split

Model Training

Predictions

Classification Evaluation

📊 CLASSIFICATION METRICS

🔹 15 — CLASSIFICATION METRICS — LOAN DATA

Explored important classification evaluation metrics to understand how well a classification model performs.

Metrics Covered

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Classification Report

Understanding different metrics is important because accuracy alone may not always provide a complete picture of model performance.

🏦 LOAN DEFAULT RISK

🔹 16 — LOAN DEFAULT RISK — CLASSIFICATION METRICS

Applied classification evaluation techniques to a Loan Default Risk dataset.

Focus Areas

Classification Model Evaluation

Confusion Matrix

Accuracy

Precision

Recall

F1-Score

Classification Report

This project helped strengthen my understanding of evaluating classification models in a practical Machine Learning problem.

🌳 DECISION TREE

🔹 17 — DECISION TREE — CLASSIFICATION & REGRESSION

Implemented Decision Tree Machine Learning workflows for classification and regression problems.

📧 Decision Tree Classification — Spam Email Detection

Built a Decision Tree classification workflow using a Spam Email dataset.

Concepts Covered

DecisionTreeClassifier

Entropy

Maximum Tree Depth

One-Hot Encoding

ColumnTransformer

Pipeline

Classification Report

Model Evaluation

Model Configuration

DecisionTreeClassifier(
    random_state=42,
    criterion='entropy',
    max_depth=4
)

The preprocessing workflow includes:

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

🍷 Decision Tree Regression — Wine Quality

Explored a regression workflow using the Wine Quality dataset.

Regression Evaluation Metrics

R² Score

MAE

MSE

RMSE

🎯 GRIDSEARCHCV — HYPERPARAMETER TUNING

🔹 18 — GRIDSEARCHCV — DECISION TREE OPTIMIZATION

Implemented GridSearchCV to perform systematic hyperparameter tuning for a Decision Tree classification model.

Concepts Covered

GridSearchCV

Hyperparameter Tuning

Cross-Validation

Parameter Grid

Best Estimator

Model Evaluation

Hyperparameters Explored

param_grid = {
    'criterion': ['gini', 'entropy'],
    'splitter': ['best', 'random'],
    'max_depth': [None, 5, 10, 20],
    'min_samples_split': [2, 3, 5, 7],
    'min_samples_leaf': [1, 3, 5, 7],
    'max_features': ['sqrt', 'log2']
}

Cross-Validation

The project uses:

GridSearchCV(
    ...,
    cv=3
)

The parameter grid contains 512 parameter combinations, resulting in:

512 parameter combinations
        ×
3-fold Cross Validation
        ↓
1536 Model Fits

The project demonstrates how GridSearchCV can systematically search different hyperparameter combinations and select the best estimator based on the chosen evaluation criterion.

👥 K-NEAREST NEIGHBOUR

🔹 19 — K-NEAREST NEIGHBOUR — DIABETES CLASSIFICATION

Implemented K-Nearest Neighbour (KNN) for diabetes classification.

Concepts Covered

KNeighborsClassifier

Distance-Based Classification

RobustScaler

Pipeline

GridSearchCV

Cross-Validation

Hyperparameter Tuning

F1 Score

Classification Report

Workflow

Diabetes Dataset
        ↓
Train-Test Split
        ↓
RobustScaler
        ↓
Pipeline
        ↓
KNeighborsClassifier
        ↓
GridSearchCV
        ↓
Cross-Validation
        ↓
Classification Report

The project uses GridSearchCV to tune KNN parameters and evaluates the classification model using the F1 Score and classification report.

⚡ SUPPORT VECTOR MACHINE

🔹 20 — SVM — BINARY CLASSIFICATION

Implemented Support Vector Machine (SVM) using SVC for binary classification.

Concepts Covered

SVC

Support Vector Machine

Binary Classification

Decision Boundary

Support Vectors

Kernel Functions

C Parameter

Polynomial Degree

One-Hot Encoding

StandardScaler

ColumnTransformer

Pipeline

GridSearchCV

Classification Report

SVM Workflow

Loan Dataset
      ↓
Data Preprocessing
      ↓
One-Hot Encoding
      ↓
StandardScaler
      ↓
ColumnTransformer
      ↓
Pipeline
      ↓
SVC
      ↓
GridSearchCV
      ↓
Model Evaluation

Kernel Parameters Explored

{
    'model__C': [0.001, 0.01, 0.1, 1, 10, 100],
    'model__kernel': ['rbf', 'linear', 'sigmoid', 'poly'],
    'model__degree': [2, 3, 5]
}

The project focuses on binary classification using SVC and hyperparameter tuning through GridSearchCV.

🧠 NAIVE BAYES

🔹 21 — NAIVE BAYES — MULTINOMIAL TEXT CLASSIFICATION

Implemented Naive Bayes for text classification using a spam email/message dataset.

The Day 21 project specifically uses Multinomial Naive Bayes (MultinomialNB).

Concepts Covered

Naive Bayes

Bayes' Theorem

Bernoulli Naive Bayes

Gaussian Naive Bayes

Multinomial Naive Bayes

Text Classification

TF-IDF

TfidfVectorizer

MultinomialNB

Pipeline

Train-Test Split

Classification Report

Naive Bayes Variants

Variant

Common Use

Bernoulli Naive Bayes

Binary / Boolean features

Gaussian Naive Bayes

Continuous numerical features

Multinomial Naive Bayes

Count or frequency-based text features

Text Classification Workflow

Spam Dataset
      ↓
Text Data
      ↓
Train-Test Split
      ↓
TF-IDF Vectorization
      ↓
TfidfVectorizer
      ↓
MultinomialNB
      ↓
Pipeline
      ↓
Predictions
      ↓
Classification Report

Pipeline

main_pipeline = Pipeline([
    ('vectorizer', TfidfVectorizer()),
    ('model', MultinomialNB())
])

Evaluation

The model is evaluated using:

Classification Report

Precision

Recall

F1-Score

Note: The Day 21 notebook specifically executes Multinomial Naive Bayes. Bernoulli and Gaussian Naive Bayes are included as part of the Naive Bayes family being studied, but they are not executed in this Day 21 notebook.

🔤 VECTORIZATION

🔹 22 — VECTORIZATION — COUNTVECTORIZER & TF-IDF VECTORIZER

Implemented Text Vectorization techniques to convert text data into numerical features that Machine Learning models can process.

The Day 22 project focuses on:

CountVectorizer

TfidfVectorizer

N-grams

Stop Words

Text Feature Extraction

Sparse Matrix Representation

Numerical Representation of Text

📊 CountVectorizer

CountVectorizer converts text documents into numerical features based on the occurrence of words or n-grams.

Implementation

vectorizer = CountVectorizer(
    stop_words='english',
    binary=True,
    min_df=1,
    max_df=1.0,
    max_features=100,
    ngram_range=(2,2)
)

vectors = vectorizer.fit_transform(xtrain['v2'])

📈 TF-IDF Vectorizer

TF-IDF stands for Term Frequency — Inverse Document Frequency.

TfidfVectorizer represents text numerically while assigning weights based on the importance of terms across documents.

Implementation

tfidf_vectorizer = TfidfVectorizer(
    stop_words='english',
    max_features=100,
    ngram_range=(2,2)
)

tfidf_vectors = tfidf_vectorizer.fit_transform(xtrain['v2'])

🔄 Vectorization Workflow

Raw Text
   ↓
Text Preprocessing
   ↓
Vectorization
   ↓
Numerical Features
   ↓
Machine Learning Model

⚖️ CountVectorizer vs TF-IDF

CountVectorizer

TF-IDF

Represents word/ngram counts

Represents weighted term importance

Can use binary features

Produces weighted numerical values

Simple frequency-based representation

Reduces the influence of very common terms

Useful for basic text representation

Commonly used for text classification

📂 Dataset

The project uses a spam message dataset.

v1 → Message label

v2 → Message text

The v2 text column is converted into numerical features using vectorization techniques.

🛠️ Technologies Used

Python

Pandas

Scikit-learn

Jupyter Notebook

🎯 Learning Outcome

Through this project, I learned how to:

Convert text into numerical features

Use CountVectorizer

Use TF-IDF Vectorizer

Generate n-gram features

Remove stop words

Work with sparse matrices

Prepare text data for Machine Learning

🎯 K-MEANS CLUSTERING

🔹 23 — K-MEANS CLUSTERING — CUSTOMER SEGMENTATION

Implemented K-Means Clustering as an unsupervised Machine Learning technique using the Mall Customers dataset.

The Day 23 project focuses on:

Unsupervised Learning

K-Means Clustering

Customer Segmentation

Cluster Prediction

Inertia

Elbow Method

PCA

Cluster Visualization

K-Means Pipeline

📊 Dataset

The project uses the Mall Customers dataset containing customer-related features such as:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1-100)

🔹 K-Means Clustering

K-Means groups data points into clusters based on similarity.

The notebook first demonstrates K-Means with n_clusters=3, then applies the Elbow Method to compare inertia values for different cluster counts.

The notebook identifies 4 clusters as the selected value for the mall customer scenario and then visualizes the resulting clusters.

📐 Elbow Method & Inertia

The Elbow Method is used to help select an appropriate number of clusters.

Different K Values
        ↓
   K-Means Models
        ↓
 Calculate Inertia
        ↓
 Plot Inertia
        ↓
 Select Elbow Point
        ↓
 Choose K

📉 PCA — Dimensionality Reduction

The project also uses Principal Component Analysis (PCA) to transform the feature space into fewer dimensions for analysis and visualization.

Customer Features
        ↓
       PCA
        ↓
Reduced Dimensions
        ↓
Cluster Visualization

🔄 K-Means + PCA Pipeline

The notebook also demonstrates combining PCA and K-Means using a Scikit-learn Pipeline.

main_pipe = Pipeline(
    steps=[
        ('pca_', PCA(n_components=0.95)),
        ('model', KMeans(n_clusters=2, random_state=42))
    ]
)

Note: The notebook uses different cluster counts at different stages: 3 for the initial K-Means example, 4 after the Elbow Method, and 2 in the final PCA + K-Means pipeline.

🛠️ Technologies Used

Python

Pandas

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

🎯 Learning Outcome

Through this project, I learned how to:

Understand unsupervised learning

Apply K-Means clustering

Predict cluster assignments

Calculate and analyze inertia

Use the Elbow Method

Apply PCA for dimensionality reduction

Visualize clusters

Combine PCA and K-Means using a Pipeline

⚖️ IMBALANCED DATASET

🔹 24 — IMBALANCED DATASET HANDLING

Explored techniques for handling imbalanced datasets in Machine Learning using a spam message dataset.

The Day 24 project focuses on understanding majority and minority classes and exploring different approaches for addressing class imbalance.

📊 Dataset

The project uses a spam message dataset with the following class distribution:

ham     4825
spam     747

The ham class is the majority class, while spam is the minority class.

Concepts Covered

Imbalanced Dataset

Majority Class

Minority Class

Class Distribution

Class Weight

Undersampling

RandomUnderSampler

Oversampling

SMOTE

Imbalanced-learn

Machine Learning Pipeline

⚖️ Class Imbalance

An imbalanced dataset occurs when one class contains significantly more samples than another class.

Majority Class
      ↓
ham → 4825

Minority Class
      ↓
spam → 747

🔽 Random Under-Sampling

The project explores RandomUnderSampler to reduce the number of samples from the majority class.

from imblearn.under_sampling import RandomUnderSampler

resample = RandomUnderSampler(
    random_state=42,
    sampling_strategy='auto'
)

🔼 SMOTE

The project also explores SMOTE (Synthetic Minority Over-sampling Technique) for increasing the representation of the minority class.

from imblearn.over_sampling import SMOTE

⚙️ Class Weight

The project also studies the use of:

class_weight='balanced'

which can give greater importance to the minority class during model training when supported by the estimator.

🔄 Imbalanced Dataset Workflow

Spam Dataset
      ↓
Check Class Distribution
      ↓
Identify Class Imbalance
      ↓
Choose Imbalance Handling Technique
      ↓
Undersampling / Oversampling / Class Weight
      ↓
Machine Learning Model
      ↓
Model Evaluation

🛠️ Technologies Used

Python

Pandas

Scikit-learn

Imbalanced-learn

Jupyter Notebook

🎯 Learning Outcome

Through this project, I learned how to identify class imbalance and explored different techniques for handling imbalanced datasets, including class weighting, RandomUnderSampler, and SMOTE.

🌲 ISOLATION FOREST

🔹 25 — ISOLATION FOREST — ANOMALY DETECTION

Implemented Isolation Forest for anomaly detection using an unsupervised Machine Learning approach.

The Day 25 project focuses on identifying unusual observations using Isolation Forest and separating predicted anomalies from normal observations.

🌲 Isolation Forest

Isolation Forest is an unsupervised Machine Learning algorithm designed for anomaly detection.

The main idea is that anomalies are easier to isolate than normal observations.

The notebook uses:

```python
from sklearn.ensemble import IsolationForest
```

🔍 Anomaly Prediction

The model generates predictions using:

```python
result = model.fit_predict(df)
```

The prediction values are interpreted as:

```text
-1 → Anomaly
 1 → Normal
```

The notebook separates the observations into anomaly and normal groups based on these predictions.

⚙️ Model Configuration

The notebook uses the following Isolation Forest configuration:

```python
IsolationForest(
    n_estimators=100,
    max_samples=0.8,
    max_features=1.0,
    bootstrap=True,
    n_jobs=1,
    verbose=5,
    random_state=42,
    contamination=0.05
)
```

📌 Key Parameters

- `n_estimators` — Number of trees
- `max_samples` — Number/fraction of samples used for each tree
- `max_features` — Number/fraction of features used
- `bootstrap` — Whether bootstrap samples are used
- `random_state` — Reproducibility
- `contamination` — Expected proportion of anomalies

⚖️ Contamination

The notebook uses:

```python
contamination=0.05
```

This represents an expected anomaly proportion of approximately 5%.

🔄 Isolation Forest Workflow

```text
Dataset
   ↓
Load Data
   ↓
Explore Data
   ↓
Apply Isolation Forest
   ↓
Fit Model
   ↓
Predict Anomalies
   ↓
-1 → Anomaly
 1 → Normal
   ↓
Separate Anomalies and Normal Data
```

🧠 Concepts Covered

- Unsupervised Learning
- Anomaly Detection
- Isolation Forest
- Outlier Detection
- Contamination
- Ensemble Learning
- Anomaly Prediction
- `fit_predict()`

🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

📌 Dataset Note

The notebook was executed using a Credit Card Fraud Detection dataset. The dataset file is not included in this repository.

The notebook expects the dataset to be available locally as:

```text
creditcard.csv
```

🎯 Learning Outcome

Through this project, I learned how Isolation Forest can be used for anomaly detection and how model predictions can be used to separate anomalous observations from normal observations.

🗺️ MY MACHINE LEARNING JOURNEY

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

📈 Multiple Linear Regression

✅ Completed

04

⚙️ StandardScaler

✅ Completed

05

⚙️ MinMaxScaler

✅ Completed

06

🔤 Label Encoding

✅ Completed

07

🔢 One-Hot Encoding

✅ Completed

08

🔢 Ordinal Encoding

✅ Completed

09

🎯 Target Encoding

✅ Completed

10

🔧 Column Transformer

✅ Completed

11

🔧 Column Transformer — Multiple Transformers

✅ Completed

12

🔄 Pipeline + ColumnTransformer + Logistic Regression

✅ Completed

13

🧹 Missing Value Imputation — SimpleImputer

✅ Completed

14

🏦 Logistic Regression — Loan Approval Prediction

✅ Completed

15

📊 Classification Metrics — Loan Data

✅ Completed

16

🏦 Loan Default Risk — Classification Metrics

✅ Completed

17

🌳 Decision Tree — Classification & Regression

✅ Completed

18

🎯 GridSearchCV — Hyperparameter Tuning

✅ Completed

19

👥 K-Nearest Neighbour — Diabetes Classification

✅ Completed

20

⚡ SVM — Binary Classification

✅ Completed

21

🧠 Naive Bayes — Multinomial Text Classification

⭐ Completed

22

🔤 Vectorization — CountVectorizer & TF-IDF Vectorizer

⭐ Completed

23

🎯 K-Means Clustering — Customer Segmentation

⭐ Completed

24

⚖️ Imbalanced Dataset Handling

⭐ Completed

25

🌲 Isolation Forest — Anomaly Detection

⭐ Completed

🧠 KEY LEARNING AREAS

Through these projects, I have gained hands-on experience with:

📌 Regression

Linear Regression

Polynomial Regression

Multiple Linear Regression

Regression Model Evaluation

📌 Classification

Logistic Regression

Decision Tree Classification

K-Nearest Neighbour

Support Vector Machine

Naive Bayes

Binary Classification

Text Classification

Classification Model Evaluation

📌 Data Preprocessing

Standardization

Normalization

Label Encoding

One-Hot Encoding

Ordinal Encoding

Target Encoding

Missing Value Imputation

📌 Feature Transformation

ColumnTransformer

Multiple Transformers

Pipelines

Text Vectorization

CountVectorizer

TF-IDF Vectorizer

N-grams

Stop Words

Text Feature Extraction

TF-IDF Vectorization

📌 Unsupervised Learning

K-Means Clustering

Cluster Analysis

Inertia

Elbow Method

PCA

Cluster Visualization

K-Means Pipeline

📌 Imbalanced Dataset Handling

Imbalanced Dataset

Majority and Minority Classes

Class Weight

Undersampling

RandomUnderSampler

Oversampling

SMOTE

Imbalanced-learn

📌 Anomaly Detection

Isolation Forest

Anomaly Detection

Outlier Detection

Contamination

Unsupervised Learning

Ensemble Learning

📌 Model Selection & Optimization

GridSearchCV

Hyperparameter Tuning

Cross-Validation

Parameter Search

Best Estimator Selection

📌 Model Evaluation

Regression Metrics

R² Score

MAE

MSE

RMSE

Classification Metrics

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Classification Report

🔄 MACHINE LEARNING WORKFLOW

My projects follow a structured Machine Learning workflow:

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
       🎯 Hyperparameter Tuning
                 ↓
           🔮 Predictions
                 ↓
          📊 Model Evaluation
                 ↓
          🔍 Result Analysis

📈 LEARNING PROGRESS

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
          KNN
            ↓
          SVM
            ↓
   Binary Classification
            ↓
      Naive Bayes
            ↓
   Text Classification
            ↓
 Multinomial Naive Bayes
            ↓
     🚀 Continuing...

🎯 CURRENT PROGRESS

⭐ DAY 25 COMPLETED

I have progressed from basic regression algorithms to:

Regression Algorithms

Data Preprocessing

Feature Scaling

Categorical Encoding

Feature Transformation

ColumnTransformer

Pipelines

Logistic Regression

Classification

Classification Metrics

Decision Tree Classification

Decision Tree Regression Workflows

GridSearchCV

Hyperparameter Tuning

Cross-Validation

K-Nearest Neighbour

Support Vector Machine

Binary Classification

Naive Bayes

Multinomial Naive Bayes

Text Classification

Text Vectorization

CountVectorizer

TF-IDF Vectorizer

N-grams

Stop Words

Text Feature Extraction

Unsupervised Learning

K-Means Clustering

Elbow Method

Inertia

PCA

Cluster Visualization

K-Means Pipeline

Imbalanced Dataset Handling

Majority and Minority Classes

Class Weight

RandomUnderSampler

SMOTE

Oversampling and Undersampling

Isolation Forest

Anomaly Detection

Outlier Detection

Contamination

Unsupervised Learning

The goal is to continue building a strong foundation through hands-on implementation rather than only theoretical learning.

🚀 REPOSITORY GOALS

The main goals of this repository are:

Build a strong Machine Learning foundation

Implement concepts using Python

Practice data preprocessing

Understand feature engineering

Understand model evaluation

Learn hyperparameter tuning

Practice cross-validation

Work with practical datasets

Develop Machine Learning problem-solving skills

Maintain a consistent learning record

Build a professional Machine Learning portfolio

📌 WHY THIS REPOSITORY?

This repository represents my continuous Machine Learning learning journey.

Instead of learning algorithms only theoretically, I am implementing each concept through practical notebooks and datasets.

My learning philosophy:

Learn → Implement → Evaluate → Improve → Repeat

🔮 NEXT STEPS

I will continue expanding this repository with new:

Machine Learning Algorithms

Data Preprocessing Techniques

Feature Engineering Methods

Model Evaluation Techniques

Classification Algorithms

Regression Algorithms

Ensemble Learning

Clustering

Dimensionality Reduction

Practical Machine Learning Projects

The goal is to gradually move from Machine Learning fundamentals to more advanced and real-world applications.

👩‍💻 ABOUT ME

I am a Computer Science & Engineering graduate building my skills in:

Python

Machine Learning

Data Science

Artificial Intelligence

I am developing my technical skills through continuous hands-on learning, practical implementation, and project-based learning.

This repository represents my ongoing journey toward becoming a strong Machine Learning / Python professional.

⭐ SUPPORT

If you find this repository useful or interesting, feel free to ⭐ Star the repository!

🚀 LEARNING. BUILDING. IMPROVING.

Day 25 — Isolation Forest — Anomaly Detection completed.

The journey continues... 🤖
