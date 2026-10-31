HR Analytics Dashboard ( power BI)
An interactive Power BI dashboard that looks at **employee attrition**: why people leave, and which groups are most at risk.

## THE QUEASTION
Why are employees leaving, and where should HR focus first?

## THE DATA
- A sample HR dataset with 1,480 rows and 38 columns.
- 10 duplicate Employee IDs were found, so all counts use distinct Employee IDs. This gives 1,470 employees.
- Fields include department, job role, age group, gender, marital status, monthly income, overtime and job satisfaction.

## WHAT I BUILT
- KPI cards: Total Employees, Attrition Rate, Employees Left, Average Income, Average Daily Rate, Average Job Satisfaction
- Slicers: Gender and Marital Status
- Attrition Rate by Department
- Attrition Rate by Job Role
- Attrition Rate by Overtime
- Average Monthly Income by Job Role
- Employees by Age Group and Gender
- Employees by Education Field
- Job Role table with average job satisfaction and headcount

## KEY NUMBERS
Measure                         Value 
Total employees                 1,470 
Employees who left              237 
Attrition rate                  16.1% 
Average monthly income          6,503 
Average daily rate              802.49 
Average job satisfaction        2.73 

## MY FINDINGS
- Sales Representatives have the highest attrition at 39.8% (33 of 83 left). Research Directors have the lowest at 2.5%.
- Overtime is a strong signal. 30.5% of employees working overtime left, compared with 10.4% of those who do not (about 3 times higher).
- Lower pay, higher attrition. Staff earning up to 5k left at 21.8%, compared with 3.8% for those earning 15k+.
- By department: Sales 20.6%, Human Resources 19.0%, Research & Development 13.8%.
- Younger and single employees leave more. The 18-25 age group has 35.8% attrition, and single employees 25.5%, compared with 12.5% for married employees.

## MY RECOMMENDATIONS
1. Review workloads and overtime, especially in Sales.
2. Look at pay, career paths and retention plans for Sales Representatives and lower-paid staff.
3. Give early-career employees more support and development in their first years.

## HOW I BUILT IT
1. Loaded the data into Power BI and checked for duplicates.
2. Used `DISTINCTCOUNT` on Employee ID in the DAX measures so duplicates are not counted twice.
3. Created measures for Attrition Rate, Employees Left and Total Employees.
4. Added a custom sort order for age groups so they appear in order.
5. Built the charts to show attrition rate, so groups of different sizes can be compared fairly.

## TOOLS
Power BI, DAX, Excel / CSV

## FILES
- [HR DBTECH.pbix](HR%20DBTECH.pbix): the Power BI report
- [HR.csv](HR.csv): the dataset
- [Dashboard screenshot](Screenshot%202026-10-31%20075746.png)

[LinkedIn](https://www.linkedin.com/in/osavibie-edoruyi-1131a6329)
