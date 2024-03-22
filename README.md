# Customer Classification Horeca or Retail  – XGBoost + K-Fold-CV

In this kernel, we implement XGBoost with Python and Scikit-Learn to classify the customers from two different channels as Horeca (Hotel/Retail/Café) customers or Retail channel (nominal) customers.

The y labels contain values as 1 and 2. We have converted them into 0 and 1 for further analysis.

Trained the XGBoost classifier and found the accuracy score to be 91.67%.

Performed k-fold cross-validation with XGBoost.

## Finding the Most Importance Feature
The most important feature of the Dataset is found using XGBoost.
plot_importance() function in XGBoost is used to achieve the most importace feature of the Design Matrix
