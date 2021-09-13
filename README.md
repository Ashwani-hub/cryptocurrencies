# cryptocurrencies

## Analysis Overview

Using unsupervised machine learning, create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
This classification could be used by the investment bank to propose a new cryptocurrency investment portfolio to its clients

### Method of Analysis

Following methods were used for the analysis
* Preprocessing the database,
* Reduce data dimension using PCA,
* Cluster cryptocurrencies using K-Means,
* Create visualization results with 2D and 3D scatter plots.

## Resources
* Data Sources: crypto_data.csv (Retrieved from  CryptoCompare)
* Software: Python 3.7.10, Conda 4.10.3, Jupyter Notebook 6.3.0

## Results

### Clustering Cryptocurrencies using K-Means – Elbow Curve

An output of 4 clusters was decided based on the Elbow Curve.

### Visualizing Cryptocurrency Results

#### 3D-Scatter plot with clusters

![image](https://user-images.githubusercontent.com/82815722/133134012-54d53ce4-3ec9-4c20-aac5-6e46e02b41f7.png)

## Summary

Classification of 532 cryptocurrencies were identified based on similarities of their features.
