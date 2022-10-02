# Time-Series-Prediction
A project created to evaluate RMSE score for a given time series dataset with 101 samples.

## Overview 

In this Project, I aim to predict Para 9-13 for the 10th year in the dataset regarding road parameters for various sections using Para 1-10 and previous year data.
I have used XGBoost Regressor model with  250 estimators and also applied the  LASSO (L1) and Ridge (L2) regularization to prevent overfitting. 

Evaluation metric that is used is Root Mean Square Error and overall  calculated Root Mean Square Error for the model which is 9.106. 

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
