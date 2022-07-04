# Credit_Risk_Analysis

## Overview of the Analysis

The purpose of this analysis is to predict credit risk for loan appicants. I am using using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 

I am using a combinatorial approach of over- and undersampling using the SMOTEENN algorithm, and comparing two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


## Results

### Naive Random Oversampling

RandomOverSampler Model randomly selects from the minority class and adds it to the training set until both classifications are equal. 

![image](https://user-images.githubusercontent.com/97486216/177077704-3f249afc-4aad-492a-9d71-d888d36df77d.png)

### SMOTE Oversampling

SMOTE increases the size of the minority class by creating new values based on the value of the closest neighbors to the minority class instead of random selection.

![image](https://user-images.githubusercontent.com/97486216/177077853-7b977d1a-eb94-4b74-badc-1c475d1b5150.png)

### Undersampling

ClusterCentroids Model, an algorithm that identifies clusters of the majority class to generate synthetic data points that are representative of the clusters.

![image](https://user-images.githubusercontent.com/97486216/177077959-3e04c3d6-d5c8-40b4-8f74-002dfd949630.png)

### Combination (Over and Under) Sampling

SMOTEENN (Synthetic Minority Oversampling Technique + Edited NearestNeighbors) Model combines aspects of both oversampling and undersampling. 

![image](https://user-images.githubusercontent.com/97486216/177078081-2eb1b070-72b8-4123-ba28-55ea37f11c71.png)

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

Compare two new Machine Learning models that reduce bias to predict credit risk.

BalancedRandomForestClassifier Model, two trees of the same size and equal size to the minority class are constructed to represent one for the majority class and one for the minority class.

## Summary

