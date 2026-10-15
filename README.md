# Financial Risk Analysis & Loan Default Prediction

## Project Overview

This project focuses on analyzing loan data to identify important factors associated with loan default risk. The analysis includes data preprocessing, exploratory data analysis (EDA), data visualization, and machine learning.

The dataset contains **255,347 loan records** and **18 attributes**.

Three machine learning models were compared: Logistic Regression, Random Forest, and Gradient Boosting.

## Project Objectives

- Explore borrower and loan characteristics associated with default risk.
- Perform data cleaning and exploratory data analysis.
- Visualize important patterns and relationships.
- Develop and compare classification models.
- Identify influential features using feature importance analysis.

## Tools and Technologies

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn
- **Environment:** Jupyter Notebook / JupyterLite
- **Techniques:** EDA, Data Preprocessing, Data Visualization, Classification, Model Evaluation

## Dataset

The Loan Default Dataset contains 255,347 records with borrower and loan information.

Key variables include Income, Age, Credit Score, Loan Amount, Interest Rate, Months Employed, Debt-to-Income Ratio, Education, Employment Type, and Loan Purpose.

The target variable is **Default**, indicating whether a loan default occurred.

## Exploratory Data Analysis

Exploratory analysis was performed to understand the dataset and identify meaningful patterns.

The analysis included:

- Data quality checks
- Numerical feature distributions
- Categorical feature analysis
- Correlation analysis
- Loan default patterns
- Feature importance analysis

## Machine Learning Models

Three models were trained and evaluated:

1. Logistic Regression
2. Random Forest
3. Gradient Boosting

### Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 88.59% | 62.37% | 3.12% | 5.94% | 74.98% |
| Random Forest | 88.69% | 65.90% | 4.39% | 8.23% | 73.38% |
| Gradient Boosting | 88.74% | 65.41% | 5.29% | 9.79% | 75.66% |

**Gradient Boosting** achieved the strongest overall results among the three models based on ROC-AUC, Recall, and F1-score.

However, recall remained low because of class imbalance, indicating that further improvements are needed for identifying loan defaults reliably.

## Key Insights

Feature importance analysis identified several influential variables:

- Income
- Interest Rate
- Loan Amount
- Credit Score
- Age
- Months Employed
- Debt-to-Income Ratio

These variables contributed to the models' predictions of loan default risk.

## Project Structure

```text
financial-risk-analysis/
├── notebooks/
├── report/
├── images/
└── README.md
```

## Conclusion

This project demonstrates how Python, exploratory data analysis, and machine learning can be used to examine financial data and assess loan default risk.

It also highlights the importance of evaluating classification models using multiple metrics rather than relying only on accuracy.

## Author

**Tanu Shree Sharma**

M.Sc. Data Science  
Manipal Academy of Higher Education

GitHub: https://github.com/tanushreesharma2
