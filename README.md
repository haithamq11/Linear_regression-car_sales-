# Linear_regression-car_sales-

## Real life example about car sales: Project Overview

We will deal with a real-life example of car sales to predict the price for cars, then we go through several steps as follows:

* clean 
* relax assumptions 
* log transformation
* create model
* create dummies

## Resources

**Python Version:** 3.7

**Packages:** pandas, numpy, sklearn, matplotlib, seaborn

**Dataset Source:** https://github.com/timurista/data-analysis/blob/master/python-jupyter/1.04.%20Real-life%20example.csv

## dataset details

Here are the columns in dataset as follows:

* Brand: car brand such as BMW, Mercedes-Benz, Audi and Toyota
* Price: Price of car
* Body: type of car body such as sedan, van and crossover
* Mileage: aggregate length or distance in miles
* EngineV: engine size
* Engine Type: petrol, diesel and gas
* Registration: yes or no
* Year: year of car
* Model: model of car

## Data Cleaning

We cleaned the dataset before fed to model. these are the changes as following:

* Drop the column 'Model'.
* dealing with missing values.
* Dealing with outliers.
* Checking the OLS assumptions
* Checking Multicollinearity

## Model Building

I transformed the categorical variables into dummy variables. I also split the data into 20% test and rest is train set.
import Linear Regression model to train dataset and linear Regression scored 74%. 
