Credit Card Default Prediction Analysis
This repository contains an exploratory analysis and model training for predicting credit card default using a comprehensive dataset. The analysis includes data preprocessing, feature engineering, model training, evaluation, and comparison of different machine learning models.

Overview
The credit card default dataset aims to predict whether a customer will default on their credit card payment based on various demographic and financial features. The dataset includes information such as credit limit, gender, education level, marital status, age, repayment status, bill statement amounts, previous payments, and the target variable indicating default status.

Analysis Highlights

Data Understanding and Preprocessing:
Overview of the dataset and its features.
Handling missing values using mean and mode imputation.
Creating new features and encoding categorical variables.

Data Imputation and Feature Engineering:
Mapping and encoding features to create dummy variables.
Standardizing the data to mean zero and variance one.

Model Training and Evaluation:
Splitting the data into training and testing sets.
Training a Support Vector Classifier (SVC) using the full set of standardized features.
Applying Principal Component Analysis (PCA) to extract linear principal components.
Training and evaluating SVC on principal components.

Model Evaluation and Comparison:
Comparing the performance of SVC trained on standardized features versus principal components.
Analyzing the suitability of the two classifiers for predicting credit card defaults.

Key Findings

Support Vector Classifier on Standardized Data:
Achieved a training accuracy of approximately 0.823 and a test accuracy of approximately 0.814.
Demonstrated good generalization from training data to unseen data.

Support Vector Classifier on Principal Components:
Achieved a slightly lower training accuracy of approximately 0.802 and a test accuracy of approximately 0.804.
Indicates some loss of valuable information during dimensionality reduction.

Comparison:
The SVC with standard features outperformed the SVC with principal components by a small margin.
The standard features model preserved the interpretability of the original features, whereas the PCA model sacrificed some interpretability.

Credits
This analysis is based on the credit card default dataset, which is publicly available for educational and research purposes.

License
The dataset used in this analysis may have its own licensing. Please refer to the original dataset source for licensing information.