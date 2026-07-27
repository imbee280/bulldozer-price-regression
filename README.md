# Bulldozer Sale Price Regression — End-to-End Machine Learning

Predicts the auction sale price of bulldozers using historical sales data.

## Tools Used
Python, pandas, NumPy, scikit-learn, Matplotlib, Jupyter Notebook

## ML Model
Random Forest Regressor with RandomizedSearchCV hyperparameter tuning

## Process
1. Exploratory Data Analysis on 400K+ row dataset
2. Datetime feature engineering (saleYear, saleMonth, saleDayOfYear)
3. Categorical encoding and missing value imputation
4. Random Forest Regressor training
5. Hyperparameter tuning (n_estimators, max_depth, min_samples_split, max_features)
6. Evaluation: RMSLE, MAE, R²

## Dataset
Kaggle Blue Book for Bulldozers competition dataset
