# Business Performance Diagnosis

A beginner-friendly business analytics project using **Python (Jupyter Notebook)** and **Power BI** to explore sales, profit, product, regional, and discount performance in the Sample Superstore dataset.

---

##  Project Overview
The goal of this project is to diagnose overall business performance, identify strong and weak operational areas, and present actionable findings through Python visualizations and an interactive Power BI report.

---

##  Dataset Profile
* **Dataset:** Sample Superstore
* **Volume:** 9,994 rows | 21 columns
* **Temporal Period:** 2014 – 2017
* **Data Source:** Kaggle — Sample Superstore Dataset
* **Attributes Covered:** Order records, customer demographics, product categories, shipping modes, sales revenue, discount levels, and net profit margins.

---

##  Tools & Technologies
* **Environment:** Jupyter Notebook
* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Business Intelligence:** Microsoft Power BI (Desktop)

---

##  Project Workflow
1. **Data Ingestion:** Loaded and structurally inspected the raw transactional dataset.
2. **Data Profiling:** Reviewed data schemas, column types, and generated summary statistics.
3. **Data Cleansing:** Verified missing entries and resolved duplicate records.
4. **Type Standardization:** Cast raw order and shipping date strings to explicit `datetime` objects.
5. **Exploratory Data Analysis (EDA):** Performed segmented business analyses across dimensions.
6. **Python Visualization:** Designed static analytical plots using Matplotlib and Seaborn.
7. **Business Intelligence Reporting:** Developed an interactive dashboard in Power BI to track key metrics and performance trends.

---

##  Core Analysis Areas

### 1. Overall Business Performance
A high-level overview evaluating core health variables: total sales revenue, net profit, absolute order counts, unique customer reach, and average discount percentages.

### 2. Yearly Sales and Profit Trends
A comparative timeline tracking historical sales velocity and corresponding net profit margins sequentially from 2014 through 2017.

### 3. Category & Sub-Category Analysis
An evaluation of product distributions comparing total sales generated across high-level categories against net profits earned across micro-level sub-categories.

### 4. Regional Performance
Geographic data segmentation mapping both sales and profit outputs across four major zones: Central, East, South, and West.

### 5. Discount Impact Analysis
An inspection tracking how different promotional discount increments affect customer purchasing volumes and overall business profitability.

---

## 💡 Key Findings
* **Top Category:** **Technology** emerged as the strongest commercial driver, securing the highest yield in both sales volume and absolute profit.
* **Top Sub-Category:** **Copiers** generated the highest overall profit among all individual sub-categories.
* **Bottom Sub-Category:** **Tables** underperformed drastically, recording the lowest net profit and causing a visible drain on returns.
* **Geographic Strengths:** The **West** region proved to be the most lucrative market, establishing top performance in sales and profitability.
* **Geographic Weaknesses:** The **Central** region lagged as the weakest margin zone, accounting for the lowest cumulative profit.
* **Discount Dynamics:** Transactions utilizing a **0% discount** yielded the maximum total profit. In contrast, transactions with a **70% discount** marked the lowest profit levels, frequently translating into net losses.


---

##  Power BI Dashboard
The interactive Power BI canvas provides KPI summary cards alongside dynamic visualizations mapping:
* Yearly Sales vs. Profit Trends
* Volume Sales by Product Category
* Net Profit Distributions by Region
* Granular Profit Breakdown by Sub-Category
* Co-relationship between Discount Levels and Business Profit

The primary report is exported locally as a `.pbix` architecture and can be executed via Power BI Desktop.

---

##  Suggested Repository Structure
```text
Business-Performance-Diagnosis/
├── Business Performance Diagnosis.ipynb
├── Business Performance Diagnosis.pbix
├── Superstore_Cleaned.xls
├── README.md
└── Dashboard
    
```

---

##  Conclusion
The business diagnostic surfaces clear operational guidance for the Superstore entity. To stabilize and expand profit margins, management should prioritize and scale the high-yield **Technology** and **Copier** divisions, particularly by doubling down on market share in the highly responsive **West** zone. 

Conversely, immediate strategic intervention is required in the **Central** region and for the **Table** product line, both of which are currently leaking capital. Finally, the stark margin drop-offs tied to heavier promotions suggest that the current discounting structure should be systematically audited; reducing high-tier discounts (e.g., 70%) in favor of a low-to-zero discount model will help eliminate margin dilution and prevent clear transaction losses.
