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

## 3/ dm-04 (Naive Bayes Classifier 1)

My project uses the dataset "Bank Marketing" for the purpose of creating a model to correctly predict if customers will make a term deposit or not using data of 16 explanatory variables and 1 response variable. Among 16 explanatory variables, 9 are non-numeric, which means they will be preprocessed to dummy variables. The response value is in binary type: "yes" and "no".

In this project, for simplicity I will only focus on two models: Naive Bayes Classifier (Gaussian) and Logistic Regression model. I also assume a profit formula to evaluate two models and find out the one which brings about the largest amount of profit. I also use the variable selection function to pick out variables which generate best profit out of all models.

## 4/ dm-05 (Naive Bayes Classifier 2):

My project uses the Reddit API to get Reddit user's posts as the dataset for the purpose of creating a model to correctly predict the topic of each post. The explanatory variable is "body" (the body of a post), and the response variable is "subreddit" (topic of the post). In this analysis, we only deal with 5 response values: 'MachineLearning', 'DeepLearning', 'ImageProcessing', 'DataAnalysis', 'Python'.

In this project, for simplicity I will only focus on two models: Naive Bayes Classifier and Neural Network model. Test accuracy is used as the metrics to compare two models and give conclusions.

## 5/ dm-06 (Dimensionality Reduction 1)

Data source: https://archive.ics.uci.edu/ml/datasets/bank+marketing




## 6/ dm-07 (Dimensionality Reduction 2)

Data source: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data


## 7/ ai-07 (Classification Prediction Accuracy)

Data source: https://www.kaggle.com/imsparsh/churn-risk-rate-hackerearth-ml?select=train.csv
