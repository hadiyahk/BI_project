# Titanic Data Analysis Project

## Overview

This project explores the Titanic dataset using data analytics and machine learning techniques to analyze survival patterns. The analysis includes decision tree classification, clustering, and outlier detection using KMeans and LOF (Local Outlier Factor) methods.

## Dataset

The dataset includes information about Titanic passengers, such as:
- Passenger details: ID, class, sex, age, fare, and more.
- Survival information: Whether the passenger survived the disaster.
- Boarding details: Port of embarkation, siblings/spouses, parents/children aboard, etc.

## Objectives

1. Analyze the Titanic dataset to identify patterns in survival.
2. Handle missing data effectively for analysis.
3. Implement machine learning models to classify and cluster passengers.

## Methods

1. **Data Cleaning**: Replace missing values and construct new attributes for analysis.
2. **Data Transformation**: Convert categorical data to binary and format for clustering.
3. **Machine Learning**:
   - Decision Tree for classification based on survival probability.
   - KMeans clustering to group passengers by attributes.
   - LOF and distance-based methods for outlier detection.

## Tools Used

- RapidMiner for data analysis and visualization.
- Decision Tree, KMeans clustering, and outlier detection algorithms.

## Key Insights

- Wealth and passenger class significantly influenced survival rates.
- Women and children had higher survival probabilities.
- Missing data was handled through frequency binning and other methods.

## Conclusion

This project demonstrates the application of machine learning models to analyze survival data, offering insights into passenger survival during the Titanic disaster.

## References

1. [Predicting the Survival of Titanic Passengers - Towards Data Science](https://towardsdatascience.com/predicting-the-survival-of-titanic-passengers-30870ccc7e8)
2. [Titanic - Machine Learning from Disaster - Kaggle](https://www.kaggle.com/c/titanic)
3. [A Titanic Probability - Stanford](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html)
