# GuviProject3
#🏠 House Price Predictor

A machine learning project to predict housing prices in Bengaluru based on key features like area (sqft), number of bedrooms (BHK), bathrooms, and location.


## ⚙️ Features  
- **Data Preprocessing**: handling missing values, encoding categorical variables, outlier removal  
- **Exploratory Data Analysis (EDA)**: histograms, scatter plots, bar charts, correlation heatmap  
- **Feature Engineering**: BHK extraction, price per sqft calculation, location grouping  
- **Model Building**: Linear Regression, Lasso, Ridge regression using Scikit-Learn pipelines  
- **Model Evaluation**: R² score 
- **Real-time Prediction**: input house details and get predicted price  

---

## 📊 Dataset  
- **Source:** Bengaluru House Price Dataset  
- **Features:**  
  - `location` – location of the property  
  - `total_sqft` – total area in square feet  
  - `bath` – number of bathrooms  
  - `bhk` – number of bedrooms (derived from size column)  
  - `price` – target variable (in Lakhs)  

---

## 🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:**  
  - Data Processing → Pandas, NumPy  
  - Visualization → Matplotlib, Seaborn  
  - Machine Learning → Scikit-Learn  

---

## 🚀 Implementation Steps  

### 🔹 Data Cleaning & Preprocessing  
- Handle missing values (mode/median imputation)  
- Encode categorical features (OneHotEncoding)  
- Remove outliers (based on sqft per BHK and price per sqft)  

### 🔹 Exploratory Data Analysis (EDA)  
- Price distribution  
- Area vs Price  
- BHK vs Price  
- Location analysis  
- Correlation heatmap  

### 🔹 Model Building  
- Linear Regression  
- Lasso Regression  
- Ridge Regression  
- Pipelines with scaling & encoding  

### 🔹 Model Evaluation  
- R² score comparison  
- Test vs Predicted price visualization

### 📈 Results

The Linear Regression and Ridge Regression models performed better compared to Lasso.

Location, area, and number of rooms strongly influence price.

Example Prediction:

Input: 1200 sqft, 3 BHK, 2 Bath, Location = Whitefield

Output: 54.64868614337528 (Lakhs)
