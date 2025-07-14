# HR Analytics Project

A data-driven HR Analytics project conducted using Python, focusing on employee attrition analysis and various factors influencing retention within an organization. This project includes Exploratory Data Analysis (EDA), visualization, and actionable insights from HR datasets.

## 📂 Project Structure

* `HR Analytics.ipynb`: Jupyter Notebook with full analysis and visualizations
* `HR_capstone_dataset.csv`: Dataset used for the analysis
* `README.md`: This README file

## 📝 Problem Statement

Employee retention is a significant challenge in HR management. The objective of this project is to analyze historical HR data to identify factors that lead to employee attrition, explore the impact of satisfaction levels, promotions, workloads, and other factors, and provide actionable insights to reduce attrition.

## 📊 Dataset Information

The dataset used is named `HR_capstone_dataset.csv` and contains 14,999 rows and 10 columns.

### Column Descriptions:

* `satisfaction_level`: A numeric value between 0 and 1 representing the employee's job satisfaction.
* `last_evaluation`: A numeric score between 0 and 1 representing the employee’s last evaluation result.
* `number_project`: The number of projects handled by the employee.
* `average_montly_hours`: The employee’s average monthly working hours.
* `time_spend_company`: The number of years the employee has been with the company.
* `Work_accident`: Indicates whether the employee had a work accident (1 for yes, 0 for no).
* `left`: Indicates whether the employee left the company (1 for yes, 0 for no).
* `promotion_last_5years`: Indicates whether the employee was promoted in the last five years (1 for yes, 0 for no).
* `Department`: The department where the employee worked (e.g., sales, technical, HR, etc.).
* `salary`: The employee's salary category: low, medium, or high.

##  Key Steps Performed

1. **Data Cleaning:** Confirmed no missing values and validated data types.
2. **Exploratory Data Analysis (EDA):** Analyzed distributions of satisfaction level, evaluation scores, and working hours; created correlation heatmaps; explored attrition patterns across departments, salary levels, and promotions.
3. **Visualization Tools:** Used Matplotlib and Seaborn.
4. **Insights Derived:** Lower satisfaction and higher workload were strongly linked to attrition. Sales and low-salary employees exhibited higher attrition. Very few employees were promoted in the last 5 years.

##  Sample Visualizations

* Boxplots for attrition vs. satisfaction and working hours.
* Heatmap for feature correlations.
* Bar charts showing attrition by department and salary.

##  Conclusions

Employee satisfaction and workload are key drivers for attrition. Companies should prioritize employee well-being and career growth to improve retention. Salary revisions may help reduce turnover in certain departments.

##  Technologies Used

* Python (Pandas, NumPy)
* Matplotlib & Seaborn for visualization
* Jupyter Notebook

## 🔗 Project Resources

* The dataset is provided as a CSV file.
* Complete analysis is available in the Jupyter Notebook.
