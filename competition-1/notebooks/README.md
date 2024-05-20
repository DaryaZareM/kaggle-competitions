# House Prices: Advanced Regression Techniques - Kaggle Challenge

## Introduction
In this notebook, we aim to solve the Kaggle challenge: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview/evaluation). The goal of this competition is to predict the final prices of homes based on various features describing the properties.

![](https://storage.googleapis.com/kaggle-media/competitions/House%20Prices/kaggle_5407_media_housesbanner.png)

## Dataset Information
The dataset consists of a training set and a test set. The training set includes the SalePrice for each house, while the test set omits this value. We will use the training data to train our model and make predictions on the test data.

## Objectives
1. Preprocess the data: Handle missing values, encode categorical variables, and normalize/standardize numerical variables.
2. Train and evaluate multiple regression models: RandomForest, XGBoost, SVC, and Linear Regression.
3. Tune hyperparameters to find the best model.
4. Make predictions on the test set and save the results.

## Dependencies
This notebook requires the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Instructions
1. Ensure you have all the required libraries installed.
2. Download the dataset from the Kaggle competition page and place the `train.csv` and `test.csv` files in the appropriate directory.
3. Run the cells in the notebook sequentially to reproduce the results.
