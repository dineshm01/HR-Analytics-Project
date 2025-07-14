# HR Analytics Project

This is an HR Analytics project implemented in Python. The goal is to analyze employee attrition patterns and understand which factors lead employees to leave the company. The project involves Exploratory Data Analysis (EDA) using a dataset related to employee satisfaction, evaluation, salary, promotion history, and other attributes.

## Files Included

* **HR Analytics.ipynb**: Jupyter Notebook containing the complete Python code for the project.
* **HR\_capstone\_dataset.csv**: Dataset used for analysis.
* **README.md**: This project description.

## Problem Statement

The project aims to help HR teams understand the factors driving employee attrition through data analysis. By identifying patterns, the company can take proactive steps to improve retention.

## Dataset Details

The dataset contains 14,999 records and 10 columns with the following features:

* **satisfaction\_level**: Level of satisfaction from 0 to 1.
* **last\_evaluation**: Last performance evaluation score from 0 to 1.
* **number\_project**: Number of projects handled by the employee.
* **average\_montly\_hours**: Monthly average working hours.
* **time\_spend\_company**: Number of years the employee has spent in the company.
* **Work\_accident**: Indicates if the employee had a work accident (1) or not (0).
* **left**: Indicates if the employee left the company (1) or not (0).
* **promotion\_last\_5years**: Indicates if the employee got a promotion in the last 5 years (1) or not (0).
* **Department**: The department the employee belongs to.
* **salary**: Salary level (low, medium, high).

## Analysis Performed

### Initial Exploration

* Checked basic info about dataset shape, columns, and missing values.
* Verified counts of salary levels and work accidents.

### Statistical Summary

* Used `.describe()` to understand distribution of numeric columns.
* Used `.corr()` to examine correlations between numeric variables.

### Data Visualization

All visualizations were created using `matplotlib` and `seaborn` to identify trends in attrition:

* **Histogram of `last_evaluation` split by attrition (`left`)**
* **Countplots of attrition (`left`) vs:**

  * `number_project`
  * `time_spend_company`
  * `Work_accident`
  * `promotion_last_5years`
  * `Department`
  * `salary`


## Key Insights from Visualizations

* Employees with extreme evaluation scores (either very high or very low) had a higher chance of leaving.
* More projects often correlated with higher attrition.
* Attrition was higher among employees with longer tenure (`time_spend_company`).
* Employees without promotions over 5 years showed higher attrition.
* Sales department and low-salary employees exhibited higher attrition.
* Work accidents did not have a strong impact on attrition.



## Conclusions

* Low satisfaction and high workload are leading to employee exits.
* Lack of promotions contributes significantly to attrition.
* Salaries and departments show notable patterns in turnover.


## Technologies Used

* Python (NumPy, Pandas)
* Visualization: Matplotlib, Seaborn
* Jupyter Notebook


