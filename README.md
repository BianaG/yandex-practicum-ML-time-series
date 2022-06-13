# yandex-practicum-ML-time-series
This project contain a data of taxi orders at airports. The aim of this project is to predict the number of taxi orders for the next hours, to attract more drivers at peak hours.

The libraries and modules that were used in this project are as follows:

Data calculation and analysis libraries
1. pandas
2. numpy
3. math
4. sidetable

A function which breaks the time series into three components: trend, seasonality, and residuals

5. from statsmodels.tsa.seasonal import seasonal_decompose

Libraries for plotting graphs

6. matplotlib
7. seaborn

Splitting data function

8. sklearn - train_test_split

MSE model evaluetion function

9. sklearn - mean_squared_error

Cross-validation functions

10. sklearn - cross val score
11. GridSearchCV

Factory function that wraps scoring functions for use in cross_val_score

12. sklearn - fbeta_score, make_scorer

Regression models

13. sklearn - Lasso
14. sklearn - DecisionTreeRegressor
15. sklearn - RandomForestRegressor

Gradient boosting regression models

16. lightgbm
17. catboost - CatBoostRegressor

A hyperparameter optimization framework to automate hyperparameter search

18. optuna

Ignoring warnings

19. warnings
