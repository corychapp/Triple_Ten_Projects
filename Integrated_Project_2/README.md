# Zyfra - Integrated Project 2: Gold Mining

## Introduction
This integrated project revolves around Zyfra, a company specializing in efficiency solutions for heavy industry. As a business-to-business entity, Zyfra aims to address challenges in the heavy industry by providing solutions to enhance efficiency. The specific goal of this project is to predict the quantity of gold ore that will be extracted from a gold site. The focus is on identifying inefficiencies, optimizing profitable parameters, and ensuring effective extraction processes.

### Details of Linear Algebra
The initial steps involved data cleaning and exploratory data analysis (EDA). Care was taken to prevent data leakage in the models by ensuring that certain features were not made available for the test set. Given the presence of outliers in the data, appropriate manipulation techniques were applied. Histograms were plotted to analyze chemical changes in the extraction process. Functions and pipelines were employed to construct models for cross-validation, and model hyperparameters were fine-tuned using a cross-validated grid search. The Scoring Metric for models was determined using the Symmetric Mean Absolute Percentage Error (SMAPE).

## The Data
The dataset encompasses information on the extraction and purification process. It is derived from various sets, and all relevant information is consolidated in the full dataset.

## Results
Noteworthy observations from the purification stages include a significant positive mean change in gold content, an increase in lead content, and a minor negative change in silver mean. The recovery process was accurately calculated. To assess data spread, the interquartile range was utilized, and outliers were identified by multiplying the difference between the 75th and 25th percentiles by 1.5. Among over 16,000 data observations, a minimal number of outliers had a substantial impact, reducing the mean absolute error from 69.163 to 1.0875. The recovery process was consistently calculated and accurately represented.
