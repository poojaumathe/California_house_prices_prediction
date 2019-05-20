# California_house_prices_prediction
Predicting the house prices in California using the regression techniques in Python

Used California housing dataset from sklearn.datasets.fetch_california_housing. 
More information about the dataset is here:http://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html
With the help of python coding I am visualizing the univariate distribution of each feature, and the distribution of the target.
Visualizing the dependency of the target on each feature (2d scatter plot).
Spliting the data in training and test set. Evaluate Linear Regression (OLS), Ridge, Lasso and ElasticNet using cross-validation 
with the default parameters. Then scale / normalize / transform the data. Does scaling / normalizing / transformation of data help?
Tuning the parameters of the models using GridSearchCV. Do the results improve? 
Visualizing the dependence of the validation score on the parameters for Ridge, Lasso and ElasticNet.
Visualizing the coefficients of the resulting models. Do they agree on which features are important?

From all these techniques I got grid cv search is the best as compare to all others as I tried 4 different models and got best accuracy.


