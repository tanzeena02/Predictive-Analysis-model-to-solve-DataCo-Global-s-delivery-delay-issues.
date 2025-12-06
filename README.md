# Afroza Tanzeena's Portfolio

# [Project 1: Predictive Analysis model for resolving Supply Chain issues](https://tanzeena02.github.io/Predictive-Analysis-model-to-solve-DataCo-Global-s-delivery-delay-issues./)

# I developed a machine learning model for my master's course in Business Intelligence to predict delivery delays for DataCo Global. Built a machine learning classification model to predict late deliveries for DataCo Global using Python. Conducted data cleaning, normalization, EDA, and correlation analysis to identify key delay factors. Implemented Logistic Regression and Random Forest models, achieving high accuracy but indicating overfitting and the need for regularization. Insights revealed that shipment mode and product category were major contributors to delays. Recommended operational strategies—including premium shipping, inventory optimization, and ERP-integrated delay alerts—to improve supply chain efficiency and reduce late deliveries.

# Business Problem: 
DataCo Global was experiencing high delivery delay rates (54%), resulting in customer dissatisfaction, order cancellations, and lost sales. The company needed a way to predict late deliveries before they occurred and understand the key factors contributing to delays.

# Objective: 
Build a machine learning model to classify whether an order will be on-time or late, and generate data-driven recommendations to improve supply chain efficiency.

# Data Overview
Source: Kaggle DataCo Supply Chain dataset
Size: 180,519 records, 53 variables
Data contained product, customer, order, shipment, and delivery attributes

# Methods & Approach
1. Data Cleaning & Preprocessing
*Removed irrelevant or high-noise columns (customer info, product codes, zip codes, etc.)
*Handled redundancy and normalized data
*Encoded categorical variables for ML compatibility

# Exploratory Data Analysis (EDA)
*Identified categories with highest delay risk (e.g., shoes/apparel)
*Analyzed delay distribution
*Visualized top 10 product categories with late deliveries
*Built a correlation heatmap to identify influential variables: 
Shipment Mode
Product Category
Delivery Status

#Machine Learning Model Development

Split dataset into 60% training / 40% testing.
Implemented two classification models:

🔹 Logistic Regression
🔹 Random Forest Classifier

Both models showed high accuracy, but results indicated overfitting, suggesting a need for regularization or testing additional models.

# Key Findings

Shipment Mode influenced delivery risk by ~40%.

Standard shipping had significantly higher late delivery probability.

Footwear/apparel categories were most affected by delays.

Over 50% of all deliveries were late → major operational problem.

# Proposed Solutions

Offer premium (First-Class) shipping options for improved on-time performance.

Increase inventory or add seasonal warehouse space for high-risk categories (e.g., shoes).

Implement an ERP-integrated delay prediction system to alert teams before late deliveries occur.

Use ML predictions to optimize dispatch planning and workforce allocation.

# Business Impact

The predictive system and recommendations could:

Increase on-time deliveries

Improve customer satisfaction

Reduce cancellations

Boost revenue

Improve supply chain visibility end-to-end


