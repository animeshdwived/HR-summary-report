# HR Summary Report Dashboard (Power BI)
## Project object
The objective of this project is to design an interactive HR Summary Dashboard using Power BI to analyze and visualize key HR metrics such as employee distribution, salary analysis, satisfaction levels, and employment status. The dashboard aims to provide HR managers and decision-makers with clear, data-driven insights that support strategic workforce planning, improve employee engagement, and identify areas requiring attention such as high turnover roles or gender pay gaps.

## Dataset used
- <a href="https://github.com/animeshdwived/HR-summary-report/blob/main/HRData.csv">Dataset</a>

# Questions (KPIs)
- How many employees are currently working in the organization?
- What is the total salary expenditure?
- How many employees distributed across different departments?
- What are the employment status types and how many fall under each?
- How satisfied are the employees?
- What are the salary distribution across different job positions?
- Which departments or positions have the highest number of terminated employees?
- What is the gender distribution of the workforce?
- Which positions contribute most to the salary budget?

  # Dashboard Intrection
  - <a href="https://github.com/animeshdwived/HR-summary-report/blob/main/HRData.csv">View dashboard</a>
  # Process
1.	📥 Data Collection
	•	Collected raw HR data including employee details, salaries, satisfaction scores, departments, genders, and employment statuses.
	•	Data was provided in Excel/CSV format.
2.	🧹 Data Cleaning & Preparation
	•	Handled missing values and removed duplicates.
	•	Standardized categorical values (e.g., job roles, departments).
	•	Created calculated columns and measures (e.g., total salary, satisfaction buckets).
3.	🔗 Data Modeling
	•	Defined relationships between tables (e.g., Employees, Positions, Departments).
	•	Built a star schema where required to optimize performance.
	•	Used DAX to create measures like Total Salary, Employee Count, and Average Satisfaction.
4.	Dashboard Development
	•	Built an interactive Power BI dashboard using:
	•	KPI cards for key metrics
	•	Pie and donut charts for categorical distributions
	•	Bar charts for salary and satisfaction analysis
	•	Filters for department, gender, and position
	•	Applied consistent color themes for better readability.
5.	Insight Generation
	•	Analyzed trends in salary distribution, satisfaction levels, and attrition.
        •	Identified areas needing attention (e.g., positions with high turnover or salary disparity).
6.	Deployment
	•	Saved the Power BI report as .pbix.
	•	Exported a screenshot for presentation.
	•	Uploaded the project files to GitHub for portfolio/demo purposes.

## Dashboard
![hr_summary_report](https://github.com/user-attachments/assets/9124867b-b99c-439c-bcfa-002933632390)

# Project Insights
•   Production department has the highest number of employees, contributing significantly to total headcount and salary budget.
•   The majority of employees are active, while a notable number have either voluntarily left or were terminated.
•   Employee satisfaction is largely skewed toward higher ratings (4 and 5), suggesting a generally positive work environment.
•   Technical roles and managerial positions receive the highest compensation, especially in Production and Engineering departments.
•   Gender analysis reveals noticeable disparities in salary distribution in several positions, indicating potential inequality.
•   Voluntary termination is more common than termination for cause, suggesting possible issues with employee engagement or satisfaction in certain roles.
•   A small number of positions such as Data Analysts, Admin Officers, and Executives contribute less to overall salary expenditure, implying a leaner 	 
    structure in those areas.

# Final conclusion
The HR Summary Report dashboard provides a comprehensive, data-driven view of the organization’s human resources landscape. It allows stakeholders to:
•   Make informed decisions regarding compensation, workforce planning, and employee satisfaction initiatives.
•   Detect and address attrition trends and potential gender gaps in salaries.
•   Understand the department-wise and role-wise contribution to overall salary expenses.
By visualizing critical HR KPIs in a single interface, this dashboard enhances HR operational efficiency, encourages strategic planning, and supports a more data-centric HR culture within the organization.
