# DataCraft: Consumer Behavior & Shopping Analytics

An end-to-end data analytics project that processes raw customer transaction records into actionable insights for retail marketing and retention strategies. This project covers the full pipeline: data cleaning in Python, relational analysis in MySQL, and executive reporting via Power BI.

## 📌 Project Overview
DataCraft models a retail analytics pipeline using a dataset of **3,900 purchase records** containing 18 distinct customer and transactional attributes. The goal is to move past basic summary statistics to isolate purchasing trends, evaluate discount effectiveness, and segment customers by loyalty.

## 🛠 Tech Stack
* **Python (Pandas, NumPy, Matplotlib, Seaborn):** Used for missing value imputation, data cleaning, and exploratory data analysis (EDA).
* **MySQL:** Used for relational storage, complex aggregations, and performance-driven customer segmentation.
* **Power BI:** Used to build an interactive, stakeholder-facing dashboard for trend visualization and strategic reporting.

## 📊 Core Analytics Workflow

### 1. Data Cleaning & Preprocessing (Python)
* Handled missing data anomalies during the preprocessing phase, specifically resolving data gaps within the `Review Rating` field.
* Structured data types and exported clean files for relational database integration.

### 2. Database Analysis (MySQL)
* Engineered queries to evaluate customer segments against total spending power.
* Isolated how discount frequencies impact overall cart values and profit margins.
* Compared the purchasing behaviors of subscribers versus non-subscribers to measure retention.

### 3. Business Intelligence (Power BI)
* Developed an interactive dashboard tracking key performance indicators (KPIs) like customer lifetime value (CLV), purchase frequency, and preferred shipping methods across high-value tiers.

