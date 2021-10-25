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

![ros](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/ros.png)

- The Balanced Accuracy Score is: 65%
- There is a huge difference in precision between High and Low-risk, this also affects the f1 score
- The Recall (sensitivity) between high and low are similar in the 60% range


### Oversampling - SMOTE

![smote](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/smote.png)

The Balanced Accuracy Score is:  

### Undersampling - ClusterCentroids

![cluster](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/cluster.png)

The Balanced Accuracy Score is:


### Combination (over & under) Sampling - SMOTEENN

![smoteenn](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/smoteenn.png)

The Balanced Accuracy Score is:

### Ensemble - BalancedRandomForestClassifier

![balance](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/balance.png)

The Balanced Accuracy Score is:

### Ensemble - EasyEnsembleClassifier

![easy](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/easy.png)

The Balanced Accuracy Score is:

## Summary

- All summaries for each mmodel are listed above
- We recommend.....
