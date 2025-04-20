# Salary Prediction Dashboard for HRs

This project aims to assist Human Resources departments in predicting whether an individual's income is more or less than ₹50K per annum based on their demographic and employment-related information using various machine learning models.

## Project Overview

- **Internship Project Title**: RIO-210: Salary Prediction Dashboard for HRs  
- **Internship Organization**: TCS iON (Tata Consultancy Services)  
- **Institution**: Vishwakarma University, Pune  
- **Internship Duration**: 20 Feb 2024 – 20 Mar 2024  
- **Total Hours**: 210  
- **Tools Used**: VS Code, Python  
- **Libraries**: Pandas, NumPy, Missingno, Matplotlib, Seaborn, scikit-learn  

## Objective

To develop a machine learning dashboard that classifies individuals into salary brackets (≤50K or >50K) using demographic and job-related features.

## Methodology

### 1. Data Exploration & Cleaning
- Identified and imputed missing values using mode for categorical columns.
- Removed redundant features and converted all categorical variables using Label Encoding.

### 2. Exploratory Data Analysis
- Used various plots such as histograms, bar plots, boxplots, and pie charts to understand feature distributions.
- Analyzed outliers in 'age' and 'hours-per-week'.

### 3. Model Building
Implemented and tested multiple classification algorithms:
- **Random Forest** – **Best performing model** with **81.98% accuracy**
- Decision Tree – 77.95%
- Logistic Regression – 76.14%
- K-Nearest Neighbors – Tested with k from 70 to 90
- Support Vector Machine – 75.78%

### 4. Model Evaluation
- Used accuracy scores and confusion matrices for evaluation.
- Visualized model performance comparisons.

## Key Insights

- **Top Predictive Features**: Education Level, Occupation, Hours per Week
- Random Forest performed best due to its ensemble nature and resistance to overfitting.
- Handling missing values using mode imputation improved model performance.

## Challenges

- Dealing with missing and imbalanced data (e.g., race, native-country)
- Ensuring fair predictions given the sensitive nature of demographic data
- Hyperparameter tuning for optimal accuracy

## Risk vs Reward

| Risks | Rewards |
|------|---------|
| Overfitting | Accurate salary classification |
| Bias in predictions | Practical tool for HR analytics |
| Misclassification costs | Deep insight into salary predictors |

## Outcomes

- Developed a functioning ML pipeline with an accuracy of ~82%
- Gained practical experience in data science workflow
- Learned model comparison, tuning, and interpretability

