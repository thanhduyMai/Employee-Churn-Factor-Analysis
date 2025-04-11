# Employee-Churn-Factor-Analysis

Employee Churn Dataset
1. Introduction
This dataset is a modified version of the "IBM HR Analytics Employee Attrition & Performance" dataset sourced from Kaggle. Certain columns have been removed to focus on key variables pertinent to employee churn analysis.​

2. Data Source
Original Source: Kaggle

Original Dataset Name: IBM HR Analytics Employee Attrition & Performance

Original Dataset Link: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

3. Modifications from the Original Dataset
The following columns have been retained in this modified dataset:​

Age: Age of the employee.​  

BusinessTravel: Frequency of travel for business purposes.​

Department: Department in which the employee works.​

DistanceFromHome: Distance between the employee's residence and workplace.​

Education: Educational level achieved by the employee.​

Gender: Gender of the employee.​

JobInvolvement: Level of involvement in work-related activities.​

JobLevel: Job level within the organization (e.g., 5: CEO/Executive, etc.).​

JobRole: Specific role or position held by the employee.​

JobSatisfaction: Employee's satisfaction with the job (e.g., environment, colleagues, supervisor).​

MaritalStatus: Marital status of the employee.​

MonthlyIncome: Monthly income of the employee.​

OverTime: Indicates if the employee works overtime.​

PerformanceRating: Performance rating of the employee.​

WorkLifeBalance: Assessment of work-life balance.

YearsAtCompany: Number of years the employee has been with the company.​

All other columns present in the original dataset have been removed to streamline the analysis.​

4. Objective of Analysis
Analyze factors influencing employee churn within the organization.​

Develop predictive models to forecast the likelihood of employee attrition based on the retained variables.​

5. Usage Instructions
Load the dataset into Python using Pandas:​

  import pandas as pd
  df = pd.read_excel("Employee-Churn-Feature.xlsx")
Utilize appropriate analytical and modeling techniques to achieve the objectives outlined above.​

6. Notes
This dataset has undergone preprocessing to remove certain columns. For analyses requiring the omitted variables, please refer to the original dataset.​

For any questions or clarifications, please contact the dataset modifier.​

