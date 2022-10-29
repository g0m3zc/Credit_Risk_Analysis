# Credit_Risk_Analysis

## Overview of Analysis
The purpose of this analysis is to review credit risk using various supervised machine learning models.  When comparing risky to non-risky loans, there is an unbalanced amount of each.  This will allow us to compare differences between the various models.

## Results

### Resampling
1. Oversampling
- Naive Random Oversampling resulted in an accuracy score of .64.

2. SMOTEENN Algorithm
- Oversampling resulted in an acuracy score of .64

3. Undersampling
-Cluster Centroids algorith resulted in an acuracy score of .59

4. Combination Over and Under sampling using SMOTEEN resulted in an acuracy 
score of 64%

### Ensemple Classifiers

1. BRFC
- Balanced Random Forest Classifier resulted in an accuracy score of .73

2. Easy Ensemble AdaBoost Classifier resulted in an accuracy score of .74 

## Summary

Based on the results, I would recommend a model that has a better F1 score.  The Easy Ensemble AdaBoost Classifier had an F1 of .92 



