# Bank Loan Prediction Using Machine Learning

## Project Overview

This project focuses on applying Machine Learning techniques to bank loan data to predict loan amounts and loan approval status.

Four Machine Learning models have been implemented using Python, covering both Regression and Classification techniques.

## Project Objectives

- Understand and implement Machine Learning algorithms.
- Predict loan amounts using applicant income and financial information.
- Study the relationship between multiple financial variables.
- Apply Dummy Variable Encoding to categorical data.
- Predict loan approval status using Logistic Regression.
- Evaluate and interpret model performance.

## Dataset Information

- **Dataset:** `loan_approval_dataset.csv`
- **Total Records:** 4,269
- **Total Features:** 13
- **Source:** Kaggle
- **Usage:** The dataset is described as open-source and suitable for publication. Please retain the original Kaggle attribution and comply with the specific licence shown on the dataset's Kaggle page.

The dataset contains information about:

- Applicant details: Number of dependents, education and self-employment status.
- Financial details: Annual income, loan amount and loan term.
- Credit information: CIBIL score.
- Asset information: Residential, commercial, luxury and bank asset values.
- Target variable: Loan status (Approved or Rejected).

**Dataset attribution:** The Loan Approval Prediction Dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset). Please refer to the original dataset page for licensing and usage terms.

## Machine Learning Models Implemented

| No. | Algorithm | Objective |
|---|---|---|
| 1 | Simple Linear Regression | Predict loan amount using annual income |
| 2 | Multiple Linear Regression | Predict loan amount using multiple numerical variables |
| 3 | Multiple Linear Regression with Dummy Variables | Predict loan amount using numerical and categorical variables |
| 4 | Logistic Regression | Predict loan approval status |

## Model Evaluation Metrics

**For Regression Models:**
- R-squared (R²)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

**For Classification Model:**
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-score

## Technologies and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Repository Structure

```text
Bank-Loan-Prediction-Using-Machine-Learning/
│
├── Dataset/
│   └── loan_approval_dataset.csv
│
├── 01_Simple_Linear_Regression.ipynb
├── 02_Multiple_Linear_Regression.ipynb
├── 03_Multiple_Linear_Regression_Dummy_Variables.ipynb
├── 04_Logistic_Regression_Loan_Approval_Prediction.ipynb
│
└── README.md
```

## Key Learning Outcomes

- Data loading, cleaning and preprocessing.
- Selection of independent and dependent variables.
- Training and testing Machine Learning models.
- Implementation of regression and classification algorithms.
- Categorical data encoding using Dummy Variables.
- Model evaluation and performance interpretation.
- Data visualization and result analysis.

## Author

**Hardik Pareek**

MBA – Finance & Data Science with AI

This project is part of my academic and practical learning journey in Machine Learning, Data Analysis and Financial Applications.

---

*Disclaimer: This project is developed for educational purposes and is not intended for actual loan approval or lending decisions.*
