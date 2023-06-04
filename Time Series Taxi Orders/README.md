# Time Series Taxi Orders

## Business Goal
Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.
The RMSE metric on the test set should be 48 or less.

## Skills
pandas, numpy, matplotlib, seaborn, scipy, sklearn, machine learning regression, time series, LightGBM

## Result
The model that had the best combined speed and score was LightGBMRegressor. The performance and speed for the LightGBM was better than for all other models and improved from the validation to the test set.
On the test set the rmse was: 1389.0992289826563, CPU times: total: 18 s Wall time: 6.86 s.
