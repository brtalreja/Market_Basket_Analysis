# Market Basket Analysis with a comparative analysis using K-means clustering

## Overview
This project focuses on analyzing transaction datasets of varying sizes to identify frequent itemsets and association rules using apriori algorithm. Additionally, we compare the MBA findings with K-means clustering results to do a comparative analysis of both the methods.

## Data
The project uses transaction data in CSV format, which includes datasets of different sizes:
- `tr-1k.csv`: 1,000 transactions
- `tr-5k.csv`: 5,000 transactions
- `tr-20k.csv`: 20,000 transactions
- `tr-75k.csv`: 75,000 transactions

## Steps

### Data Preparation
1. Generate the canonical datasets.

### Perform Market Basket Analysis
1. Mine frequent itemsets with a specified support value.
2. Mine association rules with specified support and confidence values.
3. Visualize frequent items and association rules.

### K-means Clustering
1. Convert transaction data to a binary matrix.
2. Determine the optimal number of clusters using the WSS plot.
3. Apply K-means clustering to the binary matrix.
4. Identify and summarize frequent items within each cluster.

### Comparative Insights
1. Compare frequent items from Market Basket Analysis and K-means clustering.

## Conclusion
Both Market Basket Analysis and K-means clustering provide valuable insights into transaction data. MBA highlights direct associations between items, while clustering reveals broader patterns. Together, these methods offer a comprehensive view of customer purchasing behavior.
