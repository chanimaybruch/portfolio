# Time Series Taxi Orders

## Business Goal
Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.
The RMSE metric on the test set should be 48 or less.

## Skills
pandas, numpy, matplotlib, seaborn, scipy, sklearn, machine learning regression, time series, LightGBM

## Result
LightGBM on the test data: 42.3. LightGBM was the best model of the models we tried at predicting the number of taxi orders in the next hour. The model had some overfitting yet the result was an improvement over the baseline RMSE.
