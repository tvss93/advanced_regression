# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market.

The company wants to know: Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project involves using regression models to predict house prices

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. Data cleaning, including missing value treatment, collinearity check, dummy variable creation and outlier treatment was done.
2. Simple Linear Regression, Lasso and Ridge Regression were applied.
3. Simple Linear Regression was overfitting and Ridge Regression was very complex using almost all variables
4. Lasso variables were taken as a base and RFE was used to get to 25 variables.
5. Further iteration on Simple Linear Regression were done to ensure, no collinear variables are present and all variables are significant
6. The optimal value of alpha for lasso is 50 while its 5 for Ridge
6. The final model has a r squared of 81 on train and 77 on test
7. The most important variables are
'MSSubClass_30',
 'MSSubClass_60',
 'Neighborhood_Crawfor',
 'Neighborhood_MeadowV',
 'Neighborhood_NoRidge',
 'Neighborhood_NridgHt',
 'Neighborhood_OldTown',
 'Neighborhood_StoneBr',
 'BldgType_Twnhs',
 'BldgType_TwnhsE',
 'OverallQual_8',
 'OverallQual_9',
 'OverallQual_10',
 'OverallCond_3',
 'Exterior1st_BrkFace',
 'Exterior2nd_CmentBd',
 'BsmtQual_Fa',
 'BsmtQual_Gd',
 'BsmtQual_TA',
 'BsmtCond_Gd',
 'BsmtExposure_Gd',
 'KitchenQual_TA'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
pandas,numpy, matplotlib, scikit-learn, statsmodel, seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements



## Contact
Created by [@tvss93] - feel free to contact me!

