# -Train-Test-Split-Evaluation-MetricsAI & ML Internship – Task 5
 Task Objective

The objective of this task is to understand:

Why datasets are split into training and testing sets

How to train a classification model

How to evaluate a model using standard performance metrics

 Dataset

Heart Disease Dataset

The dataset contains medical attributes such as age, cholesterol, blood pressure, etc.

The target variable indicates whether a patient has heart disease or not.
Tools & Libraries Used

Python

Pandas

Scikit-learn

Jupyter Notebook
 Steps Performed
1️ Data Loading

Loaded the heart disease dataset using Pandas.

2️ Feature & Target Separation

Independent variables (X): All columns except the target

Dependent variable (y): Heart disease indicator

3️ Train-Test Split

Dataset split into:

80% Training data

20% Testing data

This helps evaluate model performance on unseen data.

4️ Model Training

Trained a Logistic Regression model using training data.

5️ Prediction

Predicted results on the test dataset.

6️ Model Evaluation

The following metrics were calculated:

Accuracy – Overall correctness of the model

Precision – How many predicted positives are actually positive

Recall – How many actual positives are correctly identified

Confusion Matrix – Summary of correct and incorrect predictions

Evaluation Metrics Explained
 Accuracy

Measures how often the model predicts correctly.

 Precision

Indicates how reliable positive predictions are.

 Recall

Shows how well the model detects actual heart disease cases (important in healthcare).

 Confusion Matrix

Displays:

True Positives

True Negatives

False Positives

False Negatives
