# HR Project
![cover](https://github.com/user-attachments/assets/4acca880-2e50-4712-8905-cffae08a90fa)
## Overview and Objectives
### Overview:
This project aims to analyze HR data to gain insights into employee performance, satisfaction, and attrition rates. By leveraging SQL, Python, Tableau, and Excel, we will integrate various data sources to create a comprehensive HR analytics dashboard.
### Objectives:
Identify key factors influencing employee turnover.
Determine which departments and job roles are most affected by turnover.
Analyze salary variations across different demographics and roles.
Assess the impact of education, financial benefits, and managerial level on salaries and promotions.
Investigate the relationship between work-life balance, travel frequency, and employee retention.
Evaluate the effect of managerial tenure on employee satisfaction.
Compare self-ratings and manager ratings to assess performance gaps.
Analyze the impact of training opportunities on satisfaction and career growth.
![overview](https://github.com/user-attachments/assets/bfd81de2-bc28-490c-9e75-87c185792b0d)
## Scope:
 >Data extraction, cleaning, and transformation.
  >Turnover analysis and key influencing factors.
  >Salary distribution and influencing variables.
 >Performance evaluation using self and manager ratings.
 >Work-life balance and retention analysis.
 >Predictive modeling for attrition.
 >Dashboard creation using Tableau.
![scpoe](https://github.com/user-attachments/assets/96a19f9d-58a5-4268-969f-fc629960ed0c)
## Timeline and Milestones
Week 1: Analysis & Forecasting Questions Phase 
  
  Week 2-3: Data Cleaning and preprocessing
  
  Week 4-5: Visualization Dashboard
  
  Week 6-7: Final Report & Presentation
![timeline](https://github.com/user-attachments/assets/0e025b18-f545-41c8-8b61-7af6664be7e7)
### Gantt Chart 
![time](https://github.com/user-attachments/assets/76da74ae-7bff-4664-9b14-816f3adcbccd)
## Task Assignment & Roles
Philopateer Wael : Data cleaning and data analysis based on part of questions using SQL, python
 
 Myriam Ehab Milad : Use Python to analyze the data based on the remaining questions.

Omar Ahmed  Abdalah : Design and create an interactive dashboard for data visualization using Tableau.

Huda Adel Hassan : Visualization plots answering forecasting questions ,Review all steps, assist all team members in all steps, and write the final report.

All Team : The entire team should hold a brainstorming session to determine the questions for analysis, thoroughly review and understand all the steps, and prepare the presentation.
![tassk assignment](https://github.com/user-attachments/assets/14e68d7e-7757-47be-b425-1eedd0e41989)
## Key Performance Indicators for HR Analytics
### Employee Turnover & Retention:
Employee Turnover Rate- Departmental Turnover Impact -Work-Life Balance & Retention
 ### Salary & Promotions:
Salary Equity Analysis - Managerial Influence on Promotion - Promotion & Career Growth Factors
### Employee Satisfaction & Performance:
Performance Gap Analysis - Managerial Tenure & Satisfaction - Training Effectiveness
### Dashboard & Decision-Making:
User Adoption Rate of HR Dashboard - Response Time for Insights -  Predictive Accuracy in Turnover Models
![KPI](https://github.com/user-attachments/assets/8dbc9a20-3bb4-4fff-b68f-46fa924ed690)
![KPI Details](https://github.com/user-attachments/assets/00f9df65-1f4c-44bb-8bf5-fd18ec2c7662)
## Stakeholder Analysis
### HR Department: 
Need detailed analytics on employee retention, satisfaction, salary distribution, and promotions. - Use insights to improve HR policies, training programs, and employee engagement strategies.
### Top Management & Executives (CEO, COO, Directors)
Require high-level insights on employee turnover, performance trends, and strategic HR planning. - Focus on business impact, workforce productivity, and cost-effectiveness.
### Finance Department (CFO & Financial Analysts)
Concerned with salary distribution, financial benefits, and workforce cost analysis. - se reports to optimize compensation strategies and control HR budgets.
### Department Managers (Heads of Different Departments)
Require performance insights and employee satisfaction data within their teams. - Use HR analytics to identify retention risks and improve team productivity.
![shark](https://github.com/user-attachments/assets/b1e4bf56-305a-46a2-b3ca-5135fa75b641)
## Data Modeling
### Summary of Relationships:
### PerformanceRating → Employee:
Relationship: One-to-Many (1:*). - Common Column: EmployeeID.

Description: Each employee in the Employee table can have multiple performance ratings in the PerformanceRating table.
### PerformanceRating → RatingLevel:
Relationship: Many-to-One (*:1). - Common Column: SelfRating (in PerformanceRating) and RatingID (in RatingLevel).

Description: Each performance rating can be associated with one rating level in the RatingLevel table.
### PerformanceRating → Satisfiedlevel:
Relationship: Many-to-One (*:1). - Common Column: JobSatisfaction (in PerformanceRating) and SatisfactionID (in Satisfiedlevel).

Description: Each performance rating can be associated with one satisfaction level in the Satisfiedlevel table.
### Employee → EducationalLevel:
Relationship: Many-to-One (*:1). - Common Column: EducationLevelID.

Description: Each employee can be associated with one educational level in the EducationalLevel table.
![Screenshot 2025-03-16 232213](https://github.com/user-attachments/assets/9de50a3d-8107-459b-a895-44b3ad760d79)
