# AI Credit Delinquency Prediction

Developed as part of the **Tata iQ × Forage AI Transformation Virtual Experience Program**.

## Project Overview

This project analyzes customer credit data to identify key factors associated with payment delinquency and develops machine learning models to predict customers at risk of default. The project follows a complete data science workflow, including exploratory data analysis (EDA), data preprocessing, feature engineering, predictive modeling, model evaluation, and business recommendations for improving collections strategies.

---

## Objectives

- Perform exploratory data analysis to identify delinquency risk factors.
- Clean and preprocess customer financial data.
- Build predictive models for customer delinquency.
- Compare Logistic Regression and Random Forest models.
- Evaluate model performance using classification metrics.
- Translate analytical findings into actionable business recommendations.

---

## Repository Structure

```text
├── data/                 # Dataset information
├── images/               # Project visualizations
├── notebooks/
│   ├── 01_EDA.ipynb
│   └── 02_Model_Building.ipynb
├── presentation/         # Final presentation
├── reports/              # Project reports
├── requirements.txt
└── README.md
```

---

## Dataset

The dataset was provided through the **Tata iQ × Forage AI Transformation Virtual Experience Program**.

The original dataset is **not included** in this repository because permission to redistribute it publicly has not been confirmed. A dataset description is available in the `data` folder.

---

## Exploratory Data Analysis

The EDA focused on:

- Dataset overview
- Missing value analysis
- Data preprocessing
- Correlation analysis
- Delinquency pattern analysis
- Payment history analysis
- Feature relationship visualization

Example visualizations include:

- Missing Value Analysis
- Correlation Heatmap
- Delinquency Distribution
- Random Forest Feature Importance
- Model Performance Comparison

---

## Machine Learning Models

The following classification models were implemented and compared:

- Logistic Regression (Baseline Model)
- Random Forest Classifier (Final Selected Model)

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## Results

The analysis identified payment history, credit utilization, debt-to-income ratio, and account behavior as important indicators of customer delinquency. After comparing multiple classification models, the **Random Forest Classifier** was selected as the preferred model because it captured complex relationships within the data while maintaining strong predictive performance.

---

## Reports

This repository includes:

- Exploratory Data Analysis Report
- Predictive Model Plan
- Business Summary Report
- AI-Powered Collections System Presentation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Class imbalance handling using SMOTE
- Gradient Boosting (XGBoost/LightGBM)
- Model explainability using SHAP
- Deployment using Streamlit

---

## Acknowledgements

This project was completed as part of the **Tata iQ × Forage AI Transformation Virtual Experience Program**. The project demonstrates the application of data analytics and machine learning techniques to support AI-driven credit risk assessment and business decision-making.
