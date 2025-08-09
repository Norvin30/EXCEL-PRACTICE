This Folder contains an Excel file designed to practice logical formulas in Microsoft Excel using a sample employee dataset.
The dataset includes employee details such as department, experience, salary, performance score, and employment type.

The file demonstrates the use of:

SUM

IF

Nested IF

IF + AND

IF + OR

IF + NOT

Dataset Columns
Employee – Employee name

Department – HR, IT, or Finance

Experience_Years – Years of work experience

Salary – Annual salary in USD

Performance_Score – Score out of 100

Full_Time – Yes or No

Finance department total salary – Total salary for all Finance employees

High Performer – Based on performance score (>85)

Performance Rating – Excellent, Good, or Average using Nested IF

Bonus Eligibility – Based on AND condition (Experience ≥ 5 AND Performance ≥ 85)

Training – Based on OR condition (Experience < 3 OR Performance < 70)

Work – Full-Time or Part-Time using IF + NOT

Practice formulas used in file:
Practice Formulas
Here are the formulas used in the file:

1) SUM (with filter for Finance)

=SUMIF(B2:B11,"Finance",D2:D11)

2) IF – High Performer

=IF(E2>85,"High Performer","Needs Improvement")

3) Nested IF – Performance Rating

=IF(E2>=90,"Excellent",IF(E2>75,"Good","Average"))

4) IF + AND – Bonus Eligibility

=IF(AND(C2>=5,E2>=85),"Bonus Eligible","Not Eligible")

5) IF + OR – Training Requirement

=IF(OR(C2<3,E2<70),"Needs Training", "No Training needed")

6) IF + NOT – Work Type

=IF(NOT(F2="Yes"),"Part Time","Full Time")

Purpose
This project is ideal for:

Learning and practicing Excel logical formulas

Understanding how to combine conditions

Building a portfolio-ready Excel file for GitHub



