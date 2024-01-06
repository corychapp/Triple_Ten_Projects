# Instacart - Exploratory Data Analysis (EDA) Project

## Introduction
This project delves into the analysis of customer habits using data from Instacart, an online grocery ordering and delivery service. The objective is to gain insights into Instacart customer behavior through basic Python skills, data cleaning, and exploratory data analysis.

## Details of EDA
Utilizing fundamental Python techniques, this project involves working with five different dataframes, requiring concatenation for comprehensive analysis. The primary focus lies in preparing the data and generating reports that provide valuable insights into the shopping habits of Instacart customers. Key steps include answering questions through code, explaining results in markdown cells, and visualizing data through plots. Additionally, the top 20 product_ids were identified using the value counts method. The merging process involved creating a `merge_df` variable and implementing merging code for dataframes: `products_df` and `order_products_df`. Subsequently, the top 20 products were filtered using value_counts and sorting.

## The Data
Sourced from Kaggle.com, the dataset was publicly released by Instacart in 2017 for a Kaggle competition. Note that the dataset has been modified from the original.

## Results
Upon analyzing customer habits, noteworthy findings include:
- Sunday, followed by Monday, emerges as the top days for grocery shopping.
- The minimum time people wait before placing the next order is 0 days, while the maximum recorded time is 30 days. On average, customers wait approximately 7 days before their next order.
- Wednesday and Saturday exhibit similarities, with peak purchase hours at 10 am and 3 pm (15:00 hrs) on Wednesdays and around 2 pm (14:00 hrs) on Saturdays.
- Most customers order fewer than 20 items, with the majority falling within the range of 1 to 5 items.
