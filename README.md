# SmartPrice Predictor: Used Phone Market Analysis

## Overview

The SmartPrice Predictor project delves into the burgeoning market of used and refurbished smartphones, a sector that has seen significant growth in recent years. An IDC forecast suggests this market could be worth $52.7bn by 2023, with a CAGR of 13.6% from 2018 to 2023. This project, utilizing data provided by ReCell, aims to develop a machine learning-based dynamic pricing strategy for used smartphones, addressing the increased demand for cost-effective alternatives to new devices.

## Project Objectives

- Analyze the used and refurbished smartphone market to understand significant trends and customer preferences.
- Develop a linear regression model to predict the prices of used smartphones accurately.
- Identify key factors that significantly influence the pricing of used smartphones.

## Data Insights

The dataset comprises 3571 records with 15 variables, including brand name, OS, 4G/5G support, release year, and used price. Preliminary analysis indicated the need for data preprocessing, including handling missing values, outlier management, and transformation of categorical variables into dummy variables for model compatibility.

## Exploratory Data Analysis (EDA) Highlights

- Log transformation was applied to address skewness in the price distribution, making the data more amenable to analysis.
- Insights into how physical attributes (e.g., weight and screen size) and technical specifications (e.g., OS type, release year) impact pricing.
- The dominance of Android devices in the used phone market, constituting around 90% of the market share.
- The distribution of features like screen size and camera quality across different brands.

## Model Development and Performance

The project employed a linear regression approach, focusing on factors like brand, operating system, and technical specs to predict used smartphone prices. The model demonstrated excellent performance, explaining approximately 99% of the variation in the data. A thorough validation process confirmed the model's effectiveness, showing no significant overfitting and a high degree of predictive accuracy.

## Assumptions and Validation

- Tests for normality, homoscedasticity, linearity, and independence were conducted to ensure the validity of the model assumptions.
- The Shapiro-Wilk test and plots for homoscedasticity and linearity confirmed that the model meets the necessary statistical assumptions for linear regression.

## Business Insights and Strategic Recommendations

- The model provides a robust framework for pricing used smartphones within approximately 7% of their actual market price, offering a significant tool for businesses like ReCell.
- Recommendations include targeting recent models with minimal usage for resale and leveraging data on new model pricing to optimize the pricing strategy for used devices.
- Opportunities for segment-specific marketing and sales strategies based on the analysis of phone features and brand preferences.

## Conclusion

The SmartPrice Predictor project represents a significant step forward in understanding and capitalizing on the used smartphone market. By leveraging machine learning to analyze market data and predict pricing, businesses can optimize their inventory and pricing strategies to meet consumer demand effectively.

*Note: This project is part of the coursework from University of Austin's post graduate program.*