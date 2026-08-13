📅 Day 12 – Pipeline with ColumnTransformer & Logistic Regression
📖 Overview

This project demonstrates how to build a Machine Learning preprocessing and model pipeline using Scikit-learn.

The project combines ColumnTransformer with multiple preprocessing techniques and a LogisticRegression model.

🔧 Preprocessing Techniques

Different preprocessing techniques are applied to different columns:

MinMaxScaler → salary
TargetEncoder → city
OrdinalEncoder → education
Passthrough → remaining columns

The notebook uses ColumnTransformer to combine these transformations.

🤖 Machine Learning Model
Logistic Regression

The preprocessing steps and Logistic Regression model are combined using Scikit-learn's Pipeline.

📚 Concepts Learned
Train-Test Split
ColumnTransformer
MinMaxScaler
TargetEncoder
OrdinalEncoder
Pipeline
Logistic Regression
Accuracy Score
Confusion Matrix
Classification Report
🎯 Learning Outcome

Through this project, I learned how to combine multiple preprocessing techniques and a Machine Learning model into a single pipeline.

This approach helps organize preprocessing and model training into a structured workflow.