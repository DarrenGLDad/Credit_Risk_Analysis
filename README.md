# Credit_Risk_Analysis

## Overview of the analysis: 
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Here different techniques will be employed to train and evaluate models with unbalanced classes. Here there will be utilization imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company,

## Results & Summary: : 

- I oversampled the data using RandomOverSampler and SMOTE algorithms

- Undersampled the data using the ClusterCentroids algorithm.

- I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

 To complete the analysis I evaluated the performance of these models and made a reccomendation on whether these models should be used to predict credit risk.
