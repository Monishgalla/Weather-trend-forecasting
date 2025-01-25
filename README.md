Time Series Forecasting Project

Project Overview

This project involves forecasting weather data using time series analysis techniques. The dataset contains various weather-related attributes such as temperature, humidity, wind speed, and precipitation. The goal is to build and evaluate forecasting models that utilize the lastupdated feature as the time variable.

Key Objectives

Perform data cleaning and preprocessing to prepare the dataset for analysis.

Conduct Exploratory Data Analysis (EDA) to uncover trends, correlations, and patterns.

Build forecasting models to predict weather attributes and evaluate their performance using metrics such as MAE, MSE, and R².

Visualize the results and provide insights through a structured report or presentation.

Dataset Description

The dataset contains the following key columns:

temperature_celsius: Temperature in Celsius.

humidity: Humidity level.

precip_mm: Precipitation in millimeters.

wind_mph: Wind speed in miles per hour.

lastupdated: Timestamp indicating the last data update.

Data Cleaning

Converted the lastupdated column to datetime format and set it as the index.

Identified and dropped categorical columns that are not relevant for numerical analysis.

Handled missing values, ensuring the dataset is complete and consistent.

Exploratory Data Analysis (EDA)

Trends Analysis:

Visualized temperature and precipitation trends over time.

Correlation Analysis:

Generated a heatmap to identify relationships between numerical variables.

Descriptive Statistics:

Summarized key statistics such as mean, median, and standard deviation for the weather attributes.

Model Building

Linear Regression Model

Objective: Predict temperature based on time.

Process:

Split the data into training and testing sets.

Trained a linear regression model using the temperature_celsius as the target variable.

Performance Metrics:

Mean Absolute Error (MAE): 0.0021

Mean Squared Error (MSE): 6.90e-06

R² Score: 0.98

Long Short-Term Memory (LSTM) Model

Objective: Capture complex temporal patterns for better predictions.

Process:

Reshaped data for LSTM compatibility.

Built and trained an LSTM model using the TensorFlow library.

Performance Metrics:

MAE, MSE, and R² metrics were evaluated to validate the model’s performance.

Visualization

Time series plots showing actual vs. predicted values.

Bar charts and scatter plots for performance metrics.

Heatmaps for correlation analysis.

Insights and Conclusion

The dataset displayed clear seasonal trends in temperature and precipitation.

Linear regression provided a simple yet effective baseline model with high accuracy.

The LSTM model further improved performance by capturing non-linear temporal dependencies.

Mean Absolute Error and R² values indicated strong model reliability for forecasting.

Deliverables

A detailed report in the form of a PowerPoint presentation with:

Data cleaning and EDA processes.

Model building and evaluation.

Visualizations and insights.

Code and documentation uploaded to a GitHub repository.

How to Run the Project

Clone the repository:

git clone <repository_link>

Install the required dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook for EDA and model training.

View the results in the generated report or presentation.

Future work:

Experiment with additional advanced forecasting models such as ARIMA and Prophet.

Incorporate external weather datasets for improved accuracy.

Develop a web-based dashboard for real-time weather forecasting.

