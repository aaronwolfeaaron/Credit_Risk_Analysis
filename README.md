# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to identify the risk involved in credit loans using various methods of machine learning.

## Results
### Naive Random Oversampling
![](https://github.com/aaronwolfeaaron/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-06%20at%203.38.17%20PM.png)
- Balanced accuracy score: 64.7%
- Precision score: 99%
- Recall score: 60%

### SMOTE Oversampling
![](https://github.com/aaronwolfeaaron/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-06%20at%203.38.49%20PM.png)
- Balanced accuracy score: 65.3%
- Precision score: 99%
- Recall score: 68%

### Undersampling
![](https://github.com/aaronwolfeaaron/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-06%20at%203.38.57%20PM.png)
- Balanced accuracy score: 65.3%
- Precision score: 99%
- Recall score: 40% 

### Combination Under-Over Sampling
![](https://github.com/aaronwolfeaaron/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-06%20at%203.39.04%20PM.png)
- Balanced accuracy score: 54.4%
- Precision score: 99%
- Recall score: 57%

### Balanced Random Forest Classifier
![](https://github.com/aaronwolfeaaron/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-06%20at%203.39.29%20PM.png)
- Balanced accuracy score: 78.8%
- Precision score: 99%
- Recall score: 91%

### Easy Ensemble AdaBoost Classifier
![](https://github.com/aaronwolfeaaron/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-06%20at%203.39.35%20PM.png)
- Balanced accuracy score: 92.5%
- Precision score: 99%
- Recall score: 94%

## Summary:
None of the models used for this credit risk analysis were as robust as hoped, though the Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier were much more precise than the other four. Both of the aforementioned had recall scores over 90%, as well as precision scores over 90%, meaning that they were strong in predicting high-risk loans, at lease comparatively. For this reason, I would recommend either of the ensemble methods for detecting high-risk lending. 
