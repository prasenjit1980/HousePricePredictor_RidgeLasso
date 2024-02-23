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

	Lasso
GrLivArea	0.268405
OverallQual_10	0.129434
TotalBsmtSF	0.108239
OverallQual_9	0.085077
Neighborhood_NoRidge	0.045434
BsmtFinSF1	0.042436
GarageCars	0.039535
Neighborhood_Crawfor	0.034456
LotArea	0.033786
SaleType_New	0.031389
Neighborhood_StoneBr	0.029757
OverallQual_8	0.02544
OverallCond_9	0.025081
Neighborhood_NridgHt	0.021761
BsmtExposure_Gd	0.020373
Fireplaces	0.019435
Functional_Typ	0.017726
Exterior1st_BrkFace	0.015089
Neighborhood_Somerst	0.013547
OverallCond_7	0.011873
OverallCond_8	0.011752
BsmtFullBath	0.011548
Condition1_Norm	0.011428
BsmtFinType1_GLQ	0.010693
Condition2_Norm	0.010162
LotConfig_CulDSac	0.009477
HalfBath	0.009328
2ndFlrSF	0.009015
FullBath	0.007813
LotFrontage	0.007611
MSZoning_RL	0.007447
WoodDeckSF	0.006773
MSSubClass_60	0.006576
MSZoning_FV	0.006482
MasVnrArea	0.006127
Neighborhood_BrkSide	0.006062
SaleCondition_Normal	0.005831
CentralAir_Y	0.005478
Foundation_PConc	0.004351
GarageCond_TA	0.004075
BsmtCond_TA	0.003325
FireplaceQu_Gd	0.003218
GarageType_BuiltIn	0.00288
LotShape_IR2	0.002525
GarageType_Attchd	0.002251
RoofStyle_Hip	0.002154
Exterior2nd_ImStucc	0.001963
Exterior2nd_VinylSd	0.001418
ExterCond_TA	0.001406
HouseStyle_1Story	0.001167
Exterior1st_VinylSd	0.000027
GarageFinish_RFn	-0.000191
BsmtFinType1_LwQ	-0.000386
HeatingQC_Gd	-0.000674
LotConfig_Inside	-0.000759
Neighborhood_NAmes	-0.001964
GarageType_Basment	-0.001978
LotShape_Reg	-0.002
BsmtExposure_Mn	-0.002322
RoofStyle_Gable	-0.002331
HeatingQC_TA	-0.002414
Neighborhood_OldTown	-0.003001
Exterior1st_HdBoard	-0.003011
Neighborhood_MeadowV	-0.003241
MSSubClass_30	-0.003256
BldgType_Duplex	-0.00353
GarageFinish_Unf	-0.003667
MSSubClass_190	-0.003673
Neighborhood_Mitchel	-0.003917
LowQualFinSF	-0.004633
ExterQual_TA	-0.005619
BsmtExposure_No	-0.006298
Neighborhood_Edwards	-0.006338
OverallQual_3	-0.006474
BsmtQual_Fa	-0.00677
PoolQC_No Pool	-0.007636
OverallCond_5	-0.008103
BldgType_Twnhs	-0.008156
KitchenQual_Fa	-0.009577
BldgType_TwnhsE	-0.010449
OverallQual_4	-0.010606
KitchenQual_Gd	-0.010962
OverallQual_6	-0.011309
OverallQual_5	-0.01131
MSSubClass_90	-0.011618
OverallCond_4	-0.0151
KitchenQual_TA	-0.015806
KitchenAbvGr	-0.016187
BsmtQual_TA	-0.016504
BsmtQual_Gd	-0.016954
OverallCond_3	-0.020241
AgeHouse	-0.040671
Condition2_PosN	-0.347017

Considering above points we can choose our Lasso Regression model as our final model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
