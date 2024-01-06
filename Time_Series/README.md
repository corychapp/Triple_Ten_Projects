# Sweet Lift Taxi - Time Series Prediction for Taxi Orders

## Introduction
Sweet Lift Taxi aims to attract more drivers during peak hours by predicting the number of taxi orders for the next hour. This project involves building a predictive model for such forecasts.

### Details of Time Series
The project begins with exploratory data analysis (EDA), followed by resampling of the data and feature engineering for time spacing features. Functions are created to visualize different time intervals, and a correlation matrix is generated. The statsmodel framework is utilized for decomposition, providing insights into periodic patterns. Additionally, an RMSE function is created as an accuracy metric, and the model is built using the Gridsearch framework.

## The Data
The dataset provides information on the number of taxi orders along with corresponding timestamps.

## Results
The data is compiled based on accumulated hourly actions, highlighting the busiest hours, such as approximately 9 pm to 1 am. Weekends exhibit higher activity, while requests are slower from 5 am to 7 am. The final evaluation on the test set reveals that the Catboost model presents the lowest RMSE, albeit with a longer runtime.
