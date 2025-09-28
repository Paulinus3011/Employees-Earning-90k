# Employees-Earning-90k

## Employees Earning Below 90k – Dashboard

This Power BI dashboard provides an analytical breakdown of employees based on their earnings, focusing specifically on those earning less than $90,000 annually. The dashboard highlights employee distribution across regions, departments, and gender, while also offering quick insights into overall workforce composition.


## Overview

🔢 Key Metrics

Total Employees: 869

Employees Earning < 90k: 614

Employees Earning > 90k: 255

🌍 Breakdown by Region

Texas → 238 employees

Florida → 221 employees

Mississippi → 96 employees

📌 Insight: Texas and Florida account for nearly 75% of employees earning < 90k.

🏢 Breakdown by Department

Highest concentration: Product Management (61), HR (59), Sales (58)

Lowest concentration: Marketing (43), Accounting (43)

📌 Insight: Distribution across departments is balanced, with minor variations.

👩‍💼 Breakdown by Gender

Equal representation of both genders in the < 90k group (614 each side in the dataset).

📌 Insight: No significant gender disparity among employees earning < 90k.

## Data Dictionary

Field	Description	Data Type	Example Values
Employee_ID	Unique identifier assigned to each employee	Integer	101, 205, 322
Employee_Name	Name of the employee	Text	John Doe, Jane Smith
Gender	Gender of the employee	Categorical	Male, Female
Department	Functional area where the employee works	Categorical	HR, Sales, Engineering, Accounting
Location	Geographical location/region of the employee	Categorical	Texas, Florida, California, etc.
Salary	Annual salary of the employee	Numeric (USD)	75,000; 110,000
Salary_Band	Categorized salary band (used for segmentation)	Derived Field	<90k, >90k
Earning_Status	Boolean flag indicating if an employee earns < 90k	Boolean	True, False

## Data Source

Dataset originated from an employee payroll/HR system (Excel extract or SQL export).

Contains 869 employee records with salary and demographic details.

Data was cleaned, transformed, and modeled in Power BI for dashboard reporting.

## Insights

71% of employees earn below 90k, while 29% earn above 90k.

Texas & Florida dominate the distribution.

Product Management & HR slightly lead departmental counts.

Gender parity exists in this salary band.

## Usage Scenarios

HR Teams: Identify regions or departments with lower salary clusters.

Management: Track pay distribution for workforce planning.

Analysts: Monitor salary parity across demographics.

## Future Enhancements

Add time-based trends (salary growth per year).

Standardize location field (fix “California” duplication).

Introduce advanced filters (experience level, education).

Build salary distribution histograms for more granular insights.

Los Angeles → 44 employees

California (duplication issue noted) → 15 employees
