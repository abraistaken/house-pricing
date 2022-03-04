# house-pricing

  In notebook you will find how I implemented methods which I wanted to learn. For example stacking models together and using cross_validation to train ML models. However while learning before mentioned techniques, I learned additionally how to tackle skewed data, because linear models likes more distributed data rather than right/left skewed one. To tackle skewness we can use log function, sqrt function or box cox transformation. While thinking of which ML models I could choose, I found out about robustscaller method which makes models more robust to outliers, for example I implemented it with Lasso (R1 regularization) and Elastic Net models. Additionally explored posabilities of finding best hyper parameters for ML models, such as random forest or gradientboosting, however were are other methods beside GridSearchCV, for example RandomizedSearchCV (it wasnt implemented in this notebook)
  
  Data was used from kaggle competition tab [House prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques), using above mentioned techniques I managed to rank at top 750 position out of 4400+
  
  Here you can find my kaggle profile [profile](https://www.kaggle.com/maxi13)
