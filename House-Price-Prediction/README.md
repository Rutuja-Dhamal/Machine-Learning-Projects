# 🏠 House Price Prediction - Machine Learning Project

The **House Price Prediction** project applies regression techniques in machine learning to predict the selling price of a house based on various features like number of rooms, square footage, location, and more. It serves as a practical implementation of supervised learning and provides insights into real-world regression modeling, data preprocessing, and feature engineering.

---

## 📖 Project Overview

This project focuses on building a regression model that can accurately predict housing prices using structured data. It begins with data exploration and visualization, followed by extensive feature preprocessing and model selection.

The dataset typically includes key attributes such as area, number of bedrooms, bathrooms, location, and other influential real estate factors. By the end of this project, a trained regression model is capable of estimating prices with reasonable accuracy, demonstrating the power of data-driven decision-making in real estate analytics.

---

## 🏡 Dataset Information

- **Source**: Kaggle / Custom Cleaned Housing Dataset
- **Features** may include:
  - Total square feet
  - Number of bedrooms (BHK)
  - Number of bathrooms
  - Location (encoded)
  - Area type
  - Availability
- **Target**: Price of the house (in Lakhs or Rupees)

---

## ⚙️ Technologies & Tools Used

- Python
- NumPy & Pandas – data handling
- Matplotlib & Seaborn – data visualization
- Scikit-learn – ML algorithms and evaluation
- Jupyter Notebook – for development and documentation

---

## 🔍 Project Workflow

1. **Data Loading & Cleaning**
   - Load dataset using Pandas
   - Handle missing values, duplicates, and outliers
   - Convert categorical features using encoding

2. **Exploratory Data Analysis (EDA)**
   - Visualize distribution of prices
   - Correlation heatmaps
   - Box plots and scatter plots

3. **Feature Engineering**
   - One-hot encoding for categorical variables
   - Feature scaling
   - Dimensionality reduction (if applicable)

4. **Model Building**
   - Train-Test split
   - Trained models:
     - Linear Regression
     - Lasso Regression
     - Decision Tree Regressor
     - Random Forest Regressor

5. **Model Evaluation**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score

6. **Prediction & Results**
   - Tested model on unseen data
   - Compared actual vs predicted prices
   - Visualized prediction errors

---

## 📈 Results

- Best performing model achieved **high R² scores** and low error metrics.
- The model was able to generalize well on test data.
- Price prediction trends followed the expected distribution based on area and location.

---


