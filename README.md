# Project Name
> This is a Advanced Linear regression Model Development project on the Surprise Housing dataset.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Outcome of Model Development](#Outcome-of-model-development)
* [Recommendations](#Recommendations)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Introduction
Surprise Housing uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

### Problem Statement
The company wants to purchase houses at a price below their actual values and flip them on at a higher price. For this, the comany is looking at prospective properties to buy to enter the market. The company wants us to build a model that enables to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house

### Business Goal
Surprise housing wants us to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 

### About the Dataset
The company has collected and shared a data set from the sale of houses in Australia . The data is provided in the form of a CSV file (train.csv). The company has also provided the data dictionary for the variables which are part of the historical data (AdvancedRegression.txt).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- numpy - 1.16.2
- pandas - 0.24.2
- matplotlib - 3.0.3
- seaborn - 0.11.2
- statsmodels - 0.9.0
- scikit-learn - 0.20.3

## Outcome of Model Development
### Final Equation
The equation of the best fitted line is:
SalePrice = 0.307567*GrLivArea + 0.207098*LotArea + 0.156561*OverallQual + 0.130853*1stFlrSF - 0.075735*KitchenAbvGr + 0.072945*YearBuilt + 0.067567*GarageCars + 0.067270*OverallCond - 0.064937*KitchenQualTA + 0.062527*Neighbourhood_StoneBR + 0.061766*Neighbourhood_NoRidge - 0.060925*KitchenQual_FA - 0.059986*Lotshape_IR3 - 0.059970*KitchenQual_GD + 0.058434*Neighborhood_NridgHt

### Interpretation
- We see that for every 1 unit raise in Above Ground Living Area, SalePrice increases by 0.30 units while keeping the rest of the parameters constant.
- Similarly, for every 1 unit raise in Lot Area, cnt increases by 0.20 units while keeping the rest of the parameters constant.
- Above ground living area (GrLivArea), Lot Area, Overall material and finish of the house (OverallQual), 1st floor square feet (1FlrSF) have a higher positive correlation with the sale price
- KitchenAbvGr and KitchenQualTA have a negetive correlation with the sale price


## Recommendations
After interpriting our linear regression equation, we see that there are 4 major factors that affect the Sale price:
- **Above Ground Living Area**
- **Lot Area**
- **Overall material and finish of the house**
- **1st floor square feet**