# Predicting the price of Bulldozers using Machine Learning
## 1. Problem definition

Predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers. https://www.kaggle.com/c/bluebook-for-bulldozers/
## 2. Data

The data is downloaded from the Kaggle Bluebook for Bulldozers competetion: https://www.kaggle.com/c/bluebook-for-bulldozers/data

The data for this competition is split into three parts:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## 3. Evaluation

The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices. https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

The goal is to build a ML model which minimises RMSLE.
## 4. Features

All the features of the dataset can be found in the data dictionary provided in "./data/bluebook-for-bulldozers".
