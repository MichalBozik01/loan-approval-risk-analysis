Loan Approval & Risk Analysis (Excel)

Project Overview
This project analyses loan application data to identify key factors influencing loan approval decisions and loan risk characteristics. The analysis focuses on borrower demographics, income, credit profile, and loan metrics such as Loan-to-Value (LTV) and interest rate.
Business Questions
- What factors are most associated with loan approval vs rejection?
- How do borrower characteristics affect loan risk metrics?
- Are there identifiable borrower profiles with higher risk indicators?

Data Cleaning
Data was cleaned and transformed using Power Query in Excel:
-	Standardized column names and data types
-	Converted loan status codes into readable categories
-	Created age and income ranges
-	Handled missing values logically (e.g., LTV only for approved loans)
-	Removed irrelevant columns

Analysis Approach
-	Segmented borrowers into Approved and Not Approved groups
-	Used PivotTables for aggregation and comparison
-	Focused analysis on:
o	Age
o	Income
o	Gender
o	Credit score
o	LTV and interest rate (approved loans only)

Key Insights
-	Loan rejection is more common among borrowers aged 45–64 with incomes below 5K.
-	Average LTV decreases with age, suggesting greater equity among older borrowers.
-	Borrowers under 25 face the highest average interest rates.
-	Lower income borrowers tend to have higher LTV ratios.
-	Higher credit score groups generally show lower average LTV
-	Certain borrower groups consistently receive higher approval rates
-	Group-level analysis provides more insight than individual loan IDs

Limitations
-	No time-based trends available
-	Limited credit history variables
-	Correlation does not imply causation

Tools Used
-	Microsoft Excel
-	Power Query
-	PivotTables & Charts

Repository Structure
See the folder structure above for raw data, cleaned data, analysis, and documentation.

Author
Michal Božík
Aspiring Data Analyst
(Portfolio project)
