# Credit-Card-Fraud-Detection
A comprehensive solution for detecting fraudulent credit card transactions using machine learning techniques. The goal is to create a robust and accurate model that can distinguish between legitimate and fraudulent transactions.

This repository contains a solution for detecting fraudulent credit card transactions using various machine learning models. The project involves data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

Technologies and Libraries Used:
Programming Language
Python: The primary language used for scripting and implementing the machine learning models.
Libraries
Pandas: Used for data manipulation and analysis. It provides data structures like DataFrame for handling tabular data.
NumPy: Utilized for numerical operations, providing support for large, multi-dimensional arrays and matrices.
Scikit-learn: A machine learning library used for model building and evaluation. Key functionalities include:
train_test_split: For splitting the dataset into training and testing sets.
StandardScaler: For feature scaling.
LogisticRegression: For implementing logistic regression model.
RandomForestClassifier: For implementing random forest classifier.
classification_report, roc_curve, auc, precision_recall_curve: For evaluating model performance.
Joblib: Used for parallel processing to speed up model training and evaluation.
Plotly: A graphing library used to create interactive visualizations, including:
plotly.express and plotly.graph_objects: For creating histograms, ROC curves, and Precision-Recall curves.
