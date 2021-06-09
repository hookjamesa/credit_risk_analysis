# credit_risk_analysis

## Overview

This analysis was conducted to evaluate different ML models against a credit data set: Random Oversampling, SMOTE Oversampling, ClusterCentroids Undersampling, ClusterCentroids-SMOTE combination, Random Forest, and Easy Ensemble.

## Analysis

The results from the ML models were as follows (Model: Balanced Accuracy, Precision, Recall):

* Random Oversampling: 0.5877, 0.99, 0.52
* SMOTE Oversampling: 0.5877, 0.99, 0.57
* ClusterCentroids Undersampling: 0.5000, 0.99, 0.45
* ClusterCentroids-SMOTE combination: 0.4593, 0.99, 0.99
* Random Forest: 0.8030, 0.99, 0.89
* Easy Ensemble: 0.9321, 0.99, 0.92

## Summary

Given the results, for this data set, I recommend the Easy Ensemble ML model. Its high accuracy, precision, and recall gives me good confidence in its ability to work with additional data now that the model has been trained on this data. Additionally, its F1 of 0.95 is strong compared to other models I have seen recently.
