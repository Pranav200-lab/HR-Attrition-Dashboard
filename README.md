# HR Attrition Dashboard (Power BI)

An interactive Power BI dashboard that analyzes employee attrition for 1,470 employees to find out who is leaving and why.

## Dataset
- HR_Analytics.csv: 1,470 employees, 38 columns, 237 leavers (16.12% attrition)
- Source: public IBM HR Analytics sample dataset (Kaggle)

## What I did
- Cleaned the data in Power Query: duplicate EmpID check and removal, column profiling on the entire dataset
- Wrote DAX measures: Total Employees, Total Attrition Employees, Attrition Rate (DIVIDE), and RANKX for dynamic highlighting
- Built KPI cards, charts by Department, Age Group, OverTime and Salary Slab, a donut chart by department, and slicers for Gender, Marital Status and Department
- Created a Key Insights page with bookmarks and navigation buttons

## Key findings
- Employees working overtime: 30.53% attrition vs 10.44% for others
- Age group 18-25: 35.77% attrition
- Salary up to 5k: 21.76% vs 3.76% for 15k+
- Sales: 20.63% vs R&D: 13.84% (R&D still has 133 of the 237 leavers)

## Screenshots
![Dashboard](Screenshot%202026-11-11%20152058.png)
![Key Insights](Screenshot%202026-11-11%20152206.png)

## Tools
Power BI Desktop, Power Query, DAX
