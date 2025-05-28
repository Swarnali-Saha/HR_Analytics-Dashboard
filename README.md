# HR_Analytics-Dashboard

📊 __Project Objective:__

The primary goal of this project is to uncover the key factors influencing employee attrition and deliver actionable insights to support strategic workforce retention. The interactive dashboard created offers comprehensive visibility into attrition trends within the organization, assisting the HR team in their analysis and decision-making processes.

🔍 __Project Scope:__  

Throughout the project, I had the opportunity to:
    - Analyze detailed HR data to extract meaningful patterns and trends.
    - Design and develop interactive dashboards to visualize critical HR metrics.
    - Deliver data-driven insights and strategic recommendations for improving employee retention.

🛠️ __Steps Followed:__

    - Data Acquisition:
          * Downloaded the HR dataset in .csv format and imported it into Power BI.
          * Loaded the data into Power Query Editor for preprocessing.

    - Data Cleaning:
        * Removed unnecessary columns, duplicates, and errors.
        * Replaced inconsistent values and renamed columns for clarity.
        * Applied data type detection to ensure accurate data representation.

    - Data Processing:
        * Created a new column "AttritionCount" using conditional logic: (If Attrition = "Yes", then 1; else 0).
        * Developed KPIs and charts using this new column.
        * Computed Attrition Rate using DAX: 
            Attrition Rate = SUM([AttritionCount]) / SUM([EmployeeCount])

    - Data Analysis & Visualization:
        * Built multiple visualizations including bar charts, pie charts, KPIs, matrix tables, and slicers.
        * Utilized these visual tools to present findings in an intuitive and actionable format.

📌 __Key Dashboard Questions Addressed:__

    - What is the total number of employees?
    - What are the average age and salary of employees?
    - What is the attrition count segmented by gender?
    - How many years have employees worked at the company?
    - Which department has the highest number of employees?
    - What is the gender distribution across the company?
    - What is the attrition rate by education?

📚 __Tools & Features Explored:__

    - Calculated Fields: For Attrition Rate and Active Employees
    - Matrix Table: For displaying Job Satisfaction ratings
    - Donut, Funnel, Bar, Area and Ribbon Charts
    - KPIs and Slicers
    - Filters: To segment data by education field

📈 __Summary of Key Insights:__

    - Total Employees: The organization employs 1,470 individuals, showcasing significant growth.
    - Attrition Overview: 237 employees left the organization — 150 males and 87 females — indicating higher attrition among males.
    - Education Field: Life Sciences majors had the highest attrition, highlighting a critical area for HR to address.
    - Job Role Impact: Laboratory technician roles saw the highest turnover, pointing to challenges in this area.
    - Age & Gender: Employees aged 25–34 had the highest attrition count(116; Male:70 and Female:46 ), emphasizing a retention challenge in this demographic.

__Screenshot of the dashboard:__

![Dashboard Preview:](https://github.com/Swarnali-Saha/HR_Analytics-Dashboard/blob/main/HR_Analytics%20Dashboard.png)
