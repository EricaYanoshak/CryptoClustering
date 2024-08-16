# Title: CryptoClustering
Creating a machine learning model that groups cryptocurrencies to assemble investment portfolios that are based on the profitability of those cryptocurrencies.

## Installation
The following libraries and dependencies were used to successfully run this project:
- import pandas as pd
- import hvplot.pandas
- from sklearn.cluster import KMeans
- from sklearn.decomposition import PCA
- from sklearn.preprocessing import StandardScaler

## Description: Understanding K-means Algorithm and Principal Component Analysis (PCA)
This Challenge consisted of creating a machine learning model that groups cryptocurrencies. This was done by applying the lessons learned in week 11, specifically the K-means algorithm and PCA to classify cryptocurrencies according to their price fluctuations across various timeframes; and by examining price changes over intervals spanning 24 hours, 7 days, 30 days, 60 days, 200 days, and 1 year. 

## Methodology
1. Preparing the Data
2. Finding the Best Value for k Using the Original Scaled DataFrame
4. Clustering Cryptocurrencies with K-Means Using the Original Scaled Data
5. Optimizing Clusters with Principal Component Analysis
6. Finding the Best Value for k Using the PCA Data
7. Clustering Cryptocurrencies with K-Means Using the PCA Data
8. Determining the Weights of Each Feature on Each Principal Component

## References Used
To complete this project, I relied heavily on class notes and activities provided during week 11.