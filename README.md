# 📉 Telco Customer Churn Prediction (Capstone Project)

## 1. Project Objective
This project follows the **CRISP-DM** methodology to analyze customer data, identify key drivers of churn, and build predictive machine learning models to retain customers.

## 2. Research Question
*What are the primary indicators of customer churn, and can we predict which customers are at risk of leaving?*

## 3. Dataset
**Source:** [Telco Customer Churn (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)  
*(Note: The dataset file is included in this repository as `WA_Fn-UseC_-Telco-Customer-Churn.csv`)*

## 4. Methodology (CRISP-DM)
1.  **Business Understanding:** Defined churn as a binary classification problem.
2.  **Data Prep:** Handled missing values, removed multicollinearity (TotalCharges), scaled features.
3.  **EDA:** Visualized churn balance and feature correlations.
4.  **Modeling:** Trained and compared three models:
    * Logistic Regression
    * Decision Tree
    * Random Forest
5.  **Evaluation:** Logistic Regression achieved the highest accuracy (**~82%**), proving that a linear model works best for this specific dataset.
6.  **Deployment:** Created a simulated "Churn Calculator" script to predict risk for new customers.

## 5. Key Findings
* 🔴 **Risk:** **Fiber Optic Internet** is the #1 driver of churn.
* 🟢 **Retention:** **Long-term contracts** (2-Year) are the best retention tool.
* 💡 **Insight:** Monthly price is less important than contract commitment type.

## 6. How to Run
1.  Install requirements: `pip install -r requirements.txt`
2.  Open `Capstone_Project.ipynb` in Jupyter Notebook.
3.  Run all cells to reproduce the analysis.
