# Financial Report Dashboard – Power BI
An end-to-end Power BI dashboard analyzing revenue, expenses, and profitability across three business lines: Nutrition and Food Supplements, Sports Equipment, and Sportswear.

## Overview
This project tracks financial performance (Revenue, Expense, Gross Profit, Net Profit) with monthly trends, budget-vs-target comparisons, and full income/expense statements broken down by business line and quarter. All KPIs were custom-built using DAX measures.

## Tools
- Power BI Desktop

## Dashboard Pages
1. **Overview** – KPI summary, monthly revenue/expense trends, revenue & expense vs target by business line
2. **Expense Breakdown** – COGS, Opex, and Interest & Tax breakdown by month and business line
3. **Income / Expense Breakdown** – Full income statement and expense statement by quarter, business line, with narrative insights
4. **Profit Breakdown** – Operating profit, EBIT, EBIT margin, and net profit margin trends

## Dashboard Preview
![Overview](screenshots/1_overview.png)
![Expense Breakdown](screenshots/2_expense_breakdown.png)
![Income/Expense Breakdown](screenshots/3_income_expense_breakdown.png)
![Profit Breakdown](screenshots/4_profit_breakdown.png)

## DAX Measures
This dashboard uses 33 custom DAX measures covering core financial metrics, month-over-month growth, target/budget comparisons, and dynamic conditional formatting. Full documentation with code and explanations: [docs/DAX_Measures.md](docs/DAX_Measures.md)

## Insights
- Nutrition and Food Supplements led Q1 sales at 405,450, while consulting revenue peaked in Q3
- Sports Equipment had its highest sales in Q4 at 1,950,000
- Sportswear showed strong Q1 sales at 1,351,500 but declined gradually across quarters

## Reference
KPI definitions and formulas used in this project are documented in [docs/Finance_Analysis.pdf](docs/Finance_Analysis.pdf).
