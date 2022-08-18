# house-price-advanced-regression
The Ames Housing dataset is an incredible alternative for data scientists looking for a modernized and expanded version of the often-cited Boston Housing dataset. 

Link for dataset: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

The objective of this machine learning project is to predict the sale price of each house for each Id in test dataset by performing Exploratory data analysis and predictive modelling of training dataset

Summary of work in this project:

•	Collected meaningful insights about the features by performing exploratory data analysis, plotted bargraphs, statistical charts, line charts and bar graphs of the features using matplotlib and seaborn package in python. Imputed missing data

•	Implemented feature scaling techniques to scale large numerical variables.

•	reduced the dimentionality of dataset by selecting important features by modelling the dataset into a Lasso model and eliminated less important features based on feature importance parameter

•	Tested various regression models with regularizations and Developed a regression model using XGBRegressor to predict the sale price of houses in test dataset

•	Evaluated the model based on RMSE, R2 score and adjusted R2 score evaluation metrics, improved the performance with hyper parameter optimization technique using RandomizedSearchCV and achieved a 0.89 R2 score in prediction of sale price of houses

