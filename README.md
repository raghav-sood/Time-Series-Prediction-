# Time-Series-Prediction
A project created to evaluate RMSE score for a given time series dataset with 101 samples.

## Overview 

Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values. While regression analysis is often employed in such a way as to test relationships between one or more different time series, this type of analysis is not usually called "time series analysis", which refers in particular to relationships between different points in time within a single series.

In this Project, I aim to predict Para 9-13 for the 10th year in the dataset regarding road parameters for various sections using Para 1-10 and previous year data.I have used XGBoost Regressor with  250 estimators and also applied the regularisation for removing overfitting.

Calculated overall Root Mean Square Error for the model which is 9.106. 

## Model 
XGBoost Regressor.

## Outputs

### Samples , Comparisons and Graphs Directory
A directory named samples which consists of segregated pre processed samples of 10 years in .csv format.

A directory named comparisons which include comparison of each output for Para 9-13 where:
1) First row denotes the **Actual** output
2) Second row denotes the **Predicted** output
3) Third row denotes the **RMSE Error**

A directory named graphs which include comparison of actual vs predicted in graphical format for Para 9-13.

### RMSE
The overall Root Mean Square Error for the model which is 9.106.
