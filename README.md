# Cryptocurrencies
## Overview
The purpose of this project is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
Unsupervised machine learning algorithms are used for no known output. To be specific, it is grouping unlabled data into distinct clusters; Detecting unusual data points in dataset; Reducing large datasets into smaller datasets while preserving most of the useful information.
A clustering algorithm will be selected to group the cryptocurrencies and final results will be presented through data visualizations. 

## Analysis process
### 1.Preprocessing the Data for PCA
Data preprocessing refers to the technique of cleaning and organizing the raw data to fit the trained Machine Learning models.
In this project, "dropna()" to remove null values, "drop(columns=[])" to drop "IsTrading" column, and drop cryptocurrencies without conins mined; "get_dummies()" was used to convert variables from text features to binary format; "StandardScaler()" was used to standardize and transform the data.
crtpto_df (drop all the unnecessary data)


dropping rows with null data and converting columns containing text to binary format
### 2.Reducing Data Dimensions Using PCA
### 3.Clustering Cryptocurrencies Using K-means
### 4.Visualizing Cryptocurrencies Results
## Summary





