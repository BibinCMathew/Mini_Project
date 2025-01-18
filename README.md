Breast Cancer Classification
Overview
This project implements several supervised learning algorithms to classify breast cancer data into malignant or benign categories. The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset from the sklearn library. The aim is to compare the performance of different classification algorithms on the dataset.

Dataset
The dataset contains 30 features describing characteristics of cell nuclei present in breast cancer biopsies, such as radius, texture, smoothness, compactness, and concavity. The target variable is binary:

0: Benign
1: Malignant
This dataset is loaded from the sklearn.datasets.load_breast_cancer() function.

Algorithms Implemented
The following classification algorithms are implemented in this project:

Logistic Regression – A linear model used for binary classification.
Decision Tree Classifier – A tree-based model that makes decisions based on feature values.
Random Forest Classifier – An ensemble method that combines multiple decision trees.
Support Vector Machine (SVM) – A model that tries to find the hyperplane that best separates the classes.
k-Nearest Neighbors (k-NN) – A non-parametric method that classifies based on the nearest data points.
Preprocessing Steps
Missing Values: The dataset does not contain any missing values, so this step was skipped in this case.
Feature Scaling: Standard scaling was applied to the features to ensure each feature contributes equally to the model, especially for algorithms sensitive to distance (SVM and k-NN).
Model Evaluation
Each model is evaluated using accuracy, confusion matrix, precision, recall, and F1-score. A comparison is made to determine which algorithm performs the best for this dataset.

Requirements
To run the project, you need the following Python libraries:

scikit-learn
numpy
pandas
matplotlib
seaborn
