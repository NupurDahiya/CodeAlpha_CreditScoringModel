# Credit Scoring Model

## Overview
A machine learning project that predicts credit risk using the German Credit dataset. It compares multiple classification algorithms and evaluates their performance using standard classification metrics.

## Objectives
- Analyze financial and applicant data.
- Perform data preprocessing and feature analysis.
- Train and compare classification models.
- Evaluate predictions using precision, recall, F1-score, accuracy, and ROC-AUC.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib

## Machine Learning Models
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Evaluation
The models are compared using accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices, and threshold analysis. Random Forest achieved a ROC-AUC of approximately 0.790 in the current test run.

## Feature Analysis
Permutation importance was used to identify features that most influenced model performance, including checking status, duration, and savings status.

## Dataset
The project uses the German Credit dataset from OpenML (`credit-g`), containing 1,000 records and 20 input features.

## Limitations
This is an educational project based on a small, historical dataset. Its predictions may not generalize to current applicants. It is not intended for real lending decisions.

## Author
Add your name here.

## Internship
Machine Learning Internship — CodeAlpha