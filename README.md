
# Customer Segmentation - K-Means Clustering

## Overview
A K-Means Clustering model to segment retail store customers based on their purchase history using Annual Income and Spending Score.

## Dataset
Kaggle - Customer Segmentation Tutorial
- 200 customers
- Features: Age, Gender, Annual Income, Spending Score

## Customer Segments Found
| Cluster | Type | Avg Income | Avg Spending |
|---|---|---|---|
| 0 | 😊 Average Customers | $55.3k | 49.5/100 |
| 1 | 💎 Premium Customers | $86.5k | 82.1/100 |
| 2 | 🛍️ Impulsive Buyers | $25.7k | 79.4/100 |
| 3 | 💰 Careful Spenders | $88.2k | Low |
| 4 | 😴 Budget Customers | $26.3k | 20.9/100 |

## Results
- Optimal clusters: 5 (found using Elbow Method)
- Successfully segmented 200 customers into 5 distinct groups

## Libraries Used
- numpy, pandas, matplotlib, seaborn, scikit-learn