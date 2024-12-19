# midterm_project

## Overview
This is an individual take-home midterm exam requiring Python code and a summary report. The assignment consists of two parts: updating a Generalized Method of Moments (GMM) model and analyzing credit data to evaluate a bank's credit approval process.

## Part 1: GMM Model Update (20%)
- **Task 1**: Update the GMM model from class to include a non-zero bias term (𝛿) in the instrumental-variable moment expression.
- **Task 2**: Analyze the GMM summary table and test statistics to determine if the industry expert’s claim about bias is statistically justified.

## Part 2: Credit Approval Process (80%)
- **Task 1**: Use “midterm_parttwo.csv” to fit a logistic regression model predicting credit ratings from customer features. Split the data into training (50%) and test (50%) sets. Report confusion matrix, recall, precision, and F1 score.
- **Task 2**: Adjust the model for a stricter approval process (15% approval rate). Calculate the new threshold and update the confusion matrix, recall, precision, and F1 scores.

# Final Exam: Demand Forecasting and Customer Choice Analysis

## Objective
This exam focuses on analyzing transactional data to forecast orders, model customer product choices, characterize demand uncertainties, and apply simulations for better demand forecasting.

### Part 1: Forecasting Distinct Orders
- **Task**: Group transactions by month to calculate the number of unique orders (distinct order codes).  
- **Model**: Develop a predictive model (e.g., time series) to forecast the monthly count of distinct orders.  

### Part 2: Customer Choice Model
- **Task**: Build a classification model to predict customer product selection.  
- **Key Feature**: Incorporate seasonality as an explanatory variable using appropriate encoding (e.g., one-hot encoding).

### Part 3: Quantity Demanded
- **Task**: Use empirical data to characterize the uncertainty of product quantities demanded.  
- **Method**: Utilize empirical quantiles or statistical distributions for each product (e.g., `scipy.stats.mstats.mquantiles`).

### Part 4: Demand Lead Time and Monte Carlo Simulation
- **Task 1**: Characterize demand lead time using empirical quantiles or other statistical methods.  
- **Task 2**: Conduct Monte Carlo simulation to combine uncertainties (forecast, classification, demand lead time).  
- **Task 3**: Analyze simulated data to separate advance demand from urgent demand.  
- **Task 4**: Compare simulated advance demand with actual advance demand in the test set to improve forecast accuracy.

