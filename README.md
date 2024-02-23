# Project Name
> House Price Prediction using Ridge and Lasso Regression


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market.

The company wants to know:

* Which variables are significant in predicting the price of a house.
* How well those variables describe the price of a house.

This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Pandas - version 2.0.3
- NumPy - version 1.24.3
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.2
- Jupyter Notebook 6.5.4

## Conclusions
- On analysing data, it was observed that, Ridge and Lasso both the models have almost same test and train accuracy. So it can be said that there is no overfitting.
- Lasso and Ridge both have similar r2 score and MAE on test dataset but Lasso has eliminated features and final no. of features in Lasso Regression model is 93. Where - Ridge has all 280 features. So, our Lasso model is simpler than Ridge with having similar r2 score and MAE.
- Ridge Regression model on test dataset: r2 score= 0.794697, RSS= 1.211327, MSE= 0.002778	and RMSE=0.052709 Lasso Regression model on test dataset: r2 score= 0.741649, RSS= 1.524321, MSE= 0.003496 and RMSE=0.059128.

Considering above points we can choose our Lasso Regression model as our final model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
