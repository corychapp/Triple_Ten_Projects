# Megaline Mobile Carrier - Automated Phone Plan Offer Project

## Overview
This project revolves around implementing beginner-level machine learning techniques to automate the process of determining which customers should be offered the updated phone plan for Megaline, a mobile phone carrier. The primary objective is to treat this as a classification task, enabling the company to efficiently identify and target the most suitable customers for the new product offering.

## Details of Beginner Machine Learning
The initial steps involve data cleaning and conducting a thorough Exploratory Data Analysis (EDA). Visualization of the data is facilitated through a heatmap, highlighting correlations among different features. Subsequently, the data is partitioned into features (denoted as 'x') and targets (denoted as 'y'). The `train_test_split` function is employed to create training and test sets, incorporating a random_state parameter and defining a specific test size.

## The Data
The dataset used contains behavioral information about subscribers who have already transitioned to the new plans, stemming from the Statistical Data Analysis project.

## Results
Analysis reveals that more than half of the customers have opted for the Smart Plan. However, there is evidence of overfitting in two training datasets, as their accuracy surpasses that of the test set. The RandomForestClassifier exhibits the highest accuracy rate at 81%, surpassing the 75% threshold. This accuracy is significantly higher than the 50% chance rate in a balanced dataset and exceeds the 75% chance rate in a scenario where data leans towards skewed preferences.
