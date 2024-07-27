# CryptoClustering
This challenge use the knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Project Structure
- The initial data source can be found in the Resources folder- "crypto_market_data.csv"
- Analysis of data can be found in "Crypto_Clustering.ipynb"

Methodology
- Prepare the Data
- Find the Best Value for k Using the Original Scaled DataFrame
- Cluster Cryptocurrencies with K-means Using the Original Scaled Data
- Optimise Clusters with Principal Component Analysis
- Find the Best Value for k Using the PCA Data
- Cluster Cryptocurrencies with K-means Using the PCA Data

Finding and conclusion:
1. PCA: total explained variance of the three principal components is 89.5%.
2. The best k value found using the PCA data appears to be the same as the best k value found using the original data, both answer is 4.
3. Using fewer features PCA for clustering with K-Means results in more compact and distinct clusters. The PCA reduces dimensionality and noise, leading to better-defined clusters compared to clustering with the original data. It makes grouping of the data, preclear and interpretable.
