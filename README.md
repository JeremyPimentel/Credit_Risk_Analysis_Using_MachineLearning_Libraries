# Credit_Risk_Analysis_Using_MachineLearning_Libraries

## Overview of Analysis
The purpose of this analysis was to train a supervised machine learning library to train, split and predict credit risk factors. 

## Results

Naive Oversampling: 

Balanced Accuracy Score = 64.86%
Precision high_risk = 0.01
Precision low_risk = 1.00 
recall high_risk = 0.65
recall low_risk = 0.64

SMOTE Oversampling:

Balanced Accuracy Score = 64.86%
Precision high_risk = 0.01
Precision low_risk = 1.00 
recall high_risk = 0.65
recall low_risk = 0.64

Undersampling: 

Balanced Accuracy Score = 64.86%
Precision high_risk = 0.01
Precision low_risk = 1.00 
recall high_risk = 0.65
recall low_risk = 0.64

Combination Sampling:
Balanced Accuracy Score = 64.86%
Precision high_risk = 0.01
Precision low_risk = 1.00 
recall high_risk = 0.65
recall low_risk = 0.64

Balanced Random Forest Classifier:
Balanced Accuracy Score = 99.95%
Precision high_risk = 0.84
Precision low_risk = 1.00 
recall high_risk = 1.00
recall low_risk = 1.00

Easy Ensemble Classifier:
Balanced Accuracy Score = 100%
Precision high_risk = 0.84
Precision low_risk = 1.00 
recall high_risk = 1.00
recall low_risk = 1.00

- The Balanced Accuracy Scores, Precision Scores and Recall Scores for the oversampling, undersampling and combined models were all calculated to be the same values as shown above. This could be because the dataset is such that even with rebalancing we get the same results. 
- However, the scores changed with the Balanced Random Forest and Easy Ensemble Classifier. The Balanced Accuracy scores changed from 64.86% to 99.95% and 100% respectively and the Precision and recall scores changed from 0.01/1.00 and 0.65/0.64 for high and low risk to 0.84/1.00 and 1.00/1.00. 

### Summary 

In conclusion, the results of the over and undersamlping and combined sampling methods yeilded the same results where as the balanced and ensemble models gave results with much higher accuracy scores. 

Given these results it is reccommended to use either the Balanced Random Forest Classifier or the Easy Ensemble Classifier models for this Credit Risk analysis based on the higher accuracy scores achieved. 
