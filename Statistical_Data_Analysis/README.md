# Megaline - Statistical Data Analysis (SDA) Project

## Introduction
As an analyst for the telecom operator Megaline, this project aims to determine which prepaid plan, Surf or Ultimate, brings in more revenue. The commercial department seeks insights to adjust the advertising budget based on plan performance.

### Details of SDA
Conducting a preliminary analysis on a client selection of 500 Megaline clients, I explore data related to client demographics, plan usage, and communication metrics in 2018. Using pandas, I load and clean the data, addressing duplicates, casing, spacing, and missing values across 5 datasets. The index is reset to the plan name for simplicity, and feature engineering is implemented to enrich the data. Groupby functions, aggregations, and pivot tables are employed to extract insights. Visualizations are created to enhance data presentation. Additionally, a hypothesis is formulated and tested using t-tests and p-values.

## The Data
Five datasets are provided for analysis.

## Results
The analysis reveals that Surf users generally require more minutes. Mean and variance calculations for call duration indicate similar user behavior for calls on both plans. Surf users tend to utilize the upper limits of their plan, while Ultimate users stay within or use lower amounts of their plan package. On average, half of the Surf user population exceeds package limits monthly.
