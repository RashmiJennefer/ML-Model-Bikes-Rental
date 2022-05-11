# Boom Bikes ML Model
This model aspires to understand the demand for shared bikes among the people after the quarantine situation ends across the nation due to Covid-19.


## Table of Contents
* Problem Statement
* Steps to build ML Model
* Technology Used
* Conclusions
* Acknowledgements

## Problem Statement
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- To identify the variables which are significant in predicting the demand for shared bikes eg holiday, workingday, temp etc.
- How well those variables describe the bike demands
- To create a linear model that quantitatively relates demand for shared bikes with the available independent variables.

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Steps to build ML Model
The steps we will follow in this exercise are as follows:
1. Reading, understanding and visualizing the data
2. Preparing the data for modelling (train-test split, rescaling etc)
3. Training the model
4. Residual analysis
5. Predictions and evaluation on test set

## Technologies Used
- Multiple Linear Regression
- EDA (Exploratory Data Analysis)
- Hypothesis Testing

## Conclusions
- We can see that temperature variable is having the highest coefficient 0.5390, which means if the temperature increases by one unit the number of bike rentals increases by 0.5390 units. Therefore US bike-sharing provider BoomBikes can focus more on Temperature
- We also see there are some variables with negative coefficients. A negative coefficient suggests that as the independent variable increases, the dependent variable tends to decrease. We have mist cloudy , light snow variables with negative coefficient. So during this time we can give offers on bike rentals to increase the business.
- Can focus more on Summer & Winter season, August, September month, Weekends, Working days as they have good influence on bike rentals.

## Acknowledgements
- I thank God almighty for giving me the strength and wisdom to do the project.
- This project was inspired by family and friends.


## Contact
Created by [@RashmiJennefer] - feel free to contact me!
