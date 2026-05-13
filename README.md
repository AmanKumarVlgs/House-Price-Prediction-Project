# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning techniques on the Bengaluru Housing Dataset.  
The project includes complete data preprocessing, feature engineering, visualization, outlier treatment, model building, evaluation, and ensemble learning.

The objective of this project is to build a robust regression model capable of estimating house prices based on multiple house-related features such as:
- Area Type
- Location
- Total Square Feet
- Number of Bathrooms
- Number of Balconies
- BHK Count
- Price Per Square Feet

---

# 🚀 Features of the Project

✅ Data Cleaning  
✅ Missing Value Treatment  
✅ Feature Engineering  
✅ Outlier Detection & Removal  
✅ Exploratory Data Analysis (EDA)  
✅ Correlation Analysis  
✅ Feature Encoding  
✅ Feature Scaling  
✅ Model Training  
✅ Model Evaluation  
✅ Ensemble Learning using Stacking Regressor  

---

# 📂 Dataset

Dataset Used:
- Bengaluru House Price Dataset

Main features used:
- `area_type`
- `location`
- `total_sqft`
- `bath`
- `balcony`
- `bhk`
- `price`

---

# 🛠️ Technologies Used

## Programming Language
- Python

## Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost

---

# 📊 Exploratory Data Analysis

The project performs:
- Distribution Analysis
- Outlier Analysis
- Correlation Heatmaps
- Bivariate Analysis
- Feature Relationship Visualization

Visualization techniques used:
- Histograms
- Boxplots
- Regression Plots
- Heatmaps
- Bar Charts

---

# ⚙️ Data Preprocessing

The preprocessing pipeline includes:

## Missing Value Handling
- Numerical columns filled using median values
- Categorical columns handled using mode values

## Feature Engineering
New features created:
- `bhk`
- `price_per_sqft`
- `total_rooms`
- `bath_per_bhk`
- `balcony_per_bhk`

## Encoding
Categorical features encoded using:
- One Hot Encoding

## Scaling
Feature scaling performed using:
- MinMaxScaler

---

# 📈 Models Used

The following Machine Learning algorithms were trained and compared:

| Model |
|---|
| Linear Regression |
| Ridge Regression |
| Decision Tree Regressor |
| XGBoost Regressor |
| LightGBM Regressor |
| CatBoost Regressor |
| Stacking Regressor Ensemble |

---

# 🧠 Ensemble Learning

A Stacking Regressor ensemble model was implemented using:

### Base Models
- CatBoost
- LightGBM
- Linear Regression

### Meta Model
- Ridge Regression

This ensemble achieved the best prediction performance.

---

# 📉 Evaluation Metrics

The models were evaluated using:

- R² Score
- Adjusted R² Score
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

---

# 📌 Machine Learning Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
EDA & Visualization
       ↓
Feature Engineering
       ↓
Outlier Treatment
       ↓
Encoding & Scaling
       ↓
Train-Test Split
       ↓
Model Building
       ↓
Model Evaluation
       ↓
Ensemble Learning
       ↓
Final Prediction
