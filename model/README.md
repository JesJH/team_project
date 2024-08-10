# Team Project - 2

### Video link

Kateryna Gogina https://drive.google.com/file/d/1Mf_1ckG_bjio2REA2NCYTYtKZy-3ahVA/view?usp=sharing

### Retail Data Analysis and Prediction

## Overview

This project involves analyzing and predicting retail transaction data. The primary goal is to predict the Amount spent in transactions using various machine learning models, including Linear Regression, Random Forest, and Gradient Boosting.

The project leverages several libraries for data manipulation, visualization, and machine learning, including pandas, numpy, matplotlib, scikit-learn, and stats models.

## Table of Contents

1. Project Structure
2. Data Description
3. Setup and Installation
4. Usage
5. Model Evaluation
6. Feature Importance
7. Results
8. Conclusion

### Project Structure

The project contains the following files:

- new_retail_data.csv: The dataset used for analysis and prediction.
- README.md: This file.

### Data Description

The dataset contains various attributes related to retail transactions, including:

- Transaction_ID: Unique identifier for each transaction.
- Customer_ID: Unique identifier for each customer.
- City, State, Country: Geographical information of customers.
- Age, Gender, Income: Demographic information of customers.
- Customer_Segment: The segment to which a customer belongs.
- Date, Year, Month, Time: Temporal information related to transactions.
- Total_Purchases: Total number of purchases by a customer.
- Amount: The amount spent in a transaction (target variable).
- Total_Amount: Total amount spent by a customer.
- Product_Category, Product_Brand, Product_Type: Information about the products.
- Feedback, Shipping_Method, Payment_Method, Order_Status: Various categorical attributes related to transactions.
- Ratings: Customer ratings for transactions.
- Products: Details of the products purchased.

Installation

1. Clone the repository:

git clone https://github.com/yourusername/retail-data-analysis.git
cd retail-data-analysis

2. Install the required libraries:

pip install pandas matplotlib numpy scikit-learn statsmodels

3. Place the new_retail_data.csv file in the data/ directory.

### Usage

1. Run the script:

python retail_data_analysis.py

2. The script performs the following tasks:

- Loads and cleans the dataset.
- Performs feature engineering, including creating age categories.
- One-hot encodes categorical variables.
- Splits the data into training and testing sets.
- Scales the features using StandardScaler.
- Builds and evaluates three machine learning models:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Plots the results of model predictions and feature importance.
- Observe the model evaluation metrics and visualizations.

### Model Evaluation

# Linear Regression

- Mean Absolute Error (MAE): 49.01
- R-squared: 0.7756

# Random Forest Regressor

- Mean Absolute Error (MAE): 0.0143
- R-squared: 0.9999
- Time Taken: 376 seconds

# Gradient Boosting Regressor

- Mean Absolute Error (MAE): 7.68
- R-squared: 0.9942

### Feature Importance

The script plots the feature importance scores for the Random Forest Regressor, which provides insights into the most influential features in predicting the transaction amount.

### Results

The Random Forest Regressor outperformed the other models, achieving near-perfect performance with an R-squared value of 0.9999. The Gradient Boosting Regressor also performed well, while Linear Regression had a comparatively lower R-squared value.

### Conclusion

This project demonstrates the process of data analysis and prediction using various machine learning techniques. It highlights the importance of feature engineering, data preprocessing, and model evaluation in building effective predictive models.
