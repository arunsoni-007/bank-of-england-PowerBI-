# Bank of England Customer Analysis Dashboard

This project showcases an in-depth analysis of customer data for the Bank of England. It uses **Excel** for data cleaning and **Power BI** for creating interactive dashboards. The goal is to identify customer trends, demographics, and balance patterns to facilitate data-driven decision-making.

---

## Dashboard Overview

### Key Highlights:
- **Customer Demographics**: Distribution of customers by age, gender, and job classifications.
- **Top Customers**: List of the top 10 customers by account balance.
- **Regional Trends**: Balance distribution across UK regions.
- **Monthly and Quarterly Trends**: Insights into balance changes over time.
- **Gender and Job Classification Insights**: Correlation between job types, gender, and account balances.

![Dashboard Screenshot](replace-with-your-screenshot-path)

---

## Data Cleaning Process

### 1. Data Cleaning with Excel
The raw dataset was processed to ensure consistency and accuracy:

- **Removed Duplicates**: Used the "Remove Duplicates" feature in Excel to ensure unique records.
- **Handled Missing Values**:
  - Identified missing fields using conditional formatting.
  - Replaced missing numerical values (e.g., balances) with `0` or calculated averages.
  - Replaced missing categorical values (e.g., job classifications) with `"Other"`.
- **Standardized Data Formats**:
  - Reformatted dates to `DD-MM-YYYY`.
  - Converted text columns to proper case.
- **Created New Columns**:
  - Added an **Age Group** column to bucket customer ages.
  - Categorized **Job Classifications** into "White Collar," "Blue Collar," or "Other."

### 2. Export for Power BI
The cleaned data was exported as a `.CSV` file for Power BI visualization.

---

## Visualization with Power BI

### Dashboard Features:
- **Interactive Filters**: Slicers for age groups, gender, and job classifications enable dynamic analysis.
- **Visualizations Used**:
  - **Pie Charts**: Distribution of customers by gender and job classification.
  - **Bar Charts**: Insights into balances by education fields and job classifications.
  - **Line Chart**: Analysis of monthly and quarterly balance trends.
  - **Map Visualization**: Geographic distribution of account balances.
- **Insights Panel**: Displays key metrics such as total balance, customer count, and active customers.

---

## Getting Started

### Prerequisites
To view and interact with the Power BI dashboard, you will need:
- **Microsoft Power BI Desktop** (latest version recommended)
- A compatible system to open `.PBIX` files.

### Files Included
- **Cleaned Data**: `cleaned_customer_data.csv`
- **Power BI Dashboard**: `customer_analysis_dashboard.pbix`
- **Raw Data**: `raw_customer_data.xlsx` (if applicable)

---

## Usage
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/bank-of-england-dashboard.git
