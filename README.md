
# 🚗 Fuel Efficiency Prediction and Analysis for Automotive Insights

## 📖 Overview

This project uses Machine Learning to predict vehicle fuel efficiency (MPG) based on automotive characteristics such as engine size, horsepower, weight, acceleration, model year, and origin.

The goal is to help automotive manufacturers understand the factors affecting fuel efficiency and support data-driven vehicle design decisions.

---

## 🎯 Business Objective

- Predict vehicle fuel efficiency accurately.
- Identify the key drivers of fuel consumption.
- Enable manufacturers to optimize vehicle design.
- Support data-driven decision-making in the automotive industry.

---

## 📊 Dataset

**Auto MPG Dataset**

Features used:

- Cylinders
- Displacement
- Horsepower
- Weight
- Acceleration
- Model Year
- Origin

**Target Variable:**
- MPG (Miles Per Gallon)

---

## ⚙️ Project Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development
5. Cross-Validation
6. Hyperparameter Tuning
7. Model Evaluation
8. Feature Importance & Explainability
9. Power BI Dashboard Development

---

## 🤖 Models Evaluated

| Model | MAE | RMSE | R² |
|---------|---------:|---------:|---------:|
| Linear Regression | 2.29 | 2.89 | 0.845 |
| XGBoost (Tuned) | 1.77 | 2.45 | 0.888 |
| Random Forest (Tuned) | **1.59** | **2.15** | **0.914** |

### ✅ Best Model

**Random Forest Regressor (Tuned)**

- R² Score: **91.4%**
- MAE: **1.59 MPG**
- RMSE: **2.15 MPG**

---

## 🔍 Key Insights

- Vehicle **weight** is the strongest predictor of fuel efficiency.
- Higher **horsepower** and **engine displacement** generally reduce MPG.
- Fuel efficiency improved significantly across model years.
- Japanese vehicles showed higher fuel efficiency compared to other regions.

---

## 📈 Power BI Dashboard

The dashboard was designed for business stakeholders to:

- Monitor fuel efficiency trends
- Identify key MPG drivers
- Compare vehicle performance by region
- Understand model accuracy
- Support engineering and design decisions

### Dashboard Highlights

✅ Executive KPI Cards

✅ Feature Importance Analysis

✅ MPG vs Weight Relationship

✅ Regional Fuel Efficiency Comparison

✅ Model Performance Overview

✅ Strategic Recommendations

---

## 🛠️ Tech Stack

**Programming:** Python

**Libraries:**
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn

**Visualization:**
- Power BI

---

## 📂 Project Structure

```text
Fuel-Efficiency-Prediction
│
├── data/
├── notebook/
├── dashboard/
├── report/
├── images/
└── README.md
```

---

## 🚀 Business Impact

This project demonstrates how machine learning can help manufacturers predict fuel efficiency before production, identify efficiency trade-offs, and make informed design decisions. The solution provides actionable insights that can contribute to reduced costs, improved vehicle performance, and stronger competitive advantage.

---

## 👨‍💻 Author

**Rahit Saha**

Data Science & AI Enthusiast

