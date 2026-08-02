# Credit Card Financial Dashboard (Power BI)

This is a Power BI dashboard I built to practice end-to-end data analysis — starting from raw data in SQL, all the way to a working weekly report with insights. I followed a tutorial by Rishabh Mishra on YouTube and built the project alongside it to actually understand how each step works, instead of just copying the final dashboard.

## What this project is about

The goal was to build a weekly credit card financial dashboard that gives a quick, real-time view of how the business is performing — things like revenue, transaction trends, and customer activity — so that anyone looking at it can track key numbers without digging through raw data every time.

## Tools used

- **SQL** – to store and query the raw transaction and customer data
- **Power BI** – for building the dashboard and data model
- **DAX** – for writing calculated columns and measures
- **Excel/CSV** – as the initial data format before loading into SQL

## How the project was built

1. **Got the data** – Started with a CSV file containing credit card transaction and customer details.
2. **Loaded it into SQL** – Created tables in SQL and imported the CSV data into them, so the data could be queried properly instead of working directly off a spreadsheet.
3. **Connected SQL to Power BI** – Pulled the data from the SQL database into Power BI for modeling and visualization.
4. **Wrote DAX measures** – Created custom columns and calculations, for example:
   - Grouping customers by **age** and **income** brackets using `SWITCH` statements
   - Calculating **weekly revenue** (annual fees + transaction amount + interest earned)
   - Comparing **current week vs previous week revenue** using `CALCULATE` and `FILTER`
5. **Built the dashboard** – Designed visuals to show trends, week-over-week changes, and breakdowns by customer segments.

## Key insights from the dashboard (as of Week 53 / Dec 31)

- Revenue grew by **28.8%** week-over-week
- Total revenue for the year came out to around **57M**
- Interest earned contributed about **8M**, and total transaction amount was **46M**
- Male customers contributed slightly more to revenue (31M) compared to female customers (26M)
- **Blue and Silver** card categories made up **93%** of all transactions
- **Texas, New York, and California** together accounted for **68%** of the business
- Overall card **activation rate** stood at **57.5%**
- Overall **delinquent rate** was **6.06%**

## What I learned from this

- How to move data from a raw CSV into a proper SQL database and query it
- Writing DAX logic for grouping data and doing time-based comparisons (like week-over-week revenue)
- Structuring a dashboard so it actually answers business questions, not just displays charts
- Reading a dataset and pulling out insights that matter (customer segments, geography, product mix)

I built it hands-on to learn the workflow, not just to watch — all the SQL queries, DAX code, and dashboard structure were written and tested by me while following along.
