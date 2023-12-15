# Project-On-Linear-Regression-1
Implementation of simple linear regression to predict delivery time.
# Objective
Is to predict the delivery time using sorting time.
# 
Used perticular libreries to perform EDA,plotting and to get data information . Used Linear Regression  model to predict the delivery time.
# Methodology
## 1.Preprocessing and EDA:
Performed EDA to get more informative features about the given data set and got the below insights.
* No null values in dataset.
* No outliers in dataset.
* delivery time is having 82.5% correlation with sorting time.
* maximum occurence of sorting time is 7.
* max delivery time is 29, min delivery time is 8, average delivery time is 17
* max sorting time is 10, min sorting time is 2, average sorting time is 6. max sorting time count is 7.
## 2.Model Building and Model Validation:
Model used here is simple Linear Regression. Model validation done by using r2_score and root mean square error and got
* model intercept_ is 6.6 and coef_ is 1.60
* model r2_score is 57% and RMSE is 2.33
# Insights:
* In above project we have dataset of delivery time and sorting time.
* It is observed that delivery time and sorting time is strongly correlate with each other.
* max delivery time is 29, min delivery time is 8, average delivery time is 17
* max sorting time is 10, min sorting time is 2, average sorting time is 6. max sorting time count is 7.
* Then built simple linear regression machine learning model to predit delivery time based on sorting time.
* model coefficient of determination is 0.57, so model is good fit.
