# Bankruptcy Prediction
## Overview
Bankruptcy prediction is of great importance in economic decision making, which aims to assess the financial condition of a company and its future perspectives within the context of longterm operation on the market. This project focuses bankruptcy prediction based on one real world data set, mainly focusing on tackling imbalance and the comparison of different methods.
## Dataset
The data set is Polish companies bankruptcy data, which contains 5910 observations and 65 variables. Only 410 out of 5910 observations are bankrupt, indicating the data is highly imbalanced. Moreover, there exist 4666 missing values in the predictors, so an imputation technique should be performed.
**Link:** https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data
## Dependencies
Install the following dependencies using pip:
* numpy
* pandas
* matplotlib
* seaborn
## Evaluation Metric
In cases of class imbalance, AUC of ROC curve is a preferred evaluation metric over accuracy.
## Result
XGBoost gives AUC score of 0.88.