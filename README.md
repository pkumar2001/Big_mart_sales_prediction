# Big_mart_sales_prediction

## Problem Statement
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

## Data
We have train (8523) and test (5681) data set, train data set has both input and output variable(s). We need to predict the sales for test data set.


## Summary
I have first calculated the least RMSE error on the train dataset for each of RandomForestRegressor, GradientBoostingRegressor and XGBoost Then which ever model has least RMSE is used on test data. This is done so that the code runs optimised on private the data test.
