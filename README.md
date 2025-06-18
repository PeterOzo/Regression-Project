# Regression-Project

## Analyzing Factors Influencing Heart Disease Severity using Multiple Linear Regression

📌 Project Overview

This project investigates the contributing factors to heart disease severity by applying Multiple Linear Regression (MLR) techniques to a clinical dataset. Developed as part of the graduate course DATA-612: Advanced Data Science Applications, this analysis aims to identify key health indicators that significantly predict heart disease severity. The broader objective is to support early detection and effective management of cardiovascular diseases through data-driven insights.


🎯 Objectives
The core research questions guiding this study are:

Which health indicators are the most significant predictors of heart disease severity?

How do categorical variables such as sex and chest pain type influence prediction outcomes?

What is the relationship between continuous variables like cholesterol, blood pressure, and maximum heart rate with the severity of heart disease?

🗂 Dataset Information
Name: Heart Failure Prediction Dataset

Source: Kaggle Dataset by fedesoriano

Size: 918 observations × 12 variables

Variables:

Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, HeartDisease

The dataset is derived from multiple combined heart disease datasets, including Cleveland, Hungarian, Switzerland, Long Beach VA, and Stalog (Heart), originally sourced from the UCI Machine Learning Repository.

🧪 Methodology
The analysis follows a structured statistical workflow:

Data Cleaning & Preparation

Handled missing values and duplicates

Recoded categorical variables

Standardized continuous variables

Exploratory Data Analysis (EDA)

Descriptive statistics and visualizations

Correlation analysis and multicollinearity checks (VIF)

Model Building

Multiple linear regression to assess the influence of independent variables

Backward elimination for variable selection

Assumption testing: normality, homoscedasticity, multicollinearity

Model Diagnostics

Residual analysis

Durbin-Watson test for autocorrelation

Model performance metrics

📊 Key Features
📈 Interactive Visualizations using plotly and ggplot2

📉 Regression Diagnostics using olsrr, car, and lmtest

🧠 Interpretability Tools including correlation heatmaps and variance inflation factor (VIF) analysis

🗃️ Dynamic HTML Output with collapsible code blocks and a floating table of contents for easy navigation

💡 Expected Outcomes
The final model aims to:

Highlight statistically significant predictors of heart disease

Offer interpretable results for clinicians and health professionals

Demonstrate how statistical modeling can support public health decisions

🛠️ Technologies Used
R Language

RMarkdown / knitr

Libraries: tidyverse, GGally, car, lmtest, olsrr, corrplot, patchwork, plotly, DT
