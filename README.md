# Project list:

## 1/ ai-05 (Clustering 1):

In this project, I chose the dataset "Ch10Ex11.csv" from the website: https://www.statlearning.com/. This dataset contains 1000 gene expressions of 40 tissue samples with the first 20 samples are from healthy patients while the remaining are from the diseased. The dataset file, however, was generated as 40 columns and 1000 rows, therefore there is a need to make a transpose matrix from the original data file.

In this project, we will use clustering to check if hierarchical clustering and k-means clustering may correctly classify these samples into 2 groups as labeled. Naive Bayes Classifier (a supervised method) is also used to compare results with unsupervised learning models aforementioned. Finally, we will check which genes differ the most between 2 clusters by using loadings.

## 2/ ai-06 (Clustering 2):

In this project, I make use of the dataset "OnlineRetail.csv" from the website: https://www.kaggle.com/vijayuv/onlineretail.

This dataset contains all purchases made for an online retail company based in the UK during an eight month period. The dataset includes 8 columns (all explanatory variables) with no response values. 

For this dataset, I conducted two main analyses:
1/ Customer clustering using RFM (recency - frequency - monetary) analysis. By creating a RFM table, I cluster customers into groups to find out which customer cluster to focus efforts on to generate the most profits. Both k-means and hierarchical clustering are applied in this project to compare clustering results.

2/ Find out buying behaviors: I make use of Apriori algorithms to find out list of products that are bought together most often.
