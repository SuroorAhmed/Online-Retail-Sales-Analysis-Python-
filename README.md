# Online-Retail-Sales-Analysis-Python-
Author:
Suroor Ahmed
Data Analyst | Python | SQL | Data Visualization

--Project Overview--

This project analyzes transactional data from a UK-based online retail business to uncover sales trends, product performance, and customer purchasing behavior. The goal is to demonstrate an end-to-end data analysis workflow using Python, from raw data to actionable business recommendations.

--Business Questions--

This analysis focuses on answering the following questions:

How does revenue change over time?

Which products contribute the most to total revenue?

How is customer spending distributed?

Are there identifiable temporal patterns (monthly or day-of-week)?

What actions can the business take based on these insights?

--Dataset--

Source: UCI Machine Learning Repository – Online Retail Dataset

Time Period: December 2010 – December 2011

Description: Transaction-level data including invoices, products, quantities, prices, customers, and countries

Currency: British Pounds (GBP)

--Tools & Technologies--

Python

pandas – data manipulation and cleaning

numpy – numerical operations

matplotlib – data visualization

Jupyter Notebook

--Project Structure--

online-retail-analysis/
│
├── data/
│   └── raw/
│       └── Online Retail.xlsx
│
├── notebooks/
│   └── 01_online_retail_eda.ipynb
│
├── outputs/
│   └── figures/
│
├── requirements.txt
└── README.md

--Analysis Process--

1. Data Cleaning & Preparation

Removed cancelled transactions

Excluded rows with missing customer identifiers

Handled missing product descriptions

Converted dates to datetime format

Engineered new features including:

Total transaction value

Time-based variables (year, month, weekday)

2. Exploratory Data Analysis (EDA)

Examined overall revenue distribution

Analyzed monthly revenue trends

Identified top revenue-generating products

Assessed customer spending distribution

Explored day-of-week revenue patterns

3. Data Visualization

Line charts for revenue trends

Bar charts for top products

Histograms for customer spending distribution
(All monetary values shown in GBP)

--Key Insights--

Revenue exhibits clear seasonal variation, indicating fluctuating demand throughout the year.

A small number of products drive a large portion of total revenue, highlighting product concentration risk.

Customer spending is highly skewed, with a small group of high-value customers contributing disproportionately to sales.

Revenue varies by day of the week, suggesting opportunities for targeted promotions and operational optimization.

--Business Recommendations--

Focus inventory and marketing efforts on top-performing products.

Develop retention strategies for high-value customers (e.g., loyalty programs).

Align promotions and staffing with seasonal demand patterns.

Use day-of-week insights to optimize marketing campaigns.


--Limitations & Future Work--

No customer demographic data was available.

Analysis does not account for inflation or exchange rate changes.

Future enhancements could include:

Customer segmentation (RFM analysis)

Cohort analysis

Predictive modeling for sales forecasting
