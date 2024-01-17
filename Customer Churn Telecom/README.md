# Customer Churn Telecom

## Business Goal
We built a model for telecom operator Interconnect to forecast their churn of clients.  We also explored features that may be associated with churn in order to make suggestions to the company on how to prevent churn. We built and compared different binary classification models, and used oversampling and hyperparameter tuning to improve model evaluation scores.

## Skills
pandas, matplotlib, seaborn, sklearn, machine learning with imbalanced data, CatBoostClassifier, XGBClassifier, LGBMClassifier, SMOTE, Pipeline, GridSearchCV

## Result
Our best perfoming model was the CatBoostClassifier model with an AUC-ROC score of 0.84 and an F1 score of 0.64. 

Customers who cancelled were fairly new customers or customers with a lower longevity. They averaged less than a 10 month longevity compared to customers who remained, who averaged around a 40 month longevity. Churn was moderately negatively correlated with longevity (-0.36), so that the longer a customer remains, the less likely the customer was to churn. Customers who churned had a higher percentage of month-to-month contracts, 88%, compared to no_churn customers where 43% had month-to-month contracts. This indicates that customers who signed up for contracts of a longer duration were less likely to churn.

Customers who had a higher monthly fee were more likely to leave. In addition, customers who paid by electronic check were more likely to leave than those who paid by mail check, credit card or bank transfer. It is unclear why electronic check would be associated with churn. It is possible that customers who paid by electronic check did not have an automatic payment and so they saw their invoice each month, which may have motivated them to churn.

Also internet service was found to be an important feature in predicting churn. It is worthwhile to explore if churn based on internet serivce was due to the high cost of the service or poor service quality.

Other factors that may be associated with churn and need further exploration were techsupport, onlinesecurity, onlinebackup, and dependents.

Suggestions to the company to prevent churn:

The company might offer a financial incentive to sign up for an annual or multi-annual contract instead of monthly. A customer who is signed up for 12 months or longer has a greater likelihood of remaining. For example, customers could receive a 20% discount to sign up for an annual contract.

Also, is possible that if the payments were automatic then month-to-month customers would not think monthly about their monthly fee and would retain the service. Therefore, the company might offer financial incentives to get automatic payments. For example, offer a discount for customers to transfer to an automatic payment plan.

In addition, the company could temporarily offer a lower fee for more expensive services such as internet services so that customers would get used to them and be willing to pay the higher fee once the temporary low fee period has ended.
