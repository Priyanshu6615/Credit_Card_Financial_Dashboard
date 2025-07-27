Credit Card Financial Dashboard real time end to end project using Power BI,SQL server and excel.

This Power BI report shows insights into credit card customers and transactions. It highlights where revenue comes from, how customers use their cards, trends over time, covering revenue drivers, demographics, card usage patterns, and quarterly trends.

Steps to Build the Dashboard

🔹 Step 1: Data Cleaning & Modeling

Used Power Query to remove duplicates/nulls and standardize date formats.

Parsed Transaction Date and Transaction Time, extracted Year, Quarter, Month, Week, and Hour.

Created a dedicated Date dimension table for time‑intelligence.


🔹 Step 2: Data Relationships

Linked Customer, Card, and Transaction tables via Customer‑ID and Card‑ID keys.

Validated referential integrity and filtered out orphan records.


🔹 Step 3: KPI Creation (DAX)

Total Revenue, Total Transactions, Total Interest Earned

Revenue per Customer, Transactions per Card Type

Average Transaction Value, Transaction Volume by Channel


🔹 Step 4: Visualizations
Bar Chart – Top 5 States by Revenue

Clustered Bar – Revenue by Income Group & Education

Line Graph – Weekly Revenue Trend

Stacked Column – Quarterly Transaction Volume & Amount

Matrix – Job Role vs. Revenue & Interest

Pie Chart – Expenditure by Category (Bills, Entertainment, Fuel, Grocery, Travel)

Treemap or Ribbon – Card Usage Method (Swipe, Chip, Online)


🔹 Step 5: Interactivity 

Slicers for Year, Quarter, State, Card Tier, Income Group

Tooltips showing breakdowns (e.g., avg. spend, txn count)

Bookmarks & Buttons for guided storytelling (e.g., “Customer Overview” → “Transaction Trends”)


🛠 Tools & Technologies Used

Power BI Desktop: Data modeling, DAX measures, and interactive report design.

DAX: Advanced calculations for KPIs and time‑intelligence functions.

SQL: Cross‑verified aggregates and ran supplementary queries during data profiling.


🎯 Key Insights
Top States: TX, NY, CA drive the highest credit‑card revenue.

High‑Income & Graduate Customers account for the largest share of spending.

Age Groups 30–40 & 60+ show strongest revenue contributions.

Q4 peaks in both transaction volume and amount.

Platinum & Blue Tiers outperform other card levels in revenue and interest earned.

Online & Chip Transactions dominate usage channels.

