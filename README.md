# *Project Title: Palmora HR Analysis*

- [Project Overview](#Project-Overview)
- [Case Questions](#POINTERS-FROM-STAKEHOLDER)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Cleaning and Transformation](#Data-Cleaning-and-Transformation)
- [Report & Insights](#REPORT-&-INSIGHTS)
- [Recommendations](#Recommendations)
- [Conclusion](#CONCLUSION)
- 
# *Project Overview*
As a data analyst intern directed to assist with HR analysis of Palmora Manufacturing Group. Dataset is collected from the company and have been required to perform basic data cleaning and data processing using necessary tools to prepare the data for analysis. Organize and present the data effectively. Design a dashboard, utilizing the power of grouping for enhanced data visualization and analysis.  

In this project, Microsoft Excel and Power BI is used for analysis and visualization respectively. Insights from the analysis is recorded.  

The Palmora Analysis provides a comprehensive view of key performance indicators, employee data, and organisational efficiency metrics. The data highlights various aspects such as workforce distribution, performance trends, and operational bottlenecks.

The Dashboard reveals that employees with duplicate records have been intentionally left by HR to track their efficiency in different branch locations. This strategy helps determine whether employees should be retained in the new location based on their performance or returned to their previous branch if they are underperforming.


## POINTERS FROM STAKEHOLDER
*	Generally, there are two genders in the organization. However, some employees refused to disclose their gender. You would need to assign a generic gender status to these employees.
*	Some employees are without salary because they are no longer with the company. You will need to take those employees out 
*	Lastly, some departments are indicated as “NULL”. These department would also need to be taken out.  

## *CASE QUESTIONS:*

Select the appropriate visuals, to answer the questions below. 
1. What is the gender distribution in the organization? Distil to regions and departments using slicers. 
2. What is the Average Salary gotten by each Gender type. 
3. Show insights on ratings based on gender. (Hint: use a 100% stacked column chart)

## Exploratory Data Analysis
### *Data Source*

Dataset was obtained from the company and it consists if 1014 records and 7 columns including S/N, Name, Gender, Department, Salary, Location and Ratings.


### *Data Cleaning and Transformation*

* S/N column removed since it is same as that of Excel.
* 2 duplicate record was found and removed from the raw data.
* 43 Employees with ‘blank’ salary removed indicating they are no longer with the company.
* 27 Employees with ‘Null’ department removed indicating they are no longer with the company.
* 42 Employees with undisclosed gender: - generic genders (Male or female) were assigned for each employee based on their first name by using Excel data validation technique.
* Further scrutiny using conditional formatting showed there are more duplicate employee records with a difference in only ‘location’ and ‘ratings’ column which indicates location transfer.
* Based on the duplicate records, Excel formula was used to separate duplicate rows where only their new location record was retained.
* Further analysis was prompted to see how the employees are doing in their respective new location compared to old location. In order to achieve this, ‘rating’ column were represented by digits as Very Good, Good, Average, Poor, Very Poor, Not rated as 5,4,3,2,1,0 respectively.


### *REPORT & INSIGHTS*

The Palmora Analysis provides a comprehensive view of key performance indicators, employee data, and organisational efficiency metrics. The data highlights various aspects such as workforce distribution, performance trends, and operational bottlenecks.

* 70 Employees were found to be inactive with the company
* 140 duplicate employee records distilled to 70
* 804 unique employee records
* 874 Total Active Employees
* 3 Branches; 12 Departments
* $64,530,000 paid in Salary
* 36 Employees doing Good in new Location; 33 doing Bad 
* 340 Kaduna, 308 Abuja, 226 Lagos

The Dashboard reveals that employees with duplicate records have been intentionally left by HR to track their efficiency in different branch locations. This strategy helps determine whether employees should be retained in the new location based on their performance or returned to their previous branch if they are underperforming.



### *** Performance Insights on Transferred Employees & Branches

o	Employees who have adapted well to the new location show improved efficiency scores, stronger engagement, and higher productivity.

o	Some employees exhibit a decline in performance, indicating possible challenges such as difficulty adjusting to the new environment or differing work expectations.

o	Branches that receive high-performing employees benefit from increased operational effectiveness.

o	Underperforming transferred employees may negatively impact the new branch while also struggling with their transition.



### *** Recommendations for Employee Performance Improvement
•	For Employees Excelling in the New Location:

   o	Recognise and reward their adaptability to encourage continued high performance.
   
   o	Provide leadership or mentorship roles to maximise their impact in the new branch.
   
•	For Employees Struggling in the New Location:

   o	Implement tailored training sessions to help them adjust to the new branch’s workflow and expectations.
   
   o	Offer periodic performance reviews and structured feedback to guide their improvement.
   
   o	Provide temporary assistance (training, guides) to facilitate a smoother transition.
   

------------------------------------
# *CONCLUSION*
Tracking efficiency ratings through duplicate records is a strategic HR approach. By analysing performance trends, the company can make informed decisions on whether employees should remain in the new location or return to their former branch. Implementing targeted support mechanisms will ensure that all employees have the opportunity to succeed in their assigned locations.



------------------------------------

