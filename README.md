Fraud Detection Using Machine Learning
This project implements a fraud detection system using various machine learning algorithms to classify transactions as either fraudulent or normal.

Overview
The dataset used includes a binary Class feature, where:

0 = Normal transaction
1 = Fraudulent transaction
The goal is to build, evaluate, and compare different machine learning models to accurately detect fraudulent activities.

Project Workflow
Data Preprocessing:

Data exploration and cleaning.
Handling class imbalance and scaling features.
Converting the binary Class feature into categories ("Normal" and "Fraud").
Exploratory Data Analysis (EDA):

Visualizing the distribution of transaction classes.
Exploring feature correlations and distributions.
Models Implemented:

Naive Bayes: A simple, probabilistic classifier that assumes feature independence.
Decision Tree: A tree-based model that splits data into subsets based on feature values.
Logistic Regression: A binary classification model that estimates the probability of a transaction being fraudulent.
Model Evaluation:

Performance is evaluated using accuracy, precision, recall, F1-score, and confusion matrix.
Models are compared to identify the best-performing algorithm for fraud detection.
