# Credit Card Loan Default Predictor

Project in course DS340 (Machine Learning Course) that focuses on machine learning and data cleaning techniques, using data from a kaggle dataset linked in "DS 340 Final Paper".

This project was created with one other partner from the course.

## Problem

Can a customer's financial profile as well as repayment information accurately predict whether or not they default on their next credit card payment?

This project explores a problem relevant to credit-risk analysts: identifying potential defaults while managing false alarms. We compare multiple models and examine how synthetic oversampling changes the tradeoff between precision and recall.

Developed by Melaku Mohammed and Christian Abrams for DS340.

## Data

Source: Default of Credit Card Clients dataset on Kaggle

- Records: 30,000 credit card customers in Taiwan.

- Target: default.payment.next.month, where 1 indicates default and 0 indicates no default.

- Class distribution: 22.12% default and 77.88% non-default.

- Features: Credit limits, demographic attributes, and six months of repayment status, bill amounts, and payment amounts.

- Identifier: Customer ID is excluded from the classical modeling notebook’s predictors.

The historical data includes repayment information from April–September 2005. Findings may not generalize to current customers or other markets. Class imbalance also makes accuracy alone an insufficient measure of performance.

## Approach, Results, and Interpretation

All explored in detail through the DS 340 Final Paper.pdf

## My Contribution

This was a two-person project and I contributed the predictive models created (SMOTE + non-SMOTE), the neural network, and a minor contribution to the initial EDA.

## Reproduction

The classical modeling notebook downloads the dataset using the library kagglehub (See example in DS340_EDA.ipynb): uciml/default-of-credit-card-clients-dataset

**Project files**

DS340_EDA.ipynb --> Exploratory data analysis

DS340_models.ipynb --> Classical model comparisons without SMOTE

DS340_models_SMOTE.ipynb --> Classical model comparisons with SMOTE

DS340_nn.ipynb --> Neural network experiment

DS 340 Final Paper.pdf --> Full project report

DS 340 Final Presentation.pptx.pdf --> Presentation
