# HR Project
![1](https://github.com/user-attachments/assets/688542ad-53b6-496d-9438-92cd038ee162)
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
![3](https://github.com/user-attachments/assets/3ea4d428-f0a3-488b-a3c3-b428bd1748e5)
## Scope:
 >Data extraction, cleaning, and transformation.
  >Turnover analysis and key influencing factors.
  >Salary distribution and influencing variables.
 >Performance evaluation using self and manager ratings.
 >Work-life balance and retention analysis.
 >Predictive modeling for attrition.
 >Dashboard creation using Tableau.
![4](https://github.com/user-attachments/assets/a2dc41c5-592c-4339-80ce-9ecfb19c09eb)
## Timeline and Milestones
Week 1: Analysis & Forecasting Questions Phase 
  
  Week 2-3: Data Cleaning and preprocessing
  
  Week 4-5: Visualization Dashboard
  
  Week 6-7: Final Report & Presentation
  ![5](https://github.com/user-attachments/assets/79f78eaf-fd96-41e0-bef7-8042408e1907)

### Gantt Chart 
![Screenshot 2025-04-24 013854](https://github.com/user-attachments/assets/a660ea12-571b-46e1-bc51-0e254f915796)

## Task Assignment & Roles
Philopateer Wael : Data cleaning and data analysis based on part of questions using SQL, python
 
 Myriam Ehab Milad : Use Python to analyze the data based on the remaining questions.

Omar Ahmed  Abdalah : Design and create an interactive dashboard for data visualization using Tableau.

Huda Adel Hassan : Visualization plots answering forecasting questions ,Review all steps, assist all team members in all steps, and write the final report.

All Team : The entire team should hold a brainstorming session to determine the questions for analysis, thoroughly review and understand all the steps, and prepare the presentation.
![6](https://github.com/user-attachments/assets/b8099baf-e2b1-40e2-a845-6c11e6103263)
## Key Performance Indicators for HR Analytics
### Employee Turnover & Retention:
Employee Turnover Rate- Departmental Turnover Impact -Work-Life Balance & Retention
 ### Salary & Promotions:
Salary Equity Analysis - Managerial Influence on Promotion - Promotion & Career Growth Factors
### Employee Satisfaction & Performance:
Performance Gap Analysis - Managerial Tenure & Satisfaction - Training Effectiveness
### Dashboard & Decision-Making:
User Adoption Rate of HR Dashboard - Response Time for Insights -  Predictive Accuracy in Turnover Models
![7](https://github.com/user-attachments/assets/86c7f7c7-39b2-4dff-a100-df852c0aef2a)
![8](https://github.com/user-attachments/assets/33444884-8844-4016-8f85-4412b931763c)
## Stakeholder Analysis
### HR Department: 
Need detailed analytics on employee retention, satisfaction, salary distribution, and promotions. - Use insights to improve HR policies, training programs, and employee engagement strategies.
### Top Management & Executives (CEO, COO, Directors)
Require high-level insights on employee turnover, performance trends, and strategic HR planning. - Focus on business impact, workforce productivity, and cost-effectiveness.
### Finance Department (CFO & Financial Analysts)
Concerned with salary distribution, financial benefits, and workforce cost analysis. - se reports to optimize compensation strategies and control HR budgets.
### Department Managers (Heads of Different Departments)
Require performance insights and employee satisfaction data within their teams. - Use HR analytics to identify retention risks and improve team productivity.
![9](https://github.com/user-attachments/assets/d2672a60-b4d1-4fde-9ffd-62f0790e6abe)
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
![Screenshot 2025-03-16 232213](https://github.com/user-attachments/assets/9fff8ea1-1cad-4ec8-87ea-242f8d586dcd)

