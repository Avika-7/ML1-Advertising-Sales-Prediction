# Machine Learning Projects Repository

This repository contains multiple machine learning and data analysis projects focused on real-world datasets. Each project demonstrates different techniques such as regression, clustering, and classification.

--------------------------------------------------

PROJECT 1: Advertising Sales Prediction

Overview:
This project analyzes the impact of advertising expenditure (TV, Radio, Newspaper) on product sales using Linear Regression.

Objectives:
- Identify correlation between advertising mediums and sales
- Build a multiple linear regression model
- Evaluate model performance
- Analyze impact of feature removal
- Study effect of feature normalization

Technologies Used:
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

Key Findings:
- TV advertising has the strongest correlation with Sales (~0.90)
- Removing TV significantly reduces prediction accuracy
- Feature normalization does not significantly affect Linear Regression performance

Model Used:
- Multiple Linear Regression
- Train/Test Split (80/20)
- MinMaxScaler (for normalization experiment)

Sample Prediction:
Input:
TV = 200, Radio = 40, Newspaper = 50  
Predicted Sales:
19.79 units

--------------------------------------------------

PROJECT 2: Facebook Live Sellers Engagement Analysis

Overview:
This project analyzes engagement metrics of Facebook Live sellers and applies K-Means clustering to identify engagement patterns.

Objectives:
- Analyze impact of posting time on reactions
- Study correlation between reactions, comments, and shares
- Apply K-Means clustering
- Use Elbow Method to determine optimal clusters
- Analyze engagement across post types

Technologies Used:
- Python
- Pandas
- Matplotlib
- Scikit-learn

Key Insights:
- Highest reactions observed around 7 PM
- Weak positive correlation between reactions and comments/shares
- Optimal clusters found using Elbow Method (k=3)
- Video posts show significantly higher engagement

Machine Learning Techniques:
- K-Means Clustering
- Elbow Method
- Correlation Analysis

--------------------------------------------------

PROJECT 3: Wine Quality Prediction

Overview:
This project analyzes the Red Wine Quality dataset and builds machine learning models to predict wine quality based on physicochemical properties.

Dataset Features:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

Target Variable:
Quality (score from 0 to 10)

Analysis:
- Studied correlations between features and quality
- Identified important factors like alcohol and acidity
- Compared feature impact on prediction

Models Used:
- Decision Tree Classifier
- Random Forest Classifier

Technologies:
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

--------------------------------------------------

OVERALL SKILLS DEMONSTRATED

- Data Analysis and Visualization
- Supervised Learning (Regression, Classification)
- Unsupervised Learning (Clustering)
- Feature Engineering and Correlation Analysis
- Model Evaluation

--------------------------------------------------
