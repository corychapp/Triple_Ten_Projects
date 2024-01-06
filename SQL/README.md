# Zuber - SQL Analysis and Hypothesis Testing

## Introduction
This project delves into the analysis of taxi companies, with a focus on Zuber. The primary objectives include identifying the top 10 neighborhoods for rides and testing a hypothesis regarding the average duration of rides from the Loop to O'Hare International Airport on rainy Saturdays.

### Details of SQL Analysis
Employing SQL with PySpark, I analyze the data, experiment with imports such as `SparkSession`, and utilize an internal platform similar to PostgreSQL. This involves building dataframes and executing searches using SQL commands like `FROM`, `SELECT`, `CASE`, `WHEN`, `END AS`, `INNER JOIN`, `OUTER JOIN`, and more. The hypothesis is tested in Python using a t-test, with p-value calculations.

## The Data
Data is parsed from the internet using the `request.get` function and integrated using BeautifulSoup. Additionally, weather data is integrated from an external source (The Weather Channel) for accuracy, converted to JSON format for accessibility.

## Results
Exploratory Data Analysis reveals the taxi company with the largest ride share, showcasing visualizations of the top 20 companies, with Flash Cab being the dominant market share holder. Visualization is also used to highlight the neighborhood with the largest drop-off, identified as the Loop. The analysis leads to the rejection of the null hypothesis, indicating that the average duration of rides from the Loop to O'Hare International Airport does change on rainy Saturdays.
