# Credit-Risk-Analysis

## Overview of the loan prediction risk analysis:

This project analyzes how all the factors in our loan_stats csv can help predict the credit risk status of credit card users. We used imbalanced-learn and scikit-learn libraries to design models and evaluate them using a resampling method. This includes: 

- Oversample the data using the RandomOverSampler and SMOTE algorithms. 

- Undersample the data using the ClusterCentroids algorithm. 

- Use a combinatorial approach of over and undersampling using the SMOTEENN algorithm. 

-Compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

- Evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.



## Results:

## Naive Random Oversampling: 


![1_RandomOversampler](https://user-images.githubusercontent.com/104735724/185832754-b8ca03d9-163b-42fc-b154-deb4789468e0.png)
