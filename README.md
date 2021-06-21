# Credit_Risk_Analysis

## Overview

In this challenge, I will apply apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I will need to employ different techniques to train and evaluate models with unbalanced classes. Jill asked me to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the clusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier
 And EasyEnsembleClassifier, to predict credit risk. 

## Results 

### Naïve Random Oversampling

![naive random oversampling](https://user-images.githubusercontent.com/74915619/122837397-025bef80-d2c2-11eb-9731-e9c04273750c.png)

The Naïve Random Oversampling method resulted in an accuracy score of 64.97%, a precision score of 99% and a recall score of 68%.  

### SMOTE Oversampling 

![SMOTE oversampling](https://user-images.githubusercontent.com/74915619/122837402-0425b300-d2c2-11eb-9e5a-fcafd183b099.png)

The SMOTE method resulted in an accuracy score of 64.43%, a precision score of 99% and a recall score of 66%.  

### Undersampling Method

![undersampling](https://user-images.githubusercontent.com/74915619/122837404-05ef7680-d2c2-11eb-8134-1f6181fa2c32.png)

The Undersampling method resulted in an accuracy score of 64.43%, a precision score of 99% and a recall score of 66%.  

### Combination Sampling with SMOTEENN

![combinaton sampling](https://user-images.githubusercontent.com/74915619/122837407-0720a380-d2c2-11eb-9e62-0a624cb83042.png)

The Combination method resulted in an accuracy score of 63.77%, a precision score of 99% and a recall score of 56%.  

### Balanced Random Forest Classifier

![balanced random forest classifier](https://user-images.githubusercontent.com/74915619/122837409-08ea6700-d2c2-11eb-9208-47d7993ac726.png)

The Balanced Random Forest Classifier method resulted in an accuracy score of 78.78%, a precision score of 99% and a recall score of 91%.  

### Easy ensemble AdaBoost Classifier

![easy ensemble adaboost classifier](https://user-images.githubusercontent.com/74915619/122837412-0a1b9400-d2c2-11eb-8d84-14ba22bdf845.png)

The Easy ensemble AdaBoost Classifier method resulted in an accuracy score of 78.78%, a precision score of 99% and a recall score of 91%.  

## Summary

Looking at all 6 of the machine learning models, I would recommend using the Balanced Random Forest Classifier and the Easy Ensemble AdaBoost Classifiers. Both models had an accuracy scores of 78.78, a precision score of 99% and recall score of 91%. The accuracy of the model, precision and recall are very high compared to the other models used. However, even with recommendations, there are many machine learning models in this world that could be even better for this type of technical analysis. 




