# Real estate housing price prediction.
----------------------------------------
## Overview:

For this project i will be tackling a regression problem. I will be predicting the housing cost of houses using
a Melbourne Real Estate dataset. The dataset includes over 10,000 datapoints. The dataset has over 21 features such as address, 
number of rooms, number of bathrooms, landsize, distance from city centre, price etc. Using these feature i will be able to create a 
regression model which should accurarly predict the price of the house based on their features.

## Step Taken:

* I first pre-processed and cleaned the dataset, this was to ensure things such as null values and duplicates were dropped.
As this may hinder the model into making accurate predictions later on.
* I further did a thorough data analysis of the dataset, this was to get rid off any features that are closely related. As one of 
them would be redundant therefore dropped.
* The dataset was then split into training and testing, having a 80 to 20 split irrespectively.
* A range of machine learning algorithms was the applied onto the dataset such as
  * linear regression with no feature removed
  * linear regression without feature selection
  * linear regression scaled
  * linear regression with oversampling
  * linear regression with undersampling
  * linear regression grid search
  * linear regression random search
  * decision tree with no feature removed
  * decision tree without feature selection
  * decision tree scaled
  * decision tree with oversampling
  * decision tree with undersampling
  * decision tree grid search
  * decision tree random search
these were then compared to see which algorithm is accurate.  
