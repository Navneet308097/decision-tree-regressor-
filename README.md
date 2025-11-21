

# Decision Tree Regressor

This project demonstrates the use of a **Decision Tree Regressor** to predict continuous numerical values. The model learns patterns in the data by splitting it into smaller and more homogeneous groups, ultimately forming a complete regression tree.

## Overview

A Decision Tree Regressor is a supervised learning algorithm used for regression tasks.
It works by recursively dividing the dataset based on feature values to minimize prediction error. Each split aims to create regions where target values are as similar as possible.

## Features

* Builds a regression tree for predicting continuous outcomes
* Captures non-linear relationships effectively
* Easy to interpret through its tree structure
* Handles both numerical and categorical features
* No need for feature scaling

## Description

The model selects the best feature and threshold at each node to reduce impurities such as variance or mean squared error.
It continues splitting until stopping criteria are reached, resulting in leaf nodes that store predicted values.

The final output is a fully constructed **regression tree** that shows:

* Decision nodes based on feature thresholds
* Leaf nodes containing predicted numerical values
* A structured path explaining how predictions are made

This project highlights how Decision Tree Regression can provide clear, interpretable predictions for real-world continuous data problems.

