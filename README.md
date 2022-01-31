# Time_Series_Sales_Predictions

**Time-series, regression-based project to predict future sales for shop-item pairs**

I created this personal project as part of the Kaggle competition 'Predict Future Sales'. The task was to predict sales for shop-item pairs for the month of November, based on previous sales. One particular complication was that some of the items did not appear in the training set. I also ran into memory problems due to the size of the dataset, forcing me to make use of Google Colab Pro + for the higher memory availability.

The project involved a large amount of feature engineering in order to create useful information for the modelling stage. I made use of the Optuna library in order to perform a hyperparameter search for an XGBoost regressor model.
