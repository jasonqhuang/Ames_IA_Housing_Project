# Project 2 - Ames Housing Data and Kaggle Challenge

### Executive Summary

Housing data for Ames, Iowa was loaded and cleaned with the goal of creating a model to predict house sale prices. Exploratory data analysis was performed to munge the data and fit it into a Linear Regression model. The model was submitted to Kaggle as part of a competition to find the lowest Root Mean Squared Erorrs. In order to get the best score, the model was iterated multiple times with different engineered features. 

Further analysis was performed specifically to the effect of garage quality and size to the sale price of the houses. In order to utlize categorical features, dummy variables were generated. This was compiled into a presentation with marketing strategies. 

#### Background

Housing data was provided for Ames, Iowa from 2008-2010. 

#### Problem Statement

How can we improve sale prices on housing data based off of garage features?


#### Data

Imports
Load in Data
EDA
Feature Engineering
Defining Features
Train Test Split
Instantiate Model and Fit to Training Data
Baseline Predictions and Evaluations
Predictions
Scoring
Import Test File

---

### Data Dictionary

| Predictive Variable | Data type | Description |
  ------------------- | --------- | ----------- 
| garage_type | Ordinal | Garage Location |
| garage_yr_blt | float | Year of Garage Built |
| garage_finish | Ordinal | Interior finish of the garage |
| garage_cars | float | Total number of cars that fit in the home's garage | 
| garage_area | float | Size of Garage in Sq.ft |
| garage_qual | Ordinal | Garage Quality |
| garage_cond | Ordinal | Garage Condition |
| paved_drive | Ordinal | Paved Driveway |



### Conclusions/Recommendations

The features that are most positively correlated to the house sale price are the overall size of the garage, quality of the interior of the garage, garage overall quality, and a paved driveway. 
