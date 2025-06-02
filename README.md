# Credit-Card-Transaction-Analysis
InsightsProject Objective To develop a comprehensive credit card Monthly dashboard that providesreal-time insights into key performance metrics and trends, enablingstakeholders to monitor and analysis credit card operations effectively.

DAX Queries
•	Current_month = MONTH(credit_card[Transaction_date].[Date]).
•	Current_Month_Reveneue = CALCULATE(SUM(credit_card[Revenue]),FILTER(ALL(credit_card),credit_card[Current_month]=max(credit_card[Current_month])))
•	Previous_Month_revenue = CALCULATE(SUM(credit_card[Revenue]),PREVIOUSMONTH(credit_card[Transaction_date].[Date]) )
•	Revenue = credit_card[Annual_Fees]+credit_card[Total_Trans_Amt]+credit_card[Interest_Earned]

Project Insights
•	Overall revenue is 55M.
•	Total interest earn is 7.84M and transaction is 45M.
•	Blue & Silver credit card are contributing to 93% of overall transactions.
•	Expenses type, Job Category, Card category and Use chip revenue.

