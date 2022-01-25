# Credit_Risk_Analysis

## Overview 

This  assignment consists of three technical analysis deliverables:

- Resampling Models to Predict Credit Risk
- SMOTEENN Algorithm to Predict Credit Risk
- Ensemble Classifiers to Predict Credit Risk

## Resources:

Data Source: LoanStats_2019Q1.csv
Software: Python 3.7.9, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results

### RandomOverSampler model

Accuracy Score: 67.4%

Precision High Risk: 1%

Precision Low Risk: 100%

Recall High Risk: 72%

Recall Low Risk: 63%

### SMOTE Oversampling

Accuracy Score: 66.2%

Precision High Risk: 1%

Precision Low Risk: 100%

Recall High Risk: 66%

Recall Low Risk: 66%

### Undersampling

Accuracy Score: 51.3%

Precision High Risk: 0%

Precision Low Risk: 100%

Recall High Risk: 61%

Recall Low Risk: 42%

### Combination (Over and Under) Sampling

Accuracy Score: 61.5%

Precision High Risk: 1%

Precision Low Risk: 100%

Recall High Risk: 54%

Recall Low Risk: 54%

### Balanced Random Forest Classifier

Accuracy Score: 78.7%

Precision High Risk: 4%

Precision Low Risk: 100%

Recall High Risk: 91%

Recall Low Risk: 91%

### Easy Ensemble AdaBoost Classifier

Accuracy Score: 92.5%

Precision High Risk: 7%

Precision Low Risk: 100%

Recall High Risk: 99%

Recall Low Risk: 94%


## Summary

All the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high.
The Ensemble models brought a lot more improvment specially on the sensitivity of the high risk credits.
The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. On another hand, with a low precision, a lot of low risk credits are still falsely detected as high risk which would penalize the bank's credit strategy and infer on its revenue by missing those business opportunities.
For those reasons I would not recommend the bank to use any of these models to predict credit risk.
