# Multiple Linear Regression Project

This project demonstrates the application of multiple linear regression on a dataset to predict a target variable. It covers data preprocessing, model training, and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data Description](#data-description)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

The goal of this project is to predict a target variable using multiple linear regression. The project includes data loading, preprocessing, model training, and evaluation using mean squared error.

## Installation

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Data Description

The dataset used in this project is `multiple_linear_regression.csv`. It includes several features and a target variable:

- **Features**: Various input variables used to predict the target.
- **Target**: The output variable that we aim to predict.

## Data Preprocessing

Data preprocessing steps include:

1. **Loading Data**: Load the dataset using pandas.
2. **Handling Missing Values**: Drop rows with missing values to ensure data quality.

## Modeling

We implement multiple linear regression using the following steps:

1. **Splitting Data**: Split the data into training and testing sets using `train_test_split`.
2. **Training the Model**: Fit the `LinearRegression` model on the training data.
3. **Making Predictions**: Predict the target values for the test data.
4. **Evaluating the Model**: Calculate the mean squared error (MSE) to evaluate the model's performance.

## Results

The mean squared error of the model on the test set is used to evaluate the performance. Additionally, a plot is generated to visualize the performance of the model:

- **Green Dots**: Actual test values
- **Red Crosses**: Predicted values by the model

## Conclusion

In this project, we implemented multiple linear regression to predict a target variable. The model was evaluated using mean squared error, and the performance was visualized using a scatter plot.

