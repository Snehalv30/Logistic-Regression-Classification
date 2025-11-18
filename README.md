# Task 4 — Classification Using Logistic Regression

This task demonstrates how to build a binary classification model using Logistic Regression in Python. The objective is to understand logistic regression, train a classifier, evaluate its performance, and visualize important metrics.

# Objective

Build a binary classifier using Logistic Regression

Split dataset into training & testing sets

Standardize the feature values

Train logistic regression model

Evaluate using:

Confusion Matrix

Accuracy

Precision

Recall

F1 Score

ROC Curve & AUC

Understand the Sigmoid function & decision threshold

# Tools & Libraries Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn (optional for better plots)

# Dataset

Any binary classification dataset may be used, such as:

Breast Cancer dataset (from scikit-learn)

Custom CSV with a binary target (0/1)

Example Target → 0 = negative, 1 = positive

# Steps Performed
## 1. Import Libraries & Load Dataset

Load dataset using Pandas or sklearn built-in dataset

Display basic info and target distribution

## 2. Preprocessing

Select features (X) and target (y)

Train/Test Split (80% train, 20% test)

Standardize using StandardScaler

## 3. Train Logistic Regression Model

Fit model on training data

Predict labels & prediction probabilities

## 4. Model Evaluation

Metrics used:

| Metric               | Meaning                                          |
| -------------------- | ------------------------------------------------ |
| **Confusion Matrix** | Classification summary                           |
| **Precision**        | Out of predicted positives, how many are correct |
| **Recall**           | Out of actual positives, how many were detected  |
| **F1 Score**         | Balanced precision & recall                      |
| **ROC Curve**        | Relationship between TPR & FPR                   |
| **AUC Score**        | Area under curve (higher = better)               |

## 5. Decision Threshold Tuning

Explain sigmoid output (0–1)

Show how varying threshold changes accuracy & recall

# Visualization

Confusion matrix heatmap

ROC Curve

Sigmoid function example plot

# Install Dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# How to Run the Code
python logistic_regression_task4.py


OR run code cell-by-cell in Jupyter Notebook.

# Output Includes

Trained Logistic Regression Model

Evaluation metrics

Confusion matrix

ROC-AUC graph

Threshold analysis
