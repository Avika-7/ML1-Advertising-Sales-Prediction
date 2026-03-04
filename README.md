# PROJECT 1: Advertising Sales Prediction

## Overview
This project analyzes the impact of advertising expenditure (TV, Radio, Newspaper) on product sales using Linear Regression.

## Objectives
- Identify correlation between advertising mediums and sales
- Build a multiple linear regression model
- Evaluate model performance
- Analyze impact of feature removal
- Study effect of feature normalization

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Key Findings
- TV advertising has the strongest correlation with Sales (~0.90)
- Removing TV significantly reduces prediction accuracy
- Feature normalization does not significantly affect Linear Regression performance

## Model Used
- Multiple Linear Regression
- Train/Test Split (80/20)
- MinMaxScaler (for normalization experiment)

## Sample Prediction
Input:
TV = 200, Radio = 40, Newspaper = 50

Predicted Sales:
19.79 units

## Conclusion
TV advertising is the most influential feature for predicting sales. The model demonstrates strong predictive performance with multiple features.
