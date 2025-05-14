# HR_Analytics_Dashboard
This Power BI file is an HR Analytics Dashboard that visualizes key employee metrics such as attrition, job satisfaction, performance, and salary. It helps HR teams make data-driven decisions to improve employee retention and workplace efficiency

## Objective
The HR Analytics Dashboard helps the HR team understand employee data clearly.It shows why employees leave, their job satisfaction, and work-life balance.It also compares salary, experience, and job roles to find useful patterns.This helps the company make better decisions to keep employees happy.

## Dataset
<a href="https://github.com/CodebyHarsh10/HR_Analytics_Dashboard/blob/main/HR_Analytics.csv">Raw Data<a/>

## KPIs 
- Total Employees – Total number of employees in the company.(1470)
- Attrition Rate (%) – Percentage of employees who have left the company.(16.1%)
- Average Age – Average age of current employees.(37)
- Average Monthly Income – Mean salary received by employees per month.(6.5K)
- Average Years at Company – Average number of years employees have worked.(7.0)

## Process 
- Data Collection : HR data (like employee ID, age, gender, salary, job role, satisfaction scores, etc.) is collected from Excel or a database.
- Data Cleaning : Remove duplicates, fix missing values, correct data types (e.g., date, numbers), and check for errors in Power BI or Excel.
- Data Modeling : Create relationships between different tables (like employee info, department, salary, etc.) using Power BI's Model view.
- Create KPIs using DAX formulas like : Total Employees = COUNT(EmployeeID)
- Attrition Rate = (No. of Employees Left / Total Employees) × 100
- Data Visualization : Use charts like bar charts, pie charts, cards, and line graphs to show key metrics like attrition, job satisfaction, salary trends, etc.
- Dashboard Design : Arrange visuals neatly, add slicers (filters) for gender, department, etc., and apply colors/icons to make the report easy to read.
- Analysis & Insight Generation : Study the charts to find trends and patterns, such as which job roles have higher attrition, or how distance from home affects employee retention.

## View Dashboard
<img width="601" alt="HR_ANALYTICS Dashboard Screenshot 2025-05-14 161358" src="https://github.com/user-attachments/assets/da2c5896-fa92-4827-8f94-598c0da10cf1" />

## Dashboard Interaction

<a href="https://github.com/CodebyHarsh10/HR_Analytics_Dashboard/blob/main/HR_ANALYTICS%20DASHBOARD.pbix">Dashboard<a/>

## Dashboard Insights
- High Attrition in Specific Roles : Job roles like Laboratory Technician(62) and Sales Executive(57) show a higher number of employees leaving the company.
- Younger Employees Leave More : Employees aged between 26 to 35 are more likely to leave than older ones.
- Overall Attrition Rate : 16.1% (237 out of 1470 employees).
- Employees earning ≤ ₹5K/month account for ~69% of total attrition.
- Highest attrition from Life Sciences (38%) and Medical (27%) backgrounds.
- Job Roles with High Turnover: Sales Executive (57),Sales Representative (33)
- Male: 140 | Female: 79 — indicating a broader attrition challenge across both genders.
- Majority of attrition occurs within the first 2 years, highlighting potential onboarding or early engagement issue

## Conclusion
The HR analytics dashboard reveals that attrition is largely concentrated among young employees in low-paying roles within the R&D and Sales departments. Key contributing factors include
  - Low starting salary
  - Early-career stage
  - Specific job functions with limited growth or high pressure

## Recommendation
Enhance retention through salary restructuring, mentorship programs, and career path visibility.
  - Focus on early engagement and employee development, especially within the first 2 years.
  - Conduct department-specific retention reviews, especially in R&D and Sales.
