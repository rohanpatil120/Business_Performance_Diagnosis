# Business Performance Diagnosis

A beginner-friendly business analytics project using **Python (Jupyter
Notebook)** and **Power BI** to explore sales, profit, product,
regional, and discount performance in the Sample Superstore dataset.

## Project Overview

The goal is to understand business performance, identify strong and weak
areas, and present findings through Python visualizations and a Power BI
report.

## Dataset

-   **Dataset:** Sample Superstore
-   **Records:** 9,994 rows
-   **Columns:** 21
-   **Period:** 2014--2017
-   **Source:** Kaggle --- Sample Superstore dataset

The dataset includes order, customer, product, shipping, sales,
discount, and profit information.

## Tools & Technologies

-   Python, Jupyter Notebook
-   Pandas, NumPy
-   Matplotlib, Seaborn
-   Microsoft Power BI

## Project Workflow

1.  Loaded and inspected the dataset.
2.  Reviewed data types and summary statistics.
3.  Checked missing values and duplicate records.
4.  Converted order and shipping dates to datetime.
5.  Performed focused business analyses.
6.  Created visualizations in Python.
7.  Built a Power BI report to present key metrics and trends.

## Analysis Performed

### 1. Overall Business Performance

Reviewed total sales, total profit, orders, customers, and discount.

### 2. Yearly Sales and Profit Trends

Compared sales and profit across 2014--2017.

### 3. Category and Sub-Category Analysis

Compared sales by product category and profit by sub-category.

### 4. Regional Performance

Compared sales and profit across Central, East, South, and West.

### 5. Discount Analysis

Explored sales and profit across discount levels.

## Key Findings

-   **Technology** was the highest-performing category by both sales and
    profit.
-   **Copiers** had the highest profit among sub-categories.
-   **Tables** had the lowest profit among sub-categories.
-   The **West** region recorded the highest sales and profit.
-   The **Central** region recorded the lowest profit.
-   The 0% discount group had the highest total profit.
-   The 70% discount group had the lowest total profit and showed a
    loss.

These are observed patterns in the dataset; they do not prove that
discounts caused changes in profit.

## Power BI Report

The Power BI report includes KPI cards and visualizations for: - Sales
and profit by year - Sales by product category - Profit by region -
Profit by sub-category - Discount level and profit

The report is saved as a `.pbix` file and can be opened in Power BI
Desktop.

## Suggested Repository Structure

``` text
Business-Performance-Diagnosis/
├── Business Performance Diagnosis.ipynb
├── Business Performance Diagnosis.pbix
├── Superstore_Cleaned.xls
├── README.md
└── Dashboard_Screenshots/
    ├── Yearly Sales vs Profit Trend.jpeg
    ├── Sales by Product Category.jpeg
    ├── Regional Sales Performance.jpeg
    ├── Regional Profit Performance.jpeg
    ├── Profit by Sub-category.jpeg
    ├── Discount Level vs Sales.jpeg
    └── Impact of Discount on Profit.jpeg
```

Adjust filenames to match the files you upload. If you do not have
permission to redistribute the dataset, do not upload it; instead, link
to its original source.

## How to Run

### Python Notebook

1.  Download or clone this repository.
2.  Install the libraries:
    `pip install pandas numpy matplotlib seaborn jupyter`
3.  Open Jupyter Notebook and open
    `Business Performance Diagnosis.ipynb`.
4.  Update the dataset path if needed, then run the cells.

### Power BI

1.  Open `Business Performance Diagnosis.pbix` in Power BI Desktop.
2.  If prompted, locate the dataset file on your computer.

## Conclusion

This project demonstrates a beginner-friendly analytics workflow: data
inspection, preparation, exploratory analysis, visualization, and
business reporting.

**Author:** Namrata Rai\
**Project Type:** Data Analytics \| Portfolio Project
