# Credit Card Marketing Models

## Overview
This analysis focuses on the development and assessment of three predictive models—logistic regression, Generalized Additive Model (GAM), and Neural Network—for targeted advertising in a credit card marketing campaign. The analysis utilizes the `CreditCard_Ads.csv` dataset.

## Author
Vincent Bianchi

## Date
2023-12-13

## Description
This statistical analysis aims to predict the success of a credit card marketing campaign using various modeling approaches. Three primary models are explored:

1. **Logistic Regression Model:** This model is built with a set of predictor variables, including Age, Default, Housing, Loan, Contact, Previous, Poutcome, EVR, CPI, and CCI. The model is trained on a subset of the data and then evaluated.

2. **Generalized Additive Model (GAM):** The GAM model includes smooth functions for continuous variables (Age, Previous, EVR, CPI, CCI) and linear terms for categorical variables (Default, Housing, Loan, Contact, Poutcome). The model is visualized for better interpretation.

3. **Neural Network Model:** A Neural Network with one hidden layer and four hidden units is implemented. The model is trained using standardized input variables derived from the training dataset and then evaluated on a separate test dataset.

## Data Preparation
The dataset is divided into training and test sets, with a 60/40 split. This ensures that the models are trained on a subset of the data and tested on unseen data.

## Model Evaluation
The performance of each model is evaluated using confusion matrices. The logistic regression model undergoes backward selection, leading to the removal of Housing, Loan, Age, and Default variables.

## Lift Chart
A lift chart is generated to compare the prediction performance of the four models—logistic regression, backward-selected logistic regression, GAM, and Neural Network. The lift chart provides insights into the relative effectiveness of these models in predicting positive outcomes in the credit card marketing campaign.

This lab provides a comprehensive analysis of different models, offering insights into their strengths and weaknesses in the context of targeted advertising for a credit card marketing campaign.
