# Mass Prediction for Electron Collison Data
Optimising the XGBoost for Regression model on the CERN dataset for electron collisons using GridSearchCV.
 - Increase in accuracy from 97.38% to 98.86% by the use of the following hyperparameters:
  - colsample_bytree: 0.7
  - learning_rate: 0.1
  - max_depth: 6
  - n_estimators: 1000
 - RMSE decrease from 4.085 to 2.699
