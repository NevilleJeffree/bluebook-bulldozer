# 🚜 Predicting Sales Price of Bulldozers using Machine Learning
In this notebook, we're going to go through an example machine learning project with the goal of predicting the sales price of bulldozer.

1. Problem Definition
Predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers.

2. Data
Data is download from Kaggle Bluebook for Bulldozer competition.

There are 3 main datasets:
* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
3. Evaluation
The evaluation metric is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

4. Features
Kaggle provides a data dictionary detailing all the features of the dataset. View this data on Google Sheet. https://docs.google.com/spreadsheets/d/1-jyQNxlD2HyhArkHa0dTAw7TG3HrXyDfL-V_bkfn5mU/edit?usp=sharing
