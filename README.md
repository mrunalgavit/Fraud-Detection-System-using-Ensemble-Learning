# Fraud-Detection-System-using-Ensemble-Learning
# Credit Card Fraud Detection

This repository contains a machine learning project focused on detecting fraudulent credit card transactions. The objective was to develop and evaluate multiple classification models capable of identifying rare fraudulent activity within a highly imbalanced dataset.

## Project Overview

Credit card fraud poses a significant threat to financial institutions and consumers. This project addresses the challenge of detecting fraud in real-time using supervised learning algorithms. The dataset used is a standard benchmark dataset obtained from Kaggle, consisting of anonymized credit card transactions.

## Dataset Description

- Source: Kaggle (European credit cardholders dataset)
- Total records: 284,807 transactions
- Fraudulent transactions: 492 (approx. 0.17%)
- Features: 30 columns including PCA-transformed variables (V1–V28), Time, Amount, and Class (target)

Due to the high class imbalance, evaluation metrics were selected carefully to emphasize fraud detection effectiveness over overall accuracy.

## Algorithms Implemented

1. **Logistic Regression**: Used as a baseline binary classifier.
2. **AdaBoost Classifier**: Applied to improve classification by focusing on previously misclassified samples.
3. **XGBoost Classifier**: Utilized for its efficiency and accuracy in handling imbalanced classification problems.

## Methodology

- Performed exploratory data analysis to understand feature distributions and correlations.
- Applied feature scaling and class imbalance handling techniques.
- Trained and evaluated models using stratified cross-validation.
- Used metrics such as Precision, Recall, and F1-score due to the dataset imbalance.

## Evaluation Metrics

| Model            | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Logistic Regression | ~99.9%   | 91%       | 78%    | 84%      |
| AdaBoost            | ~99.93%  | 84%       | 73%    | 78%      |
| XGBoost             | ~99.96%  | 95%       | 79%    | 86%      |






