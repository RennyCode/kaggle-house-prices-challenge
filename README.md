## kaggle_house_prices_challenge
This project is an entry for a kaggle house price prediction challenge, based on google collabe environment.
The prediction is build upon reggresion models from the sklearn library (SGDRegressor, LinearRegression).

##Workflow
- Data preparation
- Model testing 
- Prediction subminssion


### Data preparation
This is the first section of the notebook which includes importing the data then editing it to best fit our models, in so we erase columns that contains a majority of Null values, encode categorical features, removing features with low corralation score to our target and normilize values.

### Model testing
To asstimate which model is better we preformed feature selection then with kfold and evaluate the models after choosing the better preforming of the two, to further our prediction we used random search and grid search to find the best hyper paramaters.

### Prediction subminssion
Finally we create the best version of our model, train and validate it to make our final prediction for submission.
