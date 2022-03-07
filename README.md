# house-pricing

  In the notebook, you will find how I implemented methods that I have learned upon doing the project. For example, using stacking models together or cross_validation to train ML models. However, while learning the aforementioned techniques, I additionally learned how to tackle skewed data, because linear models prefer normal distributed data rather than right/left skewed one. To deal with skewness, we can use the log function, sqrt function, or box cox transformation.

  Upon thinking of which ML models I could choose, I found out about the robustscaller method which makes models more robust to outliers. For instance, I integrated it with Lasso (L1 regularization) and Elastic Net models. Furthermore, I explored the possibilities of finding the best hyperparameters for ML models - such as random forest or gradient boosting. Yet, there are other methods besides GridSearchCV, such as RandomizedSearchCV (it wasn’t applied in this notebook)

Data was used from the Kaggle competition tab [House prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). 

Using above mentioned techniques, I managed to rank at the top 750th currently out of 4400+ participants.

Here you can find my Kaggle [profile](https://www.kaggle.com/maxi13)
