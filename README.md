# TensorFlow-TimeSeries-LSTM-Google_Market_price_Prediction
Predicting the Google Market price using LSTM and TimeSeries Modelling
1) The Dataset is downloaded from Yahoo Finance
2) Data Preprocessing and Data Standardisation is done
3) with the previous 60 days value, the current day value is predicted
4) so the data is splitted into batches each batch has 60 rows in x_train and one value for Y_train
5) same were applied to x_test and y_test.
6) Transform the data back using inverse_transform.
7) Plotting for the real and the predicted value is done.
