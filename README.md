# credit-risk-classification

## Overview of the Analysis

- **Purpose of the Analysis**: The purpose of this analysis is to assess the performance of a machine learning model in predicting loan statuses based on financial data.
- **Financial Information**: The dataset contains financial information related to loans, and the task is to predict whether a loan is healthy (label 0) or has a high risk of defaulting (label 1).
- **Variable Information**: The "loan_status" variable contains two classes: 0 for healthy loans and 1 for high-risk loans. Other variables include loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.
- **Machine Learning Process**: The analysis involves several stages of the machine learning process, including data preprocessing, model training using Logistic Regression, evaluation, and performance metrics assessment.

## Results

Using the provided confusion matrix and classification report, let's analyze the performance of the machine learning model (Logistic Regression):

- **Confusion Matrix**:
  - True Positives (TP): 563
  - True Negatives (TN): 18663
  - False Positives (FP): 102
  - False Negatives (FN): 56

- **Classification Report**:
  - Precision for Label 0 (Healthy Loans): 1.00
  - Precision for Label 1 (High-Risk Loans): 0.85
  - Recall for Label 0 (Healthy Loans): 0.99
  - Recall for Label 1 (High-Risk Loans): 0.91
  - Weighted Average F1-score: 0.99
  - Accuracy: 99%

## Summary

- The Logistic Regression model demonstrates excellent performance in classifying both healthy (label 0) and high-risk (label 1) loans.
- With a weighted average F1-score of 0.99 and an accuracy of 99%, the model's predictions are highly accurate.
- Precision for healthy loans (label 0) is perfect at 1.00, ensuring that when the model predicts a loan as healthy, it is always correct. Precision for high-risk loans (label 1) is 0.85, indicating a strong ability to identify high-risk loans.
- Recall for healthy loans (label 0) is 0.99, meaning that the model correctly captures most of the healthy loans. For high-risk loans (label 1), the recall is 0.91, indicating the model's effectiveness in identifying a significant portion of high-risk loans.
- The weighted average F1-score of 0.99 highlights the model's excellent balance between precision and recall.

## Recommendation

The **Logistic Regression model** is recommended for use by the company. It performs exceptionally well in correctly classifying both healthy and high-risk loans, with high accuracy and a strong balance between precision and recall. The model's ability to identify high-risk loans is particularly valuable for risk assessment in the lending business.
