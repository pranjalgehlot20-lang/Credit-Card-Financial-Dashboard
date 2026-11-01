💳 Credit Card Financial Dashboard | Power BI & SQL

1. Project Overview

This project analyses credit card customer behaviour, transaction activity and financial performance using SQL and Power BI.

The objective is to provide stakeholders with a consolidated view of financial performance, customer demographics, transaction patterns and key operational indicators.

The dashboard consists of two report pages:

* Credit Card Customer Report: Customer demographics, income groups, geographic distribution and revenue contribution.
* Credit Card Transaction Report: Transaction performance, card categories, expenditure patterns and quarterly trends.

2. Business Problem — Why?

Financial institutions need to monitor customer activity and credit card performance to understand revenue generation, transaction behaviour and customer engagement.

This project addresses the following business questions:

* How much revenue and interest are generated?
* Which customer segments contribute the most revenue?
* Which card categories dominate transaction activity?
* How does performance change across weeks and quarters?
* Which geographical regions contribute the most?
* What are the customer activation and delinquency rates?

3. Tools & Technologies

* Power BI: Dashboard development and data visualisation.
* SQL: Database creation, data extraction and preparation.
* DAX: Calculated columns and performance measures.
* CSV: Source datasets.

4. Dataset Structure

The project uses four CSV datasets:

* credit_card.csv
* customer.csv
* cc_add.csv
* cust_add.csv

The datasets contain customer demographics, credit card details and transaction-related information.

The additional datasets contain the Week 53 records and were combined with the main datasets for the analysis.

5. Analytical Approach — How?

Step 1: Data Preparation

* Prepared the source CSV files.
* Created database tables using SQL.
* Imported customer and credit card data.

Step 2: Data Modelling & Processing

* Loaded the prepared data into Power BI.
* Organised the data for customer and transaction analysis.
* Prepared fields required for dashboard reporting.

Step 3: DAX & Calculated Measures

Applied DAX to create analytical fields and measures, including:

* Age Group: Segmented customers into age categories.
* Income Group: Classified customers into Low, Medium and High income groups.
* Week Number: Extracted week numbers from transaction dates.
* Revenue: Combined annual fees, transaction amount and interest earned.
* Current Week Revenue: Calculated revenue for the latest reporting week.
* Previous Week Revenue: Calculated revenue for the preceding week.

Step 4: Dashboard Development

Created two report pages with KPI cards, charts, tables and interactive filters.

6. Dashboard Reports

A. Credit Card Customer Report

Focuses on customer demographics and financial contribution.

Key metrics:

* Total Revenue
* Total Interest
* Total Income
* Customer Satisfaction Score (CSS)

Visual analysis:

* Revenue by gender.
* Customer distribution by age group.
* Revenue by customer occupation.
* Top contributing states.
* Salary and income groups.
* Dependent count.
* Marital status.
* Education level.

B. Credit Card Transaction Report

Focuses on transaction activity and card performance.

Key metrics:

* Total Revenue
* Total Interest
* Transaction Amount
* Transaction Count

Visual analysis:

* Quarterly revenue and transaction count.
* Revenue by card category.
* Revenue by expenditure type.
* Revenue by education.
* Revenue by customer occupation.
* Revenue by chip usage.
* Customer acquisition cost by card category.

7. Key Findings — What Did the Analysis Reveal?

The following findings were calculated using the four supplied CSV datasets.

Overall Financial Performance

* Total Revenue: 56.52M
* Total Interest Earned: 7.98M
* Total Transaction Amount: 45.53M
* Total Annual Fees: 3.00M
* Transaction Count: 667,234
* Unique Customers: 10,293

Revenue is calculated as:

Annual Fees + Total Transaction Amount + Interest Earned

Weekly Performance — Week 52 vs Week 53

Metric	Week-over-Week Change
Revenue	+28.77%
Transaction Amount	+35.04%
Transaction Count	+3.39%
Customer Count	+12.80%

Key finding: Revenue increased by 28.77% between Week 52 and Week 53, accompanied by an increase in transaction amount and customer activity.

Revenue by Gender

* Male Customers: 30.93M
* Female Customers: 25.59M

Male customers contributed a higher share of total revenue in the analysed dataset.

Geographic Performance

The three highest-revenue states were:

* Texas (TX): 13.02M
* New York (NY): 12.97M
* California (CA): 12.90M

Together, these three states contributed approximately 68.81% of total revenue.

Card Category Performance

Blue and Silver card categories together accounted for approximately 96.06% of the calculated transaction count.

Customer Operational Indicators

* Activation Rate: 57.46%
* Delinquency Rate: 6.06%
* Average Customer Satisfaction Score: 3.19

8. Business Insights & Recommendations

1. Monitor Weekly Revenue Growth

The 28.77% increase in Week 53 revenue highlights the importance of tracking weekly financial performance alongside transaction activity.

2. Understand Customer Revenue Contribution

The gender-based revenue breakdown helps stakeholders examine differences in customer contribution and engagement.

3. Monitor Card Category Performance

Blue and Silver cards account for a substantial share of transaction activity. Their performance deserves continued monitoring.

4. Focus on Geographic Performance

TX, NY and CA contribute approximately 68.81% of revenue. Further analysis can help identify regional opportunities.

5. Improve Customer Activation

With an activation rate of 57.46%, stakeholders can investigate opportunities to improve customer activation and engagement.

6. Monitor Delinquency

The delinquency rate of 6.06% provides a useful indicator for monitoring credit-related customer performance.

9. Conclusion

This project demonstrates how SQL, DAX and Power BI can transform customer and transaction data into meaningful financial insights.

The two dashboard reports provide visibility into revenue generation, customer demographics, card category performance, transaction activity and key financial indicators.

The findings support data-driven monitoring of customer engagement and financial performance.

10. Project Structure

Credit-Card-Financial-Dashboard/
│
├── Credit Card Financial Dashboard-Customer.pdf
├── Credit Card Financial Dashboard-Transaction.pdf
├── Credit_Card_Financial_Dashboard_Weekly_Report.pdf
│
├── SQL Query - Financial Dashboard Data.sql
│
├── credit_card.csv
├── customer.csv
├── cc_add.csv
├── cust_add.csv
│
└── README.md

11. How to Use

1. Clone or download this repository.
2. Review the CSV source datasets.
3. Execute the SQL script to create and populate the database tables.
4. Review the exported customer and transaction dashboard reports.
5. Refer to the weekly status report for the calculated KPIs and findings.

Note: The editable Power BI .pbix file is not currently included. It will be added to this repository once recovered or recreated.

⸻

All calculated findings are based on the supplied CSV datasets. Weekly comparisons use Week 52 and Week 53 records. Minor differences from the original dashboard or reference report may arise from report filters and measure definitions.
