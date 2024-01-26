## CryptoClustering
# University of Denver, AI and ML Bootcamp. Module 11 Challenge.

# Crypto Market Analysis

## Overview
This project focuses on analyzing cryptocurrency market data using machine learning and data visualization techniques. 

The primary goal is to group cryptocurrencies based on their price change percentages over different time intervals, utilizing KMeans clustering and Principal Component Analysis (PCA).

## Installation
To run this project, you need to install the following libraries:

- pip install: pandas, hvplot, scikit-learn

## Usage
Import the required libraries and dependencies:
 - import pandas as pd
 - import hvplot.pandas
 - from sklearn.cluster import KMeans
 - from sklearn.decomposition import PCA
 - from sklearn.preprocessing import StandardScaler
   
Load the data into a Pandas DataFrame and perform exploratory data analysis:
 - market_data_df = pd.read_csv("Resources/crypto_market_data.csv", index_col="coin_id")

Normalize the data using StandardScaler, cluster the cryptocurrencies using KMeans, and determine the optimal number of clusters (k) by analyzing the Elbow Curve.

Additionally, apply PCA to reduce dimensionality and repeat the clustering process.

## Features
The project involves the following key steps:

Data Preparation: 
 - Standardizing the data for better clustering results.
 - KMeans Clustering: Grouping cryptocurrencies based on their market characteristics.
 - Elbow Method: Determining the optimal value of k for KMeans clustering.
 - PCA Analysis: Reducing dimensionality and re-clustering using PCA data.
 - Visualization: Creating scatter plots for visual analysis of clusters.

Contributing
Contributions to this project are welcome. Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
