# HR Attrition Analysis Dashboard using Power BI

## Objective :-
The HR Attrition analysis Dashboard using PowerBI project primarily focuses on analyzing employee attrition within an organization. The objective is to identify patterns, trends, and potential factors contributing to employee turnover. By leveraging HR data and utilizing Power BI, the project aims to provide valuable insights to HR professionals, enabling them to make informed decisions and implement targeted strategies to reduce attrition rates.

## Steps Followed :-


**1. Data Collection:**

The initial step involves importing the raw data from a .csv file into Power BI and refining it using Power Query Editor to ensure accuracy and completeness.

**2. Data Refinement:**

Refinement entails removing redundant columns, eliminating duplicates, rectifying errors, and standardizing values for consistency. Additionally, columns are assigned appropriate names and data types are automatically detected.

**3. Data Transformation:**

Within Power Query Editor, a new column named "AttritionCount" is generated using the conditional column feature, where values are determined based on specific conditions (e.g., if attrition = 'Yes', then 1, else 0). This column serves as the basis for calculating various KPIs and charts. Moreover, the Attrition Rate is computed using DAX queries to derive a new measure (Attrition Rate = SUM([AttritionCount]))/SUM([EmployeeCount])) in percentage.

**4. Data Interpretation:**

The analysis stage involves generating diverse visual representations such as bar charts, KPIs, tables, pie charts, and others to extract insights from the data. These visual tools aid in comprehensively understanding the data and communicating findings effectively.

## Summary & Insight's :-

Here's a summary of the key insights derived from the provided data:

- **Total Employees:** The organization has expanded significantly, currently employing 1480 individuals, highlighting substantial growth and scale.

- **Attrition Analysis:** A total of 238 employees left the organization. Among them, 151 were male, and 87 were female, indicating a higher attrition rate among males.

- **Departmental Attrition:** The Research and Development Department experienced the highest attrition rate at 55.88%, suggesting potential areas for improvement in employee retention strategies within this department.

- **Education Field Impact:** Employees in the life sciences field exhibited the highest attrition rate, underscoring the necessity to address retention challenges specific to this area.

- **Job Role Affected:** The Laboratory Technician role demonstrated the highest attrition rate, highlighting the need for targeted retention efforts within this department to mitigate turnover.

- **Attrition Rate by Gender for Different Age Groups:** The attrition count among the age group of 26-35 years was 116, the highest among other age groups, indicating a concentration of attrition within this demographic.

## Conclusion :-

The analysis reveals significant attrition within the organization, notably among males and in the Research and Development Department. High School-educated employees and those in sales roles exhibit higher turnover rates, demanding focused retention efforts. The concentration of attrition among employees aged 25-34 underscores the need for targeted retention strategies tailored to this demographic. Addressing these trends with proactive measures can enhance employee satisfaction, mitigate turnover, and foster a more stable and productive workforce, ensuring sustained organizational growth and success.



