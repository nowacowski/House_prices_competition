# House_prices_competition
This notebook shows my approach to Kaggle's 'House Prices Competition' giving result in top 7%

The steps in this notebook are:
- importing data
- dealing with missing data:
    - removing features with big procentage of missing data
    - imputing data (most common for categorical, mean for numerical)
- transforming categorical features into numerical
- exploring correlations and removing strongly correlated features
- fixing skewness of distribution of some features
- normalizing features
- splitting train-test data
- creating and fitting Ridge regression model on train data
- creating model on full train data and fitting on test data
