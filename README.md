Sales Prediction using Multiple Linear Regression
This repository contains a Python-based data science project that predicts sales volumes based on advertising budgets allocated to three different media channels: TV, Radio, and Newspaper.

The project builds a Multiple Linear Regression model to analyze how each advertising platform influences overall sales and provides an inference pipeline to forecast sales for custom budget scenarios.

Project WorkflowData Preprocessing:Imported data using pandas.Cleaned the dataset by removing the unnecessary index column (Unnamed: 0) to isolate the core independent features.Data Splitting:Split the dataset into a Training Set (80%) and a Test Set (20%) using a fixed random_state=42 to ensure consistent, reproducible results.Model Development:Initialized and fitted a LinearRegression model using scikit-learn.Performance Evaluation:Generated target predictions on the test set and evaluated accuracy using Mean Absolute Error (MAE) and the R-squared ($R^2$) metric.Scenario Prediction:Created a quick template cell to pass new, arbitrary budget allocations into the model to predict expected sales.
