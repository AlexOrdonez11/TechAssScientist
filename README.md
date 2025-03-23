In this repository you will find a anlaysis of the dataset Global Weather Repository.csv
It contains Exploratory data analysis (EDA) of a weather dataset, followed by predictive modeling for a specific location (Tegucigalpa, Honduras). 
The primary themes revolve around data exploration, outlier detection, feature engineering, data scaling, correlation analysis, and the application of time series forecasting models, including LSTM neural networks, Random Forest Regressor, and a stacked model. 
The document highlights the data preprocessing steps, model building, evaluation metrics, and feature importance analysis.

Feel free to take a look at the code in the Analysis.ipynb file

Resulting in the followint measures

LSTM Model:

Train Mean Squared Error (MSE): 1362.2510

Train Root Mean Squared Error (RMSE): 36.9087

Train Mean Absolute Error (MAE): 9.2302

Test Mean Squared Error (MSE): 8681.2693

Test Root Mean Squared Error (RMSE): 36.9087

Test Mean Absolute Error (MAE): 24.5857

Random Forest:

Random Forest Train MSE: 178.4549

Random Forest Train RMSE: 13.3587

Random Forest Train MAE: 3.1959

Random Forest Test MSE: 2548.6511

Random Forest Test RMSE: 50.4842

Random Forest Test MAE: 7.8328

Stacked Model (RF & LSTM combined) Linear Regression:


Stacked Model Train MSE: 11.9690

Stacked Model Train RMSE: 13.3587

Stacked Model Train MAE: 0.8627

Stacked Model Test MSE: 5177.3622

Stacked Model Test RMSE: 71.9539

Stacked Model Test MAE: 16.2126

Stacked Model (RF & LSTM combined) Random Forest:

Stacked Model Train MSE: 94.3645

Stacked Model Train RMSE: 13.3587

Stacked Model Train MAE: 1.9406

Stacked Model Test MSE: 2696.4991

Stacked Model Test RMSE: 51.9278

Stacked Model Test MAE: 7.7604

