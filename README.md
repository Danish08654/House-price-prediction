#  House Price Prediction using Machine Learning

##  Overview
This project focuses on predicting house prices using machine learning techniques based on property features such as area, number of bedrooms, location, and more.

##  Objective
To build a regression model that accurately predicts house prices using structured housing data.

##  Dataset
The dataset includes the following features:

1) Area (square footage)
2) Bedrooms
3) Bathrooms
4) Floors
5) YearBuilt
6) Location
7) Condition
8) Garage
9) Price (Target Variable)

##  Data Preprocessing
1) Removed unnecessary columns (Id)
2) Handled missing values
3) Applied **one-hot encoding** on categorical features:
4) Location
5) Condition
6) Garage

##  Model Used
1) Linear Regression
2) Gradient Boosting Regressor (final model)

##  Prediction
The model predicts house prices based on input features.

##  Evaluation Metrics

1) Mean Absolute Error (MAE)
2) Root Mean Squared Error (RMSE)

##  Visualization

Actual vs Predicted house prices were plotted to evaluate model performance.
