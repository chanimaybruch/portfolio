# Customer Churn Telecom

## Business Goal
We will build a model for telecom operator Interconnect to forecast their churn of clients.  We will also explore features that may be associated with churn in order to make suggestions to the company on how to prevent churn. This is a binary classification model. We will compare different classification models, and use oversampling and hyperparameter tuning to improve evaluation scores.

## Skills
pandas, matplotlib, seaborn, sklearn, machine learning with imbalanced data, CatBoostClassifier, XGBClassifier, LGBMClassifier, SMOTE, Pipeline, GridSearchCV

## Result
Our best perfoming model was the CatBoostClassifier model with an AUC-ROC score of 0.84 and an F1 score of 0.64. We can see from the CatBoost feature importance plot the features that contributed most to churn were longevity, monthlycharges, techsupport, paymentmethod, onlinesecurity, and internetservice.
