# Time_Series_Sales_Predictions

**Time-series, regression-based project to predict future sales for shop-item pairs**

I created this personal project a spart of the Kaggle competition 'Predict Future Sales'. The task was to predict sales for shop-item pairs for the month of Novemeber, based on previous sales. One particualr complication was that some of the items did not appear in the training set.

The project involved a large amount of feature engineering in order to create useful information for the modelling stage. I made use of the Optuna library in order to perform a hyperparameter search for an XGBoost regressor model.
