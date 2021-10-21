# Credit_Risk_Analysis
Module 17

## Overview
We are determining Credit Card Risk.  Our dataset comes from LendingClub and we know that we have an unbalanced classification problem where good loans outnumber risky loans.  We will be using Machine Learning to determine which models best predict credit risk.

## Results

Our Credit Card Risk analysis used 2 primary libraries:
- imbalanced-learn
- scikit-learn

We used 6 different learning models throughout our analysis. They include:
- Oversampling - RandomOverSampler
- Oversampling - SMOTE
- Undersampling - ClusterCentroids
- Combiniation (over & under) Sampling - SMOTEENN
- Ensemble - BalancedRandomForestClassifier
- Ensemble - EasyEnsembleClassifier

### Oversampling - RandomOverSampler

INSERT: ros image

The Balanced Accuracy Score is: 65%
The precision for high_risk and low_risk are extremely different, which also throws off the F1 score for the two.


### Oversampling - SMOTE

INSERT: smote image

The Balanced Accuracy Score is:  

### Undersampling - ClusterCentroids

INSERT: cluster image

The Balanced Accuracy Score is:


### Combination (over & under) Sampling - SMOTEENN

INSERT: smoteenn image

The Balanced Accuracy Score is:

### Ensemble - BalancedRandomForestClassifier

INSERT: balance image

The Balanced Accuracy Score is:

### Ensemble - EasyEnsembleClassifier

INSERT: easy image

The Balanced Accuracy Score is:

## Summary

- All summaries for each mmodel are listed above
- We recommend.....