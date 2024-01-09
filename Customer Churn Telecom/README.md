# Customer Churn Telecom

## Business Goal
We built a model for telecom operator Interconnect to forecast their churn of clients.  We also explored features that may be associated with churn in order to make suggestions to the company on how to prevent churn. We built and compared different binary classification models, and used oversampling and hyperparameter tuning to improve model evaluation scores.

## Skills
pandas, matplotlib, seaborn, sklearn, machine learning with imbalanced data, CatBoostClassifier, XGBClassifier, LGBMClassifier, SMOTE, Pipeline, GridSearchCV

## Result
Our best perfoming model was the CatBoostClassifier model with an AUC-ROC score of 0.84 and an F1 score of 0.64. We can see from the feature importance plot that the features that contributed most to churn were longevity and monthlycharges. Customers who had shorter longevity with the company and higher monthly charges were more likely to churn. 
