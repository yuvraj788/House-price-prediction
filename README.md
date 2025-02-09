# 🏡 House Price Prediction

## 📌 Project Overview
This project aims to predict real estate prices using advanced machine learning models based on key housing features. It involves thorough data preprocessing, insightful visualizations, and rigorous model evaluation to determine the most accurate prediction approach.

## 🔍 Steps in the Project

### 1️⃣ Data Preprocessing 🛠️
- 📌 Dropped unnecessary columns: `id`, `date`, `sqft_lot`, `sqft_lot15`.
- ✅ Checked and handled missing values.
- 🔄 Encoded categorical variables (`waterfront`, `condition`) into numerical values.

### 2️⃣ Exploratory Data Analysis (EDA) 📊
- 📈 **Scatter Plots:** Analyzed relationships between `sqft_living` and house prices.
- 🔥 **Heatmap:** Visualized correlations between different features.
- 🌍 **Geospatial Map:** Showcased house price distribution based on latitude and longitude.
- 📊 **Radial Bar Plot:** Highlighted average values of key features.
- 📉 **Count Plot:** Examined the distribution of floors.

### 3️⃣ Train-Test Split 🎯
- 🔹 Split the dataset into training (80%) and testing (20%) sets.
- 🔹 Applied log transformation to `price` to normalize distribution.

### 4️⃣ Model Implementation 🤖
- Applied various machine learning models:
  - 📏 **Linear Regression**
  - 🌳 **Decision Tree Regressor**
  - 🌲 **Random Forest Regressor**
  - 🚀 **XGBoost Regressor**
  - ⚡ **LightGBM Regressor**
- Evaluated models using RMSE and R² Score.

### 5️⃣ Best Performing Model 🏆
- Based on RMSE and R² score, **XGBoost Regressor** 🚀 and **LightGBM Regressor** ⚡ delivered the most accurate predictions with the lowest error.

## 🎯 Conclusion & Results
- ✅ The project successfully predicted house prices with high accuracy.
- 🔍 Feature importance analysis helped identify key influential factors.
- 🏆 **XGBoost and LightGBM** emerged as the best-performing models, minimizing prediction errors effectively.



🎯 *This project provides valuable insights into the real estate market and demonstrates the power of machine learning in price prediction.* 🚀
