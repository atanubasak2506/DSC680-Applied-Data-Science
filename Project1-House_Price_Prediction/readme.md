+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Project Name :  Housing Price Prediction
Application Version :

Python :  3.11.7
Pandas :  2.1.4
XGBoost :  2.0.3

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Business Problem  

House Prices vary frequently, due to socio-economic factor changes. In is white paper I am trying to fit a model that will predict the price of the house depending on several factors.  


Background/History 

I was looking for various sources of data to predict the house price and initially I chose data from Kaggle for this project, the data contained everything, but no time related information was there. So, the ML model that will be coming out of the data will be extremely hard to use in future. So, I changed the dataset to another as mentioned below, that has the information of when the house was build, so it will act as an age of the house, which has major impact on the house price. 

Methods 

The prediction of house price from the data, take some analysis, I have used xgboost regressor model to predict the house price. Initially I used the train test split method to split the data into train and test, Then I have used the train data to fit the xgboost model. After the fitting done, I applied the model in test data, to check the accuracy of the model. R Squared represents the proportion of variance for a dependent variable explained by an independent variable in a regression model. 

Data 

https://www.kaggle.com/datasets/gpandi007/usa-housing-dataset/data