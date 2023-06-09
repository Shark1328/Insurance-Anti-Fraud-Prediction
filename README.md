# Insurance-Anti-Fraud-Prediction
A model established to predict insurance anti-fraud problems.

There are two baselines in this project, and the details of the code are as follows:

1. The first baseline mainly focuses on familiarizing with the data and previewing the model. After simple data analysis, use CatBoost to build a basic model for prediction.
2. The focus of the second baseline is feature engineering. Process the time series in insurance data and merge multi-dimensional data with correlation (calculate the difference between the start and end dates of insurance). At the same time, the independent variables whose correlation is less than 0.6 are discarded (simplified model). Encode non-numeric data.
3. Use GBDT, decision tree and XGBoost to model and calculate the prediction accuracy through KFold respectively. Finally, the XGBoost with the highest score is used as the prediction model.
