# HR_Analytics-Dashboard

📊 __Project Objective:__

The primary goal of this project is to uncover the key factors influencing employee attrition and deliver actionable insights to support strategic workforce retention. The interactive dashboard created offers comprehensive visibility into attrition trends within the organization, assisting the HR team in their analysis and decision-making processes.
#
🔍 __Project Scope:__  

Throughout the project, I had the opportunity to:

• Analyze detailed HR data to extract meaningful patterns and trends.

• Design and develop interactive dashboards to visualize critical HR metrics.

• Deliver data-driven insights and strategic recommendations for improving employee retention.

#
🛠️ __Steps Followed:__

• __Data Acquisition:__
 
1. Downloaded the HR dataset in .csv format and imported it into Power BI.

2. Loaded the data into Power Query Editor for preprocessing.

• __Data Cleaning:__

1. Removed unnecessary columns, duplicates, and errors.
2. Replaced inconsistent values and renamed columns for clarity.
3. Applied data type detection to ensure accurate data representation.

• __Data Processing:__

1. Created a new column "AttritionCount" using conditional logic: (If Attrition = "Yes", then 1; else 0).
2. Developed KPIs and charts using this new column.
3. Computed Attrition Rate using DAX: 
4. Attrition Rate = SUM([AttritionCount]) / SUM([EmployeeCount])

• __Data Analysis & Visualization:__

1. Built multiple visualizations including bar charts, pie charts, KPIs, matrix tables, and slicers.
2. Utilized these visual tools to present findings in an intuitive and actionable format.

#
📌 __Key Dashboard Questions Addressed:__

• What is the total number of employees?

• What are the average age and salary of employees?

• What is the attrition count segmented by gender?

• How many years have employees worked at the company?

• Which department has the highest number of employees?

• What is the gender distribution across the company?

• What is the attrition rate by education?

#
📚 __Tools & Features Explored:__

• __Calculated Fields:__ For Attrition Rate and Active Employees

• __Matrix Table:__ For displaying Job Satisfaction ratings

• __Donut, Funnel, Bar, Area and Ribbon Charts__

• __KPIs and Slicers__

• __Filters:__ To segment data by education field

#
📈 __Summary of Key Insights:__

• __Total Employees:__ The organization employs 1,470 individuals, showcasing significant growth.

• __Attrition Overview:__ 237 employees left the organization — 150 males and 87 females — indicating higher attrition among males.

• __Education Field:__ Life Sciences majors had the highest attrition, highlighting a critical area for HR to address.

• __Job Role Impact:__ Laboratory technician roles saw the highest turnover, pointing to challenges in this area.

• __Age & Gender:__ Employees aged 25–34 had the highest attrition count(116; Male:70 and Female:46 ), emphasizing a retention challenge in this demographic.

#
__Screenshot of the dashboard:__

![Dashboard Preview:](https://github.com/Swarnali-Saha/HR_Analytics-Dashboard/blob/main/HR_Analytics%20Dashboard.png)
