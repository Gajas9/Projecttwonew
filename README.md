# Phase 1 Project Template - Minimum Viable Product (MVP)



**Author**: Gaja Sanchayan

## Overview

In this analysis , we used a set of data about house prices in Northwestern country to analyze what factors drives the house prices in that area which will be used by real estate agency to advice potential sellers.

## Business Problem

To provide analysis on what factors drives the house prices in Northwestern country to Local Real estate Agency for them  to advice potential sellers.


## Data
The analysis is based on a large data set of approximately 21500 housing sales. The data includes many different types of information about each houses. They were cataegorized in to two different types of data:
Continuous Data- Sqft Living, Sqft Lot, Price etc
Categorical Data –Bedrooms,Bathrooms, Grade, Condition, View 

## Methods

1.Data preparation and cleaning
Understanding the available  Data (Scatter plot )
Dropping few Features as they are not highly  related to house prices- (date, lat, long, zipcode, view)
2. Regression modelling
A baseline model and two Iteration models after to find the best line of fit to predict the house prices in future
Model Assumptions to Verify the model
2. Model Validation
Validate the model to see how well the model is generalizing to future cases


## Results

Based on Iteration 3 Model Summary, following predictions are made:
There is positive relation ship between Price and Sqft.living, Condition and Grade
For each unit increase in Sq.ft living, there will 0.56 increase in price 
For each unit increase in condition, there will 0.08 increase in price 
For each unit increase in Grade, there will 0.25 increase in price 
There is negative relationship between Price and Sq.ft lot, bedrooms >4, and Bath>2
The model validation was done using Train/Split method where 70% of sample used  for training and 30% for testing.
The Mean square error of the residuals of both the samples were compared. There does not seem to be a big difference between the train and test MSE! Thus we can say the model is  generalizing well to future cases and is the best line of Fit.







