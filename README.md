# HR Attrition Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Columns Explanation](#columns-explanation)
- [Statistical Analysis](#statistical-analysis)
- [Visualization](#visualization)
- [Results](#results)
- [Recommendations](#recommendations)
- [References](#references)

## Project Overview
This analysis investigates the drivers of employee attrition in an organization using a dataset comprising demographic information, job-related attributes, and satisfaction measures. Key objectives include:
- Identifying trends and patterns associated with attrition.
- Understanding the role of job satisfaction, compensation, and career progression in influencing employee decisions to leave.
- Developing a predictive model to forecast attrition.

The findings of this analysis will support data-driven decisions for employee retention, ultimately helping the organization reduce turnover costs and build a more committed workforce. Insights from this analysis can guide effective retention strategies and enhance employee engagement.

Employee attrition is a significant concern for organizations as it leads to high costs associated with recruitment, training, and loss of productivity. Understanding the factors contributing to employee turnover is essential for developing effective retention strategies. This study aims to identify key predictors of attrition within an organization by analyzing demographic, job-related, and satisfaction metrics.

## Columns Explanation
Below is a description of the key columns in the dataset:

- **Attrition**: Indicates whether an employee has left the company (e.g., "Yes" or "No").
- **Business Travel**: Frequency of business travel for the employee (e.g., "Rarely," "Frequently," "No Travel").
- **Age Band**: Age group category of the employee, often grouped as "<25," "25-34," etc.
- **Department**: Primary department where the employee works (e.g., "Sales," "R&D," "HR").
- **Education Field**: Field of study of the employee's highest education (e.g., "Engineering," "Human Resources").
- **Gender**: Gender of the employee (e.g., "Male," "Female").
- **Job Role**: Specific job title or role (e.g., "Analyst," "Manager").
- **Marital Status**: Marital status of the employee (e.g., "Single," "Married").
- **Over Time**: Whether the employee works overtime (e.g., "Yes" or "No").
- **Daily Rate**: Daily wage of the employee.
- **Distance From Home**: Distance between the employee's home and workplace.
- **Job Satisfaction**: Employee's satisfaction level with their job (e.g., 1 = very dissatisfied, 4 = very satisfied).
- **Monthly Income**: Monthly income of the employee.
- **Years at Company**: Number of years the employee has worked at the company.

## Statistical Analysis
Here are key statistics derived from the dataset:
- **Total number of employees**: 1,470
- **Total number of attritions**: 237
- **Total number of current employees**: 1,233
- **Average age of employees**: 37
- **Attrition rate**: 16%

These statistics provide a foundational overview of the workforce and attrition trends.

## Visualization
The dashboard visualizes employee attrition data, highlighting key metrics such as:
- **Total Number of Employees**: 1,470
- **Attrition Count by Department**: Shows which departments have the highest attrition rates.
- **Attrition by Educational Field**: Visualizes attrition rates based on employees' educational background.
- **Attrition by Age Group and Gender**: Displays gender-based attrition in different age groups.

![HR Dashboard](https://github.com/Margnet-data/HR-DATA-LITA-CLASS/blob/main/hrdata.jpg)

The visualization reveals trends in attrition and helps identify areas for focused analysis.

## Results
### Attrition by Department
1. **Departmental Differences**: Attrition varies significantly by department.
2. **High Attrition Departments**: R&D has the highest attrition with 961 employees leaving, followed by Sales with 446 employees.
3. **Low Attrition Departments**: HR has the lowest attrition count at 63 employees.

### Attrition by Education Field
1. **Fields with High Attrition**: The Life Sciences field has the highest attrition count, followed by Medical and Marketing.
2. **Fields with Low Attrition**: Technical Degree and other specializations show relatively lower attrition.

### Attrition by Gender
- **Gender Imbalance in Attrition**: Male employees constitute the majority of attrition cases (63.29%), while females account for 36.71%.

### Attrition by Age Band
1. **Age Group Trends**: Employees aged 25-34 have the highest attrition rate.
2. **Combined Factors**: Age and gender breakdowns indicate that specific age bands exhibit distinct attrition patterns.

## Recommendations
Based on the findings, here are key recommendations to reduce attrition:

1. **Focus on Retention in High-Attrition Departments**:
   - Conduct exit interviews or surveys within high-attrition departments, such as R&D and Sales, to better understand the underlying causes.
   - Implement targeted retention strategies, such as career development programs, performance incentives, or work-life balance initiatives.

2. **Enhance Support for Life Sciences and Medical Education Fields**:
   - Consider specific interventions for employees from Life Sciences and Medical backgrounds, as they exhibit high attrition rates.
   - Tailored training, mentoring, and career development programs could improve retention.

3. **Address Gender-Specific Needs**:
   - Develop policies that address gender-specific factors contributing to attrition. For example, flexible work policies or support for career advancement may help reduce attrition among female employees.

4. **Engage Younger Employees in Career Development Programs**:
   - Given that younger employees have higher attrition rates, establishing mentorship and growth programs could increase retention in this group.
   - Career pathing, regular feedback sessions, and training opportunities may make the organization more attractive to younger employees.

## References
- Dataset used in this analysis: [Attrition Dataset](https://github.com/Margnet-data/HR-DATA-LITA-CLASS/blob/main/HR%20Data.xlsx)
- Additional resources and articles related to attrition trends.

