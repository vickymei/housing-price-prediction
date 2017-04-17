# housing-price-prediction
The Iowa housing data contains one response variable SalePrice and 79 explanatory variables, of which 36 are quantitative and 43 are categorical, describing almost every aspect of residential homes in Ames, Iowa. There are 1460 instances in training data and 1459 in test data. Through proper data cleaning and variable shrinkage process, the goal of this project is to develop a model to predict the final price of a home with appropriate explanatory variables. Statistical analysis include regression with ridge-lasso, AIC/BIC, Principal Components Analysis and Gradient boosting machine have been used for modeling. These models are evaluated based on the root-mean-square error (RMSE) and running time.


# Conclusion:
GBM/RF and PCA/PLS show better results than first four linear regression do. However, trade off between accuracy and running time is significant, especially for GBM method. It can be observed that regression model takes nearly ten times running time than that of PCA/PLS, with similar RMSE result. Thus, PCA/PLS is recommended for this project. In conclusion, all models have acceptable error ranging from 0.13 to 0.19.

