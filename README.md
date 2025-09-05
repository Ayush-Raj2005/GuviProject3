# GuviProject3
🏠 House Price Predictor

A machine learning project to predict housing prices in Bengaluru based on key features like area (sqft), number of bedrooms (BHK), bathrooms, and location.

📌 Problem Statement

Estimating house prices manually can be inconsistent and error-prone. This project uses Scikit-Learn regression models to automate the prediction process and deliver more reliable and data-driven results.

Key Question:
👉 How can we build a regression model to predict house prices based on housing features?

🎯 Objectives & Deliverables

🧹 Cleaned dataset with missing values handled, encoded locations, and outliers removed

📊 EDA visualizations (histograms, scatterplots, heatmaps)

🤖 Regression models (Linear, Ridge, Lasso) trained & compared

📈 Performance evaluation using R² and MSE

🏠 Prediction pipeline for new house listings

⚙️ Features

Data preprocessing (null handling, feature engineering, outlier removal)

Price distribution & correlation analysis

OneHotEncoding for categorical features

Machine learning pipelines with scaling & regression

Real-time prediction for new house details

📊 Dataset

Source: Bengaluru House Price Dataset

Features:

location → property location

total_sqft → total area in square feet

bath → number of bathrooms

bhk → number of bedrooms (derived from size)

price → target variable (in Lakhs)

🛠️ Tech Stack

Programming Language: Python 

Libraries:

Data Processing → Pandas, NumPy

Visualization → Matplotlib, Seaborn

Machine Learning → Scikit-Learn

🚀 Implementation Steps

1.Data Cleaning & Preprocessing

 -Filled missing values (mode, median)

 -Converted sqft ranges → numeric

 -Extracted bhk from size

 -Grouped rare locations as "other"

2.Outlier removal (sqft per BHK & price per sqft)

 -Exploratory Data Analysis (EDA)

 -Price distribution plot

 -Area vs Price scatterplot

 -Average price per BHK bar chart

 -Correlation heatmap

3.Model Building

 -Linear Regression ✅

 -Ridge Regression 📐

 -Lasso Regression 🔒

4.Evaluation

 -R² Score comparison

 -Mean Squared Error (MSE)

 -Predicted vs Actual price check
