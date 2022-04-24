# Diamond-Price-Calculator
## About:
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence). Using the dataset, Diamonds, we investigated the relationships between the variable ‘Price’ and the rest of the variables. Subsequently, we created a Diamond Price Calculator using Google Colab’s Form Function, which predicts the price of diamonds with relevant inputs.
## Contents of Code:
### Data preparation & mining
Removal of outlier values, removal of unnamed variables & faulty minimum values
### Exploratory Analysis 
Box plot , Heatmap & Histogram on relationship of 4C’s 
### Machine Learning 
Label Encoding on top of Linear Regression and Random Forest Regressor

One Hot Encoding on top of Linear Regression and Random Forest Regressor
### Diamond Price Calculator 
## Contributors:
### Dylan Lim Zhuo Yang
Data preparation & mining, Exploratory Analysis 
### Lim Sin Pei
Machine Learning, Diamond Price Calculator 
## Problem Definition:
How do different variables determine the prices of diamonds in the market?

How does the different variables of each specific diamond's clarity, cut, colour and carat contribute in determining their true market value & rarity?
## Machine Learning Model Selected:
We have selected the model with the lowest RMSE (Root Mean Square Error), which was the Random Forest Regressor, with Label Encoding done to categorical variables
## What did we learn from this project?
When exploring regression models, there are multiple ways to deal with categorical data. While Label Encoding (manual encoding instead of the typical alphabetical-order-label-encoding) went better with the Random Forest Regressor, One Hot Encoding went better with the Linear Regression.
## References
https://www.kaggle.com/datasets/shivam2503/diamonds

https://levelup.gitconnected.com/random-forest-regression-209c0f354c84 

https://www.analyticsvidhya.com/blog/2020/03/one-hot-encoding-vs-label-encoding-using-scikit-learn/

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html 
