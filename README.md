# Sales Analysis Project 

## Project Overview

This project analyzes supermarket sales transaction data to generate business insights using a complete analytics workflow. The objective was to evaluate sales performance across store branches and build a dashboard summarizing key performance metrics.

The project demonstrates integration of:

- Python (data loading and inspection)
- SQL via DuckDB (data aggregation)
- Tableau Public (data visualization and dashboarding)
- Git and GitHub (version control)

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- DuckDB (SQL queries on in-memory data)
- Tableau Public (dashboard creation)
- Jupyter Notebook (analysis environment)
- Git (version control)

---

## Dataset

Dataset: Supermarket Sales Dataset (Kaggle)

The dataset contains transactional sales data including:

- Invoice ID
- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Total Sales
- Payment Type
- Rating

---

## Project Workflow

### 1. Data Loading (Python)

- Imported the CSV dataset into a Pandas DataFrame.
- Inspected dataset structure, shape, and column names.
- Verified data was loaded correctly.

### 2. Data Aggregation (SQL with DuckDB)

- Used SQL queries within Python to aggregate sales data.
- Calculated total sales per branch.
- Calculated total number of transactions.
- Calculated total items sold.
- Sorted results by highest-performing branch.

### 3. Export for Visualization

- Exported aggregated results to a new CSV file.
- Prepared structured dataset for use in Tableau.

### 4. Tableau Dashboard

- Connected Tableau Public to the aggregated CSV file.
- Built visualizations showing total sales by branch.
- Added transaction and quantity metrics for comparison.
- Created a dashboard summarizing branch performance.

Insert Tableau Public dashboard link here.

---

## Key Insights

- Identified the highest-performing branch by total revenue.
- Compared transaction volume versus revenue contribution.
- Demonstrated how SQL aggregation supports executive-level reporting.

---

## Project Structure

SalesAnalysis/

- supermarketsales.csv (raw dataset)
- sales_analysis.ipynb (Python and SQL analysis)
- sales_summary.csv (aggregated data for Tableau)
- README.md
- .gitignore

---

## What This Project Demonstrates

- End-to-end analytics workflow
- Data inspection and validation
- SQL proficiency within a Python environment
- Data preparation for BI tools
- Dashboard creation and reporting
- Version-controlled project management

---

## Future Improvements

- Time-series analysis of monthly sales trends
- Product line profitability analysis
- Customer segmentation analysis
- Expanded Tableau dashboard features
