# Module 20 Report `credit-risk-classification`

## Overview of the Analysis

In this analysis, I develop a logistric regression model to predict loan default risk based on historical data. The hypothetical purpose is to assist financial institutions in managing their lending portfolios more effectively by accurately identifying high-risk loans.

The dataset contained financial information on loans, including features such as loan amount, interest rate, credit score, and employment length. The target variable was the loan status, categorized as either 0 for healthy loans or 1 for high-risk loans.

I begin by exploring the dataset, examining the distribution of the target variable using value_counts. There are no nulls in the dataset. I then proceed with the machine learning process, which involved data splitting, model selection (just LR), training, and evaluation.

I use only logistic regression as it is well-suited for binary classification tasks.

## Results

* Logistic Regression Model:
    * Accuracy Score: 0.99
    * Precision Score (High-Risk Loans): 0.86
    * Recall Score (High-Risk Loans): 0.94

## Summary

The logistic regression model performed exceptionally well in predicting both healthy and high-risk loans. It achieved an accuracy score of 0.99, indicating high overall performance. For high-risk loans, the model demonstrated a precision score of 0.86, meaning that when it classified a loan as high-risk, it was correct approximately 86% of the time. Moreover, with a recall score of 0.94, the model effectively captured the majority of actual high-risk loans.

Based on these results, I recommend deploying the logistic regression model for predicting loan default risk. Its high accuracy, precision, and recall make it a valuable tool for financial institutions to identify and manage high-risk loans effectively.

The performance of the model is important, especially in the context of the problem we are trying to solve.