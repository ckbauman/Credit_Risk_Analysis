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
- The Recall (sensitivity) between high and low are similar at 69% and 60%


### Oversampling - SMOTE

![smote](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/smote.png)

- The Balanced Accuracy Score is:  66%
- There is also a huge difference in precision between High and Low-risk, this affects the f1 score as well
- The Recall (sensitivity) between high and low are a little more similar at 63% and 69%

### Undersampling - ClusterCentroids

![cluster](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/cluster.png)

- The Balanced Accuracy Score is: 54%
- There is also a huge difference in precision between High and low-risk, this affects the f1 score as well
- The Recall (sensitivity) between high and low are worsening at 69% and 40%


### Combination (over & under) Sampling - SMOTEENN

![smoteenn](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/smoteenn.png)

- The Balanced Accuracy Score is: 64%
- There is also a huge difference in precision between high and low-risk, this affects the f1 score as well
- The Recall (sensitivity) beween high and low are also worsening at 72% and 57%, butt this has been the highest rate for high-risk so far

### Ensemble - BalancedRandomForestClassifier

![balance](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/balance.png)

- The Balanced Accuracy Score is: 79%
- There is also a huge difference in precision between high and low-risk, but high-risk went up a big to 3%
- The Recall (sensitivity) between high and low are stil far apart at 70% and 87%, but are highest values we've seen so far

### Ensemble - EasyEnsembleClassifier

![easy](https://github.com/ckbauman/Credit_Risk_Analysis/blob/main/Images/easy.png)

- The Balanced Accuracy Score is: 93%   HIGHEST
- There is also a huge difference in precision between high and low-risk, but the high-risk precision is at HIGHEST at 9%
- The Recall (sensitivity) between high and low are very close at 92% and 94% and are also the HIGHEST overall

## Summary

- All summaries for each mmodel are listed above
- We recommend.....
