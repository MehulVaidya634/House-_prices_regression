
# House_prices_regression

It is a Advanced Problem of Regression which requires advanced techniques of feature engineering, 
feature selection and extraction, modelling, model evaluation, and Statistics.

In this project, we are going to predict the price of a house using its 80 features.

# Goal:
to predict the Saleprice prices for each house.

# Data exploration.
1.training data set has 1460 samples, 80 features,1 target variable.
2.test data has 1459 samples, 80 features.
3.the target variable is SalePrice.

# Feature engineering.
1.the test dataset set and train dataset has same columns with uneven categories, therefore Concatenate both the datasets.

2.Checking for missing values.

![download (1)](https://user-images.githubusercontent.com/95433685/147868315-e3ea1984-8e0e-44ef-b57d-9d1aab18f466.png)

3.dropping columnswith greater 70 percent missing values

4.the dataset has 37 numerical columns and 38 categorical columns.

5.filling  missing values of numerical colums with mean.
and categorical with most frequent element.

6.the target variable is right skewed.

![download (2)](https://user-images.githubusercontent.com/95433685/147868732-ae0b5104-fa9a-4489-84bb-59b6500f4c70.png)

7.Checking corelation of indepent featrues with target variable.

![download (3)](https://user-images.githubusercontent.com/95433685/147868783-b9b1cd61-caaa-4c7e-842f-b45d5af54ea2.png)

8.dropping the features which are having low corelation with target variable.

## Feature scaling.

Normalization.
scaling down the values using minmax scalar as the data does not follow noraml distribution.

## Independent and dependent variables

1.Creating independent and dependent variables.

2.Splitting the dataset into the Training set and Test set.
## Training the model.
1.Fitting the training data.

2.Applying linear regression model on data.

3.predicting the traget variable.

4.Training ridge and lasso resgression.



## Results.

1.The linear regreesion model got the r2_score of 87.80%

2.ridge and lasso regression model gave r2_score of 89.47%.
