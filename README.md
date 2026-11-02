# Data Cleaning & Reporting Automation

Automates the process of cleaning messy sales data and generating business reports using Python.

## Problem Statement
Raw sales data often contains missing values, duplicate records, and inconsistent formatting (e.g. mismatched casing in city names, mixed gender labels). This project builds an automated pipeline that cleans the data and generates a summary report with visualizations — with a single command.

## Tools Used
- Python
- pandas, numpy
- matplotlib
- openpyxl

## Pipeline Steps
1. **Data Generation** (`generate_data.py`) — creates a synthetic messy sales dataset
2. **Data Cleaning** (`clean_data.py`) — removes duplicates, fills missing values, standardizes text/date formats
3. **Reporting** (`generate_report.py`) — generates an Excel summary and two charts (revenue by city, weekly revenue trend)
4. **Automation** (`run_pipeline.py`) — runs the full pipeline end-to-end in one command

## How to Run
\```bash
pip install pandas numpy matplotlib seaborn openpyxl
python scripts/run_pipeline.py
\```

## Sample Output

**Revenue by City**
![Revenue by City](reports/revenue_by_city.png)

**Weekly Revenue Trend**
![Revenue Trend](reports/revenue_trend.png)

## Key Insight
(Fill this in once you look at your own numbers — e.g. "Bangalore generated the highest revenue after cleaning removed 3 duplicate customer records and standardized inconsistent city name formatting.")