# Body-Fat-Prediction

This mini project aims to predict body fat percentage in a dataset of 252 individuals using Lasso and Ridge regression models. 
The primary objective is to compare the performance of these two regression techniques in terms of accuracy and error metrics.

I implement Lasso regression and perform hyperparameter tuning using a grid search with cross-validation.
The best alpha (hyperparameter) is determined, and the Lasso model is trained with this optimal alpha.
Model performance is evaluated on both the training and testing datasets, calculating Mean Squared Error (MSE) and R-squared (R2).
Similarly, Ridge regression is implemented and follows the same steps as with Lasso regression.
The best alpha is found using cross-validation, and the Ridge model is trained with this optimal alpha.
Model performance is evaluated using MSE and R2 on the training and testing datasets.

This mini project provides valuable insights into utilizing Lasso and Ridge regression methods for body fat prediction. 
The findings suggest that although the results have been very close to each other, a small difference is observed and the Lasso regression model yields slightly better accuracy by having higher R-squared (R2) and lower mean squared error (MSE) compared to Ridge.
