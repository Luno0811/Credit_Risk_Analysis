# Credit_Risk_Analysis

# Overview of the Analysis

The purpose of this analysis is to use different machine learning methods to train a model on identifying credit card risk. Some of the methods we plan to use include oversampling and undersampling with SMOTE and SMOTEEN, and also Forest Calssifiers and Ensemble Classifiers to reduce bias. Afterwards, we will evaluate the data and make recommendations on if this model is fit for use.

# Results 

Naive Oversampling 
- Balanced Accuracy score was 0.64
- Precision score was 0.99
- Recall score was 0.68

SMOTE Oversampling 
- Balanced Accuracy score was 0.63
- Precision score was 0.99
- Recall score was 0.68

Undersampling 
- Balanced Accuracy score was 0.63
- Precision score was 0.99
- Recall score was 0.45

Combination Sampling
- Balanced Accuracy score was 0.62
- Precision score was 0.99
- Recall score was 0.67

Balanced Forest
- Balanced Accuracy score was 0.99
- Precision score was 1.00
- Recall score was 1.00

# Summary

Many of the over or undersampling methods were very similar in accuracy, but the Balanced Forest ensemble method was much more accurate, and is our recommendation for the model to use moving forward.