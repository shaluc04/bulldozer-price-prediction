﻿## [Predicting the sale price of Bulldozers using machine learning (Time-Series Data)](end-to-end-bulldozer-price-regression.ipynb) 
 
 This notebook goes through an example machine learning project with the goal of predicting sale price of bulldozers.
 
 ### What is Regression?
 Regression analysis consists of a set of machine learning methods that allow us to predict a **continuous outcome variable (y)** based on the value of **one or multiple predictor variables (x)**.
 
 #### Problem Definition
> How well can we predict the future sale price of a bulldozer, given it's characteristics and previous examples of how much similar bulldozers have been sold for?

#### Data
The data is downloaded from Kaggle's "Bluebook for Bulldozers" competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

This is a **time-series data**.There are 3 main datasets:

- **Train.csv** is the training set, which contains data through the end of 2011.
- **Valid.csv** is the validation set, which contains data from January 1, 2012 - April 30, 2012.
- **Test.csv** is the test set. It contains data from May 1, 2012 - November 2012.

#### Evaluation
The evaluation metric for this competition is the **RMSLE (root mean squared log error)** between the actual and predicted auction prices.

The goal for most regression evaluation metrics is to **minimize the error**.
