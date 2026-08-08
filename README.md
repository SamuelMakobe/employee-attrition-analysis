# Employee Attrition Analysis

## Project Overview

This project was completed as part of Week 1 of the Data Science Internship at **AnalystLab Africa**. The project focuses on exploring employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset.

The purpose of the analysis was to understand the structure of the dataset, explore employee characteristics, identify patterns in employee attrition, and develop initial business insights that could help an organisation better understand factors associated with employee turnover.

## Business Problem

Employee attrition can affect an organisation through increased recruitment and training costs, loss of experienced employees, and potential disruption to productivity. Understanding patterns associated with employee turnover can help organisations identify areas that may require further investigation.

This project therefore explores employee attrition and examines how it varies across different workforce characteristics.

## Dataset

The analysis uses the **IBM HR Analytics Employee Attrition & Performance** dataset. The dataset contains **1,470 employee records and 35 variables** covering demographic, job-related, satisfaction, compensation, and work-related characteristics.

The target variable for the analysis is **Attrition**, which indicates whether an employee left the organisation (`Yes`) or remained (`No`).

## Tools and Technologies

* Python
* pandas
* NumPy
* `matplotlib.pyplot`
* Jupyter Notebook
* Anaconda

## Analysis Performed

The project included:

* Loading the dataset using pandas.
* Inspecting the dataset structure using `shape`, `columns`, and `dtypes`.
* Checking for missing values and duplicate records.
* Examining descriptive statistics for numerical and categorical variables.
* Calculating employee attrition counts and percentages using `value_counts()`.
* Comparing attrition across departments, job roles, overtime status, and job satisfaction using `pd.crosstab()`.
* Creating visualisations using pandas plotting functions and `matplotlib.pyplot`.
* Developing initial business insights from the analysis.

## Key Findings

Some of the initial findings from the analysis were:

* The overall employee attrition rate was **16.12%**.
* **Sales Representatives** had the highest observed attrition rate among the analysed job roles, at **39.76%**.
* Employees who worked overtime had an attrition rate of **30.53%**, compared with **10.44%** among employees who did not work overtime.
* Attrition differed across departments, with **Sales** showing an attrition rate of approximately **20.63%**.
* Employees with lower job satisfaction showed higher attrition rates than those with higher job satisfaction.

These findings represent initial observations from exploratory analysis and would require further investigation before being used to make definitive conclusions about the causes of employee attrition.

## Project Structure

```text
employee-attrition-analysis/
│
├── Employee_attrition_analysis.ipynb
└── README.md
```

## How to Use This Project

To explore the analysis:

1. Download or clone this repository.
2. Open `Employee_attrition_analysis.ipynb` using Jupyter Notebook or JupyterLab.
3. Run the notebook cells sequentially to reproduce the analysis and visualisations.

## Author

**Samuel Makobe**

Data Science Intern
AnalystLab Africa
