# About Dataset
salaries dataset generally provides information about the employees of an organization in relation to their compensation. It typically includes details such as how much each employee is paid (their salary), their job titles, the departments they work in, and possibly additional information like their level of experience, education, and employment history within the organization.
  
# Features

| Feature | definition |
| -------- | -------- |
| Id: | A unique identifier for each employee. |
| EmployeeName: | The name of the employee. |
| JobTitle: | The job title of the employee. |
| BasePay: | The base salary of the employee. |
| OvertimePay: | The amount of overtime pay the employee received. |
| OtherPay: | The amount of other pay the employee received. |
| Benefits: | The total benefits the employee received. |
| TotalPay: | The total pay the employee received, including base pay, overtime pay, and other pay. |
| TotalPayBenefits: | The total pay and benefits the employee received. |
| Year: | The year in which the salary information was collected. |
| Notes: | Additional notes about the employee or their salary. |
| Agency: | The agency that the employee works for. |
| Status | |
  
# Tasks

1. **Basic Data Exploration**: Identify the number of rows and columns in the dataset, determine the data types of each column, and check for missing values in each column.

2. **Descriptive Statistics**: Calculate basic statistics mean, median, mode, minimum, and maximum salary, determine the range of salaries, and find the standard deviation.

3. **Data Cleaning**: Handle missing data by suitable method with explain why you use it.

4. **Basic Data Visualization**: Create histograms or bar charts to visualize the distribution of salaries, and use pie charts to represent the proportion of employees in different departments.

5. **Grouped Analysis**: Group the data by one or more columns and calculate summary statistics for each group, and compare the average salaries across different groups.

6. **Simple Correlation Analysis**: Identify any correlation between salary and another numerical column, and plot a scatter plot to visualize the relationship.

8. **Summary of Insights**: Write a brief report summarizing the findings and insights from the analyses.
  
# Summary of Insights  

The findings and insights from the analysis of a data set on the salaries of employees in **San Francisco** from **2011 to 2014**.  

**Missing Values**

* Notes and Status columns are empty.
* Missing values in pay columns are minimal and can be handled by filling them with the median for BasePay and zeros for OvertimePay and OtherPay.
* Missing values in Benefits column can be assumed to represent zero benefits.

**Average Pay Components**

* Average BasePay: $66,325.45
* Average Benefits: $25,007.89
* Average TotalPay: $74,768.32
* Average TotalPayBenefits: $93,692.55

**Top and Worst Paid Jobs**

* **Top 10 Paid Jobs:**
  * GENERAL MANAGER-METROPOLITAN TRANSIT AUTHORITY
  * Chief Investment Officer
  * Chief of Police
  * Chief, Fire Department
  * DEPUTY DIRECTOR OF INVESTMENTS
  * CHIEF OF DEPARTMENT, (FIRE DEPARTMENT)
  * Gen Mgr, Public Trnsp Dept
  * Asst Chf of Dept (Fire Dept)
  * DEPUTY CHIEF OF DEPARTMENT,(FIRE DEPARTMENT)
  * Dep Dir for Investments, Ret
* **Worst 10 Paid Jobs:**
  * PUBLIC SAFETY COMMUNICATIONS TECHNICIAN
  * BdComm Mbr, Grp2,M=$25/Mtg
  * BOARD/COMMISSION MEMBER, GROUP II
  * BOARD/COMMISSION MEMBER, GROUP III
  * SPECIAL ASSISTANT XIV
  * BdComm Mbr, Grp3,M=$50/Mtg
  * BOARD/COMMISSION MEMBER, GROUP V
  * SPECIAL EXAMINER
  * BdComm Mbr, Grp5,M$100/Mo
  * Commissioner 16.700c, No Pay

**Correlations**

* Strong correlation between TotalPay and BasePay, Benefits.
* BasePay is the most significant component of TotalPay.
* Weaker correlation between TotalPay and OvertimePay, OtherPay.
* Positive correlation between Benefits and TotalPay.
* Possible negative correlation between OtherPay and BasePay, Benefits.

**Other Findings**

* 52% of employees didn't have overtime work and 28% didn't have other pay.
* 74% of employees have Benefits pay.
* Benefits data is missing for 2011.
* There is an upward trend from 2011 to 2013, followed by a steep drop in 2014.
* Some rows were dropped due to missing values or data integrity issues.
