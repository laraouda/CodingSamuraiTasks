# CodingSamuraiTasks
-Task 1: House Prediction using Linear Regression 

# 🏠 House Price Prediction Using Linear Regression

This project uses the California Housing dataset to build a machine-learning model that predicts house prices using linear regression techniques. The dataset contains demographic and housing-related data from the 1990 U.S. Census.

## 📦 Features Used
- `longitude`, `latitude`
- `housing_median_age`
- `total_rooms`, `total_bedrooms`
- `population`, `households`
- `median_income`
- `ocean_proximity` (categorical)
- 🛠️ Engineered:
  - `rooms_per_household`
  - `bedrooms_per_room`
  - `population_per_household`


## 🔍 Goals
- Build a regression pipeline with preprocessing (scaling + encoding)
- Engineer new features to improve predictions
- Use regularization (Ridge) to reduce overfitting
- Visualize model performance and data relationships


## 📊 Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn


## 🚀 Model Results
- **Model Used:** Ridge Regression
- **R² Score:** ~0.63
- **MSE:** ~3.57 billion

---

## 📁 Files
- `notebook.ipynb`: Main code notebook
- `housing.csv`: Dataset file
- `README.md`: Project overview


## ✅ Future Improvements
- Try other models (e.g., Random Forest, Gradient Boosting)
- Perform hyperparameter tuning
- Add cross-validation
- Use geospatial clustering for location features

