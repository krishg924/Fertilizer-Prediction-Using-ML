# 🌱 Fertilizer Prediction Using ML

This project predicts the **top 3 recommended fertilizers** for a given crop based on environmental and soil parameters using advanced machine learning techniques.

---

## 📌 Problem Statement

Given features like:

- 🌡️ Temperature  
- 💧 Humidity  
- 🌾 Soil nutrients (Nitrogen, Phosphorous, Potassium)  
- 🌱 Crop Type  
- 🌍 Soil Type  

...the goal is to predict the **most suitable fertilizers**, ranked by effectiveness.

---

## 🔍 Key Features

- ✅ Multi-class, multi-label ranking problem  
- 📊 MAP@3 used for evaluation  
- 🧪 Models compared: LightGBM, XGBoost, CatBoost, Random Forest  
- 🧠 Hyperparameter tuning via **Optuna**  

---

## 🧠 ML Approach

1. **Data Preparation**
   - Label encoding
   - Feature distribution analysis
   - Handling missing values (if any)

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Count plots for categorical features

3. **Modeling**
   - LightGBM with 'multiclass' objective  
   - Comparison with XGBoost, CatBoost, Random Forest  
   - MAP@3 as primary evaluation metric  

4. **Hyperparameter Optimization**
   - Optuna for automated parameter search  
   - Best model: LightGBM

---

## 📁 Tech Stack

- **Languages:** Python  
- **Libraries:** pandas, numpy, scikit-learn, xgboost, lightgbm, optuna
- **Visualization:** seaborn, matplotlib
- **Evaluation Metric:** MAP@3

---
