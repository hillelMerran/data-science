# Linear regression project - prediction of house price

This directory contains a project using linear regression model in order to predict the price of habitations in a given city.
It is based on a dataset found in Kaggle describing house sales in the city of Ames.
[Data link](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)

The project is divided in two parts:
## First part - Feature Engineering
This part is focused on cleaning the data and preprocessing it before applying linear regression model.
- Outliers processing
- Null features processing
- Categorial features processing

Code file - Feature_Engineering_on_Ames_data.ipynb
Input - AmesHousing.csv
Output - Ames_Final_Df.csv

## Second part - Linear regression application
Application of linear regression model to the preprocessed data.
- Data splitting
- Data scaling
- Model training
- Model evaluation
- Model prediction on non previously seen data

Code file - Linear_Regression_SalePrice_Ames_Data.ipynb
