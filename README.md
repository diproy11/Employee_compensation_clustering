# K-Means-Project

Source of Data The San Francisco Controller's Office maintains a database of the salary and benefits

paid to City employees since fiscal year 2013. This data is summarized and presented on

the Employee Compensation and is also

available in CSV format in the directory.

# Overview of the problem
# Description of Data :
Each row is an employee, and has columns about employee's information like their job type,salary, hours of overtime,other benefits etc.Overall there are 22 columns.

# Column definations:
1.Year Type Fiscal (July through June) or Calendar (January through December)

2.Year An accounting period of 12 months. The City and County of San Francisco operates on a fiscal year that begins on July 1 and ends on June 30 the following year. The Fiscal Year ending June 30, 2012 is represented as FY2011-2012.

3.Organization Group Code Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.

4.Organization Group Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.

5.Department Code Departments are the primary organizational unit used by the City and County of San Francisco. Examples include

6.Code Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).

7.Union Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).

8.Job Family Code Job Family combines similar Jobs into meaningful groups.

9.Job Family Job Family combines similar Jobs into meaningful groups.

10.Job Code Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.

11.Job Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.

12.Employee Identifier Each distinct number in the “Employee Identifier” column represents one employee. These identifying numbers are not meaningful but rather are randomly assigned for the purpose of building this dataset. The column does not appear on the Employee Compensation report hosted on openbook.sfgov.org, but that report does show one row for each employee. Employee ID has been included here to allow users to reconstruct the original report. Note that each employee’s identifier will change each time this dataset is updated, so comparisons by employee across multiple versions of the dataset are not possible.

13.Salaries Normal salaries paid to permanent or temporary City employees.

1.Overtime Amounts paid to City employees working in excess of 40 hours per week.

2.Other Salaries Various irregular payments made to City employees including premium pay, incentive pay, or other one-time payments.

3.Total Salary The sum of all salaries paid to City employees.

4.Retirement City contributions to employee retirement plans.

5.Health and Dental City-paid premiums to health and dental insurance plans covering City employees. To protect confidentiality as legally required, pro-rated citywide averages are presented in lieu of employee-specific health and dental benefits.

6.Other Benefits Mandatory benefits paid on behalf of employees, such as Social Security (FICA and Medicare) contributions, unemployment insurance premiums, and minor discretionary benefits not included in the above categories.

7.Total Benefits The sum of all benefits paid to City employees.

8.Total Compensation The sum of all salaries and benefits paid to City employees.

# Objective of Problem :
You have to fit the data to a clustering model.

Find the number of clusters for the data
