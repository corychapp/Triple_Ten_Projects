# Rusty Bargain Used Cars - Numerical Methods for Predicting Car Values

## Introduction
In this project for Rusty Bargain Used Cars, the objective is to build a model for quickly determining the value of cars added to the app. Key considerations include the quality and accuracy of predictions, the speed of predictions, and the time required for training the predictive model.

### Details of Numerical Methods
Accessing historical data encompassing technical specifications, trim versions, and prices, the project commenced with data cleaning and exploratory data analysis (EDA). Categorical features were encoded using label encoding in preparation for building the machine learning model. Pipelines were implemented for model evaluation, employing gradient boosting analysis on the test set with hyperparameters for Linear Regression, RandomForest Regressor, and CatBoost Regressor.

## The Data
Real car facts were gathered, processed, and presented for analysis.

## Results
While the dummy model proved to be the fastest, prioritizing accuracy led to the selection of RandomForest Regressor (RFR) and CatBoost Regressor as they provide higher accuracy. Considering both speed and accuracy, RFR emerges as a suitable model for cost analysis.
