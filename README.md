# HR-Employee-Attrition-Analysis

This project presents an end-to-end analysis of employee attrition using a fictional HR dataset. The primary objective is to identify key factors contributing to employee turnover and provide actionable insights to improve employee retention and organizational effectiveness.

## Project Overview

Employee attrition is a critical challenge for organizations, as it directly impacts productivity, morale, and business continuity. This project leverages exploratory data analysis and machine learning techniques to understand the drivers of attrition and predict the likelihood of an employee leaving the company.

## Objectives

* Explore attrition trends across demographics, job roles, and performance metrics
* Identify the most influential factors contributing to employee attrition
* Build a predictive model to classify employees likely to leave
* Recommend data-driven strategies to reduce attrition

## Project Structure

```
hr-employee-attrition-analysis/
│
├── README.md                    # Project documentation
├── HR_Attrition_Analysis.ipynb  # Main analysis notebook
├── data/
│   └── HREmployeeAttrition.csv  # Dataset file
```

## Dataset

The dataset used is a synthetic HR dataset containing 1,470 employee records and 35 features such as:

* Demographics (Age, Gender, Marital Status)
* Job Information (Job Role, Department, Years at Company)
* Compensation (Monthly Income, Stock Option Level)
* Performance and Engagement (Performance Rating, Job Satisfaction)
* Attrition Label (Yes/No)

## Key Analyses Performed

* Descriptive statistics and missing value treatment
* Feature distribution and class imbalance handling
* Correlation analysis and multicollinearity detection
* Logistic Regression model for classification
* Model performance evaluation using accuracy, precision, recall, F1 score, and ROC-AUC

## Results Summary

* Top contributors to attrition: OverTime, Job Satisfaction, Age, and Monthly Income
* The Random Forest Classifier model achieved competitive performance with balanced precision-recall tradeoffs
* Actionable insights were derived to help HR teams focus on high-risk employee segments

## Requirements

Install all necessary dependencies using:

```bash
pip install -r requirements.txt
```

Key packages include:

* pandas
* matplotlib
* seaborn
* scikit-learn

## How to Use

1. Clone the repository
2. Install dependencies
3. Run the `HR_Attrition_Analysis.ipynb` notebook

## Author

Shreyas Dasari
Data Scientist | AI Engineer