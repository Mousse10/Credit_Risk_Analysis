# Credit_Risk_Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. In this challenge, we apply machine learning to solve a real-world challenge which is credit card risk. We need to employ different techniques to train and evaluate models with unbalanced classes. We use mbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. First, we will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. We will then se a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Followed by a comparison between two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Purpose

The purpose of this analysis is to understand how to utilize Machine Learning statistical algorithms to make predictions based on data patterns provided. Once the models are applied, we need to be able to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results 

### Naive Random Oversampling

![](https://github.com/Mousse10/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.PNG)

- Balanced accuracy score: 62.49%
- Precision score: 99%
- Recall score: 65%

### SMOTE Oversampling

![](https://github.com/Mousse10/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.PNG)

- Balanced accuracy score: 65.12%
- Precision score: 99%
- Recall score: 66%

### Undersampling

![](https://github.com/Mousse10/Credit_Risk_Analysis/blob/main/Resources/Undersampling.PNG)

- Balanced accuracy score: 51.03%
- Precision score:
- Recall score:

### Combination Under-Over Sampling

![](https://github.com/Mousse10/Credit_Risk_Analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling.PNG)

- Balanced accuracy score: 51.03%
- Precision score: 99%
- Recall score: 44%

### Balanced Random Forest Classifier

![](https://github.com/Mousse10/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.PNG)

- Balanced accuracy score: 79.52%
- Precision score: 99%
- Recall score: 88%

### Easy Ensemble AdaBoost Classifier

![](https://github.com/Mousse10/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier%202.PNG)

- Balanced accuracy score: 92.63%
- Precision score: 99%
- Recall score: 94%

## Summary

Upon further review and comparing the different results, we clearly see better results from the ensemble classifier methods to try and predict which loans are high or low risk. Out of all the models, the one with the best results is the Easy Ensemble Adaboost Classifier as it scored over 90% in all three major scores. 
