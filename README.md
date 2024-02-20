## House Price Prediction Project
![img](https://ml-ops.org/img/ml-engineering.jpg)
                                                                          
### Overview

This project aims to predict house prices using the California housing dataset `(housing.csv)`. Various machine learning models have been employed, including Linear Regression, Stochastic Gradient Descent Regressor, Support Vector Regressor, Decision Tree Regressor, and Random Forest Regressor.

### Dataset

The California housing dataset contains housing data for districts in California, with features such as median income, housing median age, average rooms, etc. The target variable is the median house value for California districts.

### Models Used and It's accuracy

|ML Models|Train Accuracy|Test Accuracy|
|---|---|---|
|Linear Regression|64.3|65.9|
|SGD Regressor|64.2|65.5|
|SVR()|-4.6|-5.3|
|DecisionTreeRegressor()| 100.0|67.6|
|RandomForestRegressor()|97.5|82.6|

### Files Included

`main.ipynb`: Jupyter Notebook containing the code for data exploration, model training, and evaluation.

`housing.csv`: California housing dataset.

`requirements.txt`: List of required Python packages.

### Acknowledgments
-The California housing dataset used in this project is sourced from [housing.csv](https://www.kaggle.com/datasets/camnugent/california-housing-prices).


