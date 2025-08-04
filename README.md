# Airbnb-Price-Predictor
## Overview
This is my repository containing the Jupyter Notebook used to create a Random Forest model that predicts the price of an Airbnb. This notebook includes my project statement, data cleaning and pre-processing, model exploration, feature selection and engineering, as well as analysis peppered throughout. This project was done as part of the Machine Learning foundations course through eCornell, which I did as a part of the Break Through Tech program affiliated with MIT.

## Motivation
I decided to build a model to predict the price of an Airbnb because I was personally curious as to what aspects of a house would most indicate the price, such as location, accomodation, or ammenities. Additonally, as part of the course, we did lots of classification problems, so I wanted to gain more experience with regression problems.

## Data Preparation
I employed techniques using Pandas and scipy methods to clean and pre-process my data. For example, I used the scipy winsorization() method to remove outliers from my data, the Pandas fillna() method to replace missing values with means, and the Pandas replace() method to replace boolean values with 1 or 0. 

## Models Used
Initially, I started simple and used linear regression models and decision trees. After determining that the models were performing very similarly, I then decided to use random forest. 

## Model Optimizing
I employed hyperparameter techniques such as GridSearch to test various combinations of hyperparameters. Additionally, I created plots using seaborn to visualize the relationship between values of features and model performance.

## Metrics Used
I used primarily mean squared error to determine the accuracy of my models. 

## Conclusion
I determined that of the three models I tested, random forest created the highest-performing model. Additionally, I discovered that the model performed the best when it had the most freedom, such as having no maximum depth and a minimum samples per leaf of one. From the initial model configuration I tested, I was able to lower the mean squared error from 222 to about 85, which is a 62% decrease. 
