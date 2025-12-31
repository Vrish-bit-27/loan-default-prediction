# Loan Default Prediction (German Credit Dataset)

## Objective
Predict whether a borrower will default on a loan so that banks can reduce financial risk and make safer lending decisions.

## Dataset
German Credit Risk Dataset  
1000 rows · 24 features + 1 target label

Target meaning:
- 0 = repaid loan
- 1 = defaulted loan

## Model Used
Logistic Regression  
Chosen because it is:
- simple
- explainable
- widely used in banking risk models

## Steps Performed
1. Loaded dataset in Google Colab
2. Converted target column so 1 = default
3. Performed basic EDA
4. Split data (90% training / 10% testing)
5. Trained Logistic Regression model
6. Evaluated accuracy, precision, recall, F1-score
7. Saved trained model file

## Responsible AI Notes
- avoid unfair bias  
- ensure data privacy  
- model should be explainable  

## Result
The model successfully predicts loan default risk and demonstrates how ML can support lending risk management in banking.
