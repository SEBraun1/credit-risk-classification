## Overview of the Analysis

This analysis was conducted to produce a supervised learning model that can predict the creditworthiness of borrowers. 

The dataset used in the model was harvested from a peer-to-peer lending service containing historical lending data and included
fields such as borrow income, debt to income ration, derrogatory remarks, etc. 

The target variable of interest was 'loan status', ie: "Healthy" or "High-risk".

Steps:

- Separate data into labels and features
- Split data into training and testing subsets
- Instantiate, fit, and predict using a LogisticRegression module
- Evaluate model's performance with balanced accuracy, confusion matrix, and classification report


## Results

* LR_Model 1:
  * The model predicts both, healthy and high-risk, loans with a 99% weighted average of accuracy, precision, and recall.


## Summary

The logistic regression model performs with high accuracy, precision, and recall. Evaluating the macro average, the precision
or positive predictive value is 92%, which could indicate some false positive assignments and evaluation of additional models
is recommended. 
