# California-Housing-Price-Prediction
Machine Learning project predicting California housing prices using regression models (Linear, Ridge, Lasso, ElasticNet, SVR, MLP, Gradient Boosting). Includes full code, report, and presentation.

# 🏡 California Housing Price Prediction

**Author:** Muhammad Osama  
**Course:** Data Science & Machine Learning (Fanshawe College)  
**LinkedIn:** [muhammad-osama-872328202](https://www.linkedin.com/in/muhammad-osama-872328202)  
**GitHub:** [MuhammadOsama380](https://github.com/MuhammadOsama380)

---

## 📖 Overview
This project predicts **median house values in California** using geographic, demographic, and economic features from the **1990 U.S. Census** dataset.  
It applies and compares multiple regression algorithms to identify the best-performing model for real estate value estimation.

---

## 🎯 Objectives
- Perform **data cleaning and preprocessing**
- Apply and evaluate **multiple regression algorithms**
- Compare performance using **Mean Absolute Error (MAE)** and **Mean Squared Error (MSE)**
- Visualize model results and interpret correlations

---

## 🧩 Dataset
**Source:** 1990 U.S. Census  
**Size:** 20,640 entries, 10 attributes  

| Feature | Description |
|----------|-------------|
| `longitude`, `latitude` | Geographic coordinates |
| `housing_median_age` | Median age of houses |
| `total_rooms`, `total_bedrooms` | Housing characteristics |
| `population`, `households` | Demographics |
| `median_income` | Median household income |
| `ocean_proximity` | Categorical (distance to ocean) |
| `median_house_value` | Target variable (USD) |

---

## ⚙️ Models Implemented
| Model | MAE | MSE |
|--------|------|------|
| **Gradient Boosting Regressor** | **31,709** | **2.28×10⁹** |
| MLP Regressor | 48,249 | 4.47×10⁹ |
| Linear Regression | 50,413 | 4.80×10⁹ |
| ElasticNet | 50,452 | 4.81×10⁹ |
| Ridge Regression | 51,232 | 5.01×10⁹ |
| Lasso Regression | 51,257 | 5.02×10⁹ |
| Support Vector Regression (SVR) | 49,232 | 5.02×10⁹ |

✅ **Best Model:** Gradient Boosting Regressor  
Captures complex non-linear relationships through sequential tree-based learning and hyperparameter tuning (GridSearchCV).

---

## 🧠 Tools & Libraries
- Python 3.x  
- pandas, numpy, matplotlib  
- scikit-learn  
- Jupyter Notebook  

---

## 📈 Visualizations
- **Correlation heatmap** (feature vs. target)  
- **MAE/MSE comparison bar charts**  
- **Actual vs. Predicted scatter plots** for each model  

---

## 🚀 Future Work
- Engineer new features (ratios, interaction terms)
- Explore SVR with RBF kernel & deeper neural nets
- Integrate external data (crime rates, school quality)
- Use FeatureTools for automated feature creation

---

## 📂 Repository Structure
