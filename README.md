# Project1-DAbootcamp-Grp2

# Project Title: 
What makes employees leave: A tale of two organisations

# Team Members:
Brianna O'Connor, Shannon Chen

# Project Description: 
The cost of hiring, training and onboarding new employees often exceeds the cost of retaining existing workers. Despite this, most organisations tend to turn a blind eye to what might be causing their best and brightest to leave. 

In this project, we seek to uncover what aspects of human resource management may contribute to staff turnover in two separate anonymised organisations. We have come up with a set of research questions about how factors such as salary, tenure, department, duration in a specific role, performance management, and workload may influence an employee’s decision to leave. From our analysis, we also hope to examine whether similar trends emerge across both organisations.

# Datasets Used:

1) EmployeeAttrition.csv (renamed from 'train_data.csv). Source: https://www.kaggle.com/datasets/pavan9065/predicting-employee-attrition?select=train_data.csv 

Variables in EmployeeAttrition.csv: 
> MMM-YY (Date of Record); 
> Emp_ID	(Unique id for employees);
> Age of the employee;
> Gender of the employee;
> City Code of the employee;
> Education_Level;
> Salary;
> Date of joining for the employee;
> Last Working Date for the employee;
> Joining Designation of the employee;
> Designation of the employee at the time of reporting;
> Total Business Value acquired by the employee in a month (negative business indicates cancellation/refund of sold insurance policies);
> Quarterly Rating	of the employee (out of 4 where higher ratings = better performance);

2) HR_comma_sep.csv. Source: https://www.kaggle.com/code/jacksonchou/hr-analytics/report

Variables in HR_comma_sep.csv: 
> satisfaction_level (Job Satisfaction - higher values, greater satisfaction);
> last_evaluation (Most recent performance rating);
> number_project (Number of projects allocated/Workload);
> average_montly_hours (Average hours spent at work each month);
> time_spend_company (Tenure in Years);
> Work_accident; left (left organisation);
> promotion_last_5years (Received a promotion in the last 5 years);
> sales (Contains information about departments sales, accounting, support etc..);
> salary (low, medium, high)

# Packages Used:

pandas

matplotlib.pyplot

scipy.stats

numpy

datetime

# Working Jupyter notebooks for Exploratory Data Analysis:

## In 01_Data

1. HRcomma_clean.ipynb
2. EmployeeAttrition_data_clean.ipynb
3. EmployeeAttrition_Designation.ipynb
4. EmployeeAttrition_SampleID.ipynb
5. EmployeeAttrition_Leavers.ipynb
6. EA_Salary_Investigation.ipynb
