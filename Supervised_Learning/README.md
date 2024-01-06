# Beta Bank - Supervised Learning for Customer Churn Prediction

## Introduction
Beta Bank is facing the challenge of customers leaving on a monthly basis, and the focus is on retaining existing customers rather than acquiring new ones. This project aims to predict whether a customer will leave the bank soon, enabling targeted efforts to retain potentially departing customers with enticing offers for enhanced loyalty.

### Details of Supervised Learning
Following data cleaning and exploratory data analysis (EDA), one-hot encoding is applied to feature preparation for machine learning, particularly in non-numeric features. Addressing class imbalance, hyperparameters are adjusted to weight the data for accurate calculations and prevent overfitting. The dataset includes information on clients' past behavior and contract terminations with the bank. StandardScaler function is used to normalize data features for evaluation. The model is fitted using the training set, and the scaler ensures consistent scaling across training, validation, and testing sets.

## The Data
The dataset encompasses information on clients' past behavior and contract terminations with the bank.

## Results
The model is constructed with the goal of achieving an F1 score of at least 0.59. The F1 score for the test set is evaluated, and the AUC-ROC metric is measured and compared with the F1 score. The Random Forest Classifier emerges as the best model, yielding a final F1 score of 0.62, exceeding expectations. Visualizations depict the AUC-ROC metric, confirming that the model performs better than random chance.
