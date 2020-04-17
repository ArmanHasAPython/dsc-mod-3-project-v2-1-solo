# Module 3 Final Project - Solo Version

## Directory

All the relevant information including Data Understanding, EDA, and operation of the baseline and 3 learner models are present in the Jupyter Notebook file labelled Customer Churn Data.ipynb

The data set is found in the data folder.

## The Project Task

The task involved producing a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. This was a binary classification problem.

The target audience was the telecom business itself, SyriaTel, and it was of high interest to identify the customers that the organisation was losing money on as they were the one's likely to churn.


Predicting customer churn using SyriaTel's telecommunication data set and enlisting a large group of variables taken into consideration.

The best model predictor was determined by using 3 different models and compared against a baseline model. 

The baseline model was the Logistic Regression model and the 3 learner models were: Decision Trees, XG Boost, and Random Forest Classifier. 

These models were used to evaluate the validation scores on each of these models and the one with the best validation score would have its test data set run at the very end, found in the evaluation section.

Subsequently this data was used to produce a confusion matrix and ROC curve which would be made more interpretable and therefore understandable by the stakeholder in a business context.

## Summary

The method utilising Random Forest Classifier without the Hyperparameter Tuning produced the best result. Based on this data set there is an estimated 14.7% churn rate. This was further evaluated to model a cost prediction to find a more accurate loss to SyriaTel