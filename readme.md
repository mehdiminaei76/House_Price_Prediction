### Overview 

This repository provides an overview of my code for training and testing machine learning models to predict house prices, based on their inforation. 

### Dataset
Boston House Price Dataset from Kaggle is used for this study, and it can be downloaded from this [link](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices). 
The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): 

CRIM: per capita crime rate by town <br>
ZN: proportion of residential land zoned for lots over 25,000 sq.ft. <br>
INDUS: proportion of non-retail business acres per town <br>
CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) <br>
NOX: nitric oxides concentration (parts per 10 million) <br>
RM: average number of rooms per dwelling <br>
AGE: proportion of owner-occupied units built prior to 1940 <br>
DIS: weighted distances to ﬁve Boston employment centers <br>
RAD: index of accessibility to radial highways <br>
TAX: full-value property-tax rate per $10,000 <br>
PTRATIO: pupil-teacher ratio by town <br>
B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town <br>
LSTAT: % lower status of the population <br>
MEDV: Median value of owner-occupied homes in $1000s <br>

### Data Pre-Processing
We first try to replace null values of numerical columns with their average. After that, we convert categorical features into one-hot encoding. 
We then normalize the features. <br>
After that, the data is split into training and test test. 

### ML Models
We look at a few different regression model to predict house prices. Specifically, we use linear regression, random forest, and neural network with one hidden layer. <br>
For each of these models, we consider a range of hyper-parameters and tune them using grid-search.
