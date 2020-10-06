# SBAloan_default_model

Our overall objectives are to determine what factors tend to cause a loan to be defaulted on and to create a model to predict which approved loan applications will default on their loan. The data set can be found at Kaggle: https://www.kaggle.com/mirbektoktogaraev/should-this-loan-be-approved-or-denied

The data set can be best explained in having 899,164 rows and 27 columns. It contains data on every SBA loan taken from 1970-2014 in the United States.

In the notebook you will see our initial data cleaning and the pre-analyzation of columns. We then look into different models to support our analysis on which features tend to cause a loan to be fedaulted. We looked into the logistic regression model, the nearest neighbors model, and the XGBoost model. We found XGBoost model performed the best at an accuracy of 90%.
