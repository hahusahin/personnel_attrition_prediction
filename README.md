# Employee Attrition Prediction

### Goal
Using the extensive data that Human Resources team collected in a business, my goal is to develop a model that could predict which employees are more likely to quit

### Data Description
* The dataset has a total of 1470 datapoints with 33 variables.

* Target variable is the binary variable of loan status.

### Exploratory Data Analysis - Modeling
* Missing values are detected and filled, unnecesarry features are deleted

* Target variable's distribution is examined

* Relationship between target variable and the features are examined and some observations are made

* Scaling is applied.

* Logistic Regression, XGBoost and Artificial Neural Network (ANN) models are tried.

* As the data is imbalanced, I tried to minimize the false negatives because the most important employees that we should concentrate on is the ones who actually left but the model predicted as stayed. So, Recall is taken as the main metric and overall of 85% recall obtained.

### Project Files
* Human_Resources.csv - Data set
* Personnel_Attrition_Prediction.ipynb - Project Notebook

### Libraries Used
* pandas, numpy
* matplotlib, seaborn
* sklearn, xgboost
* keras, tensorflow
