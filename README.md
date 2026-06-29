# Employee Attrition Prediction using Machine Learning

## Overview

Employee Attrition Prediction is a machine learning project that helps organizations identify employees who are at risk of leaving the company. The project uses the IBM HR Analytics Employee Attrition dataset to analyze employee characteristics and predict attrition based on workplace and personal factors.

The objective is to support HR teams in making proactive, data-driven decisions to improve employee retention.

---

## Project Objectives

- Analyze employee attrition patterns using Exploratory Data Analysis (EDA).
- Build and compare multiple machine learning classification models.
- Identify the key factors influencing employee attrition.
- Provide actionable HR recommendations based on the analysis.

---

## Dataset

- **Dataset:** IBM HR Analytics Employee Attrition & Performance
- **Source:** Kaggle
- **Records:** 1,470 Employees
- **Target Variable:** Attrition (Yes/No)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models

The following classification models were implemented and compared:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## Project Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Building
6. Model Evaluation
7. Feature Importance Analysis
8. Business Insights & HR Recommendations

---

## Visualizations

The project includes:

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income vs Attrition
- Confusion Matrix
- Top 10 Feature Importance
- ROC Curve Comparison

---

## Project Structure

```
EmployeeAttribution_Manivarun/
│
├── analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── summary.pdf
├── charts/
│   ├── department_attrition.png
│   ├── jobrole_attrition.png
│   ├── monthly_income_boxplot.png
│   ├── confusion_matrix.png
│   ├── top10_features.png
│   └── roc_curve.png
```

---

## Key Insights

- Employee attrition is influenced by multiple workplace factors.
- Overtime, monthly income, and years at the company are among the strongest predictors.
- Certain departments and job roles experience higher attrition rates.
- Employee retention strategies should focus on work-life balance, employee engagement, and career development.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- SMOTE for handling class imbalance
- Model deployment using Flask or FastAPI
- Interactive dashboard using Streamlit

---

## Author

**Mani Varun**

- GitHub: https://github.com/manivarun-05
- LinkedIn: www.linkedin.com/in/manivarun05

---

## License

This project is developed for educational and internship purposes.
