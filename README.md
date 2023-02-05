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
* The dataset was then split into training and testing, having a 80 to 20 ratio split of the dataset irrespectively.
* A range of machine learning algorithms was the applied onto the dataset such as; linear regression with no feature removed, linear regression without feature selection, linear regression scaled, linear regression with oversampling. These exact same techniques were applied but using decision tree instead of linear regression.
* All these algorithms were compared to one another to see which one was the most accurate.

## Results:

Through comparing the different machine learning algorithms it was found that decision tree with oversampling had highest accuracy prediction with 99.75% accuracy on the testing set.


