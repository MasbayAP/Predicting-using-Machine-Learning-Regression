# Conclusion

##After we doing the step by step to build machine learning we can coclude that:
- This data have positively skewed distribution on Overtime Pay and Other Pay,which means there's a outliers on both feautures and we need to handling it.
The reason why we need to handling a outliers because linear regression is very susceptible to outliers. For more explanation you can visit this link: https://medium.com/swlh/how-outliers-can-pose-a-problem-in-linear-regression-1431c50a8e0
or you can search it on google.

- To compare our model we can see it from the R score and RMSE. More high more good for R score, on the other hand if RMSE getting lower then more good the model.
Based on the result of all models, we can conclude that the BEST model are XGBOOST Regressor.

- BUT do not rush in determining our models, because we should be suspicious when one of our models outperformed from other models, it can be OVERFITTING.
Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data.
