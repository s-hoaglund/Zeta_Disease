# Zeta Disease Analysis

Mars Mission Control needs a good data-driven system for predicting Zeta Disease infection on the International Mars Colony.
This project uses the `_zeta-disease_training-data_` dataset to build a model that can predict who will be infected by Zeta Disease.

The dataset includes 9 columns with information on 800 people.
1.	age : in years
2.	weight : body weight in pounds (lbs)
3.	bmi : Body Mass Index (weight in kg/(height in m)2)
4.	blood_pressure : resting blood pressure (mm Hg)
5.	insulin_test : inuslin test value
6.	liver_stress_test : liver_stress_test value
7.	cardio_stress_test : cardio_stress_test value
8.	years_smoking : number of years of smoking
9. zeta_disease :
              1 = yes;
              0 = no

This project includes data exploration, data cleaning, and four different models: logistic regression, K-Nearest Neighbors, Random Forest, and XGBoost.

The models were evaluated using accuracy and recall, and XGBoost was found to be the best.

Finally, the best XGBoost model was used to predict new, unseen data.
