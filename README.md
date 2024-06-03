# Sea Level Regression Model
This project involves creating a simple regression model to analyze and predict sea levels using historical data. The dataset contains dates and Global Mean Sea Level (GMSL) values. The model is capable of predicting future sea levels, with a particular focus on projections around the year 2050.

# Project Overview
The aim of this project is to create a regression model to study the trend in sea level changes and make future predictions. The project involves:

Loading and preprocessing the sea level dataset.
Training a simple linear regression model.
Evaluating the model's performance using Mean Squared Error (MSE).
Predicting future sea levels, specifically around the year 2050.
Visualizing the results.
Dataset
The dataset used in this project contains two columns:

1. Date: The date of the recorded sea level measurement.
2. GMSL: The Global Mean Sea Level value.

# Model
A simple linear regression model is used in this project. The model is trained and evaluated using the following steps:

Normalize the date feature for numerical stability.
Add a bias term (intercept) to the features.
Split the dataset into training and testing sets.
Train the model using the training set.
Evaluate the model using both training and testing sets.

# Results
Performance Metrics:
1. Training Mean Squared Error: 11.382380840884545
2. Training R-squared: 0.974047815646115
3. Testing Mean Squared Error: 11.162677625774393
4. Testing R-squared: 0.9729358324515338

The high R-squared values indicate that the model explains a large portion of the variance in the sea level data.

# Visualization
A plot is generated showing:

Actual sea level data points.
Predicted sea levels based on the training data.
Future sea level predictions up to the year 2050.
