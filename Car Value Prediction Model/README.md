# Car Value Prediction Model

## Business Goal
A used car sales company is developing an app which can provide customers with the market value of a car. Goal is to build a model that will use car data to determine the value of car. The model should take into account:
 - the quality of the prediction
 - the speed of the prediction
 - the time required for training

## Skills
pandas, numpy, matplotlib, seaborn, scipy, sklearn, machine learning regression, Catboost, LightGBM

## Result
The model that had the best combined speed and score was LightGBMRegressor. The performance and speed for the LightGBM was better than for all other models and improved from the validation to the test set.
On the test set the rmse was: 1389.0992289826563, CPU times: total: 18 s Wall time: 6.86 s.
