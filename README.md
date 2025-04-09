# Supermarket Sales Analysis

This project analyzes sales data from a supermarket chain with three different branches over a three-month period. The analysis includes exploratory data visualization, data preprocessing, and predictive modeling using Linear Regression and Random Forest Regressor.

## Dataset Information

### Source
- **Kaggle Dataset:** [Supermarket Sales](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales/data)

### Context
The growth of supermarkets in most populated cities is increasing and market competitions are also high. The dataset contains historical sales of a supermarket company recorded in 3 different branches for 3 months. This dataset is suitable for predictive data analytics methods.

### Attribute Information
- **Invoice id:** Computer generated sales slip invoice identification number
- **Branch:** Branch of supercenter (3 branches are available identified by A, B and C)
- **City:** Location of supercenters
- **Customer type:** Type of customers (Members for customers using member card and Normal for without member card)
- **Gender:** Gender type of customer
- **Product line:** General item categorization groups:
  - Electronic accessories
  - Fashion accessories
  - Food and beverages
  - Health and beauty
  - Home and lifestyle
  - Sports and travel
- **Unit price:** Price of each product in $
- **Quantity:** Number of products purchased by customer
- **Tax:** 5% tax fee for customer buying
- **Total:** Total price including tax
- **Date:** Date of purchase (Record available from January 2019 to March 2019)
- **Time:** Purchase time (10am to 9pm)
- **Payment:** Payment used by customer for purchase (3 methods - Cash, Credit card and Ewallet)
- **COGS:** Cost of goods sold
- **Gross margin percentage:** Gross margin percentage
- **Gross income:** Gross income
- **Rating:** Customer stratification rating on their overall shopping experience (Scale of 1 to 10)

## Project Overview

This project includes:
1. Data cleaning and preprocessing
2. Exploratory data analysis with visualizations
3. Feature engineering (time categorization, one-hot encoding)
4. Statistical tests for distribution analysis
5. Predictive modeling using:
   - Linear Regression
   - Random Forest Regressor with hyperparameter tuning

## Key Visualizations
- Sales trends over time by customer type
- Sales by city and payment method
- Product line sales by time of day
- Daily sales patterns throughout the week

## Models Evaluation
The project compares the performance of Linear Regression and Random Forest models using metrics such as RMSE and R².

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy


## Acknowledgements
Thanks to the dataset provider on Kaggle and all who take time and energy to perform analyses with this dataset.
