# 🏦 Bank Customer Churn Prediction & Analytics

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-XGBoost%20%7C%20Random%20Forest-orange)
![Power BI](https://img.shields.io/badge/Data%20Visualization-Power%20BI-yellow)

## 📌 Project Overview
An end-to-end Machine Learning pipeline and interactive Power BI dashboard to predict bank customer churn. This project utilizes XGBoost for accurate predictions and SHAP values for model explainability, ultimately providing data-driven retention strategies for the banking sector.

## 🎯 Business Goal
Customer acquisition is significantly more expensive than customer retention. By accurately predicting which customers are likely to churn, the bank can proactively offer targeted loyalty programs, personalized incentives, and dedicated support to minimize revenue loss.

## 🛠️ Tech Stack & Tools
Programming Language: Python (Pandas, NumPy)

Machine Learning: Scikit-Learn, XGBoost, Random Forest

Model Explainability: SHAP (SHapley Additive exPlanations)

Data Visualization & BI: Power BI, Matplotlib, Seaborn

💡 Key Findings & Business Insights
Geographic Risk: Customers in Germany exhibit a significantly higher churn risk (average ~32%) compared to France and Spain, indicating an urgent need for region-specific retention strategies.

Age Factor: The churn rate peaks among customers aged 45-60. This valuable demographic requires targeted loyalty or retirement-focused campaigns.

Product Complexity vs. Activity: Counterintuitively, non-active customers holding 3 or 4 products show an exceptionally high churn rate. This suggests potential issues with product usability or over-marketing, proving that activity is a crucial retention metric.
🧠 Model Feature Importance
To understand exactly which factors drive customer churn, I analyzed the feature importance from the trained XGBoost model.

As seen in the chart, Age is the most critical factor influencing churn, followed by the number of products a customer holds, and their geographic location (specifically Germany).

📷 Executive Power BI Dashboard
<img width="1266" height="709" alt="PowerBI_Churn" src="https://github.com/user-attachments/assets/8af578c2-9c3f-4b21-8385-b17c776b80c0" />

## 📂 Project Structure
```text
├── data/                   # Raw and processed datasets
├── models/                 # Saved machine learning models (e.g., model.pkl)
├── notebooks/              # Jupyter notebooks for EDA, Data Cleaning, and Model Training
├── PowerBI/                # Power BI dashboard files (.pbix) and export images
├── Reports                 # SHAP Feature Importance visual
└── README.md               # Project documentation



