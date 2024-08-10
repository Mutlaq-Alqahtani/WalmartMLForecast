# Walmart Sales Prediction Using Machine Learning

# Project Overview


This project aims to predict weekly sales for Walmart stores using machine learning techniques. The dataset includes various features that are believed to influence sales, and both linear and logistic regression models are applied to explore different modeling approaches.

# Dataset

The dataset consists of the following columns:

Store: The store number.
Date: The week of sales.
Weekly_Sales: Sales for the given week.
Holiday_Flag: Indicates whether the week is a special holiday week (1) or not (0).
Temperature: Average temperature in the region.
Fuel_Price: Cost of fuel in the region.
CPI: Consumer Price Index.
Unemployment: Unemployment rate.

# Methodology

The project employs both linear and logistic regression to model and predict weekly sales based on the features provided in the dataset. The following steps were taken:

# Data Preprocessing:

1 -Handling missing values.
2- Encoding categorical variables.
3- Feature scaling.

# Model Training:

1- Splitting the data into training and test sets.
2- Training linear and logistic regression models on the training data.


# Model Evaluation:

1- Evaluating the models using test data.
2- Calculation of evaluation metrics.


# Conclusion

The logistic regression model demonstrates a high R2 score, indicating that a significant portion of the variance in weekly sales can be explained by the model. The mean absolute error and root mean squared error suggest the model's predictive accuracy is strong.
