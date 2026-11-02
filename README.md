# 📺 OTT Customer Churn & Revenue Analysis | Python, SQL & Power BI

## 1. Project Overview

This project focuses on analyzing customer churn and subscription behaviour in an OTT (Over-The-Top) streaming platform to understand customer retention, subscription patterns, and revenue performance.

The project follows an end-to-end data analytics workflow, starting with dataset loading and data cleaning using Python, performing Exploratory Data Analysis (EDA), visualizing trends using Matplotlib and Seaborn, extracting business insights through PostgreSQL queries, and developing an interactive Power BI dashboard.

The main objective is to identify factors contributing to customer churn, understand subscription preferences, analyze revenue trends, and provide actionable recommendations to improve customer retention.

**Project Objectives:**
- Analyze customer subscription and cancellation patterns.
- Calculate the overall customer churn rate.
- Compare churn across monthly and annual subscription plans.
- Identify customer segments with higher churn rates.
- Analyze revenue and subscription performance.
- Understand customer retention behaviour.
- Build an interactive Power BI dashboard.
- Provide data-driven recommendations to reduce customer churn.

---

## 2. Dataset

The project uses an OTT customer subscription dataset containing customer details, subscription information, payment details, and churn status.

**Dataset Information:**
- Dataset Format: CSV
- Data Type: Structured Data

**Important Dataset Columns:**

| Column Name | Column Name |
|---| ---|
customerid | subscription_start_date|
subscription_type | renewal_date |
plan_type | contract_type | 
cancellation_date | cancellation_reason |
monthly_charges | cltv |
churn_score | churn_flag |
customer_name | country |
state | gender | dob | 
complaint_date | escalations | csat_score

---

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Python development and analysis |
| PostgreSQL | Database management |
| SQL | Customer churn and revenue analysis |
| Microsoft Power BI | Interactive dashboard development |
| Power Query | Data transformation |
| DAX | KPI calculations and measures |
| Git & GitHub | Version control and project documentation |

---

## 4. Project Workflow

### Step 1: Data Loading using Python
- Imported the OTT customer dataset using Pandas.
- Explored the dataset using `head()`, `info()`, and `describe()`.
- Checked dataset dimensions and column data types.
- Identified numerical and categorical variables.

### Step 2: Exploratory Data Analysis (EDA)
- Analyzed customer demographics and subscription patterns.
- Examined customer churn distribution.
- Compared monthly and annual subscription behaviour.
- Evaluated revenue contribution across customer segments.
- Identified relationships between customer activity and churn.
- Generated statistical summaries to understand customer behaviour.

### Step 3: Data Cleaning & Preprocessing
- Identified and handled missing values.
- Checked and removed duplicate records where appropriate.
- Corrected inconsistent data formats.
- Converted date columns into appropriate datetime formats.
- Standardized categorical variables.
- Checked data types and handled outliers where appropriate.
- Prepared the cleaned dataset for further analysis.

### Step 4: Data Visualization using Matplotlib & Seaborn
Created visualizations to understand customer behaviour and churn patterns.

**Visualizations Included:**
- Bar charts for subscription-wise churn analysis.
- Count plots for customer distribution.
- Pie charts for churn distribution.
- Histograms for age and revenue distribution.
- Box plots for comparing customer segments.
- Heatmaps to identify correlations between numerical variables.

### Step 5: SQL Analysis using PostgreSQL
- Imported the cleaned dataset into PostgreSQL.
- Created database tables for customer analysis.
- Executed SQL queries to calculate churn rates.
- Analyzed churn across subscription types.
- Identified customer segments with higher cancellation rates.
- Evaluated revenue contribution by subscription category.
- Used `GROUP BY`, `ORDER BY`, `CASE WHEN`, aggregate functions, and subqueries.
- Extracted meaningful insights to support business decisions.

### Step 6: Power BI Dashboard Development
- Imported the cleaned dataset into Power BI.
- Used Power Query for data transformation.
- Created relationships and prepared the data model.
- Developed DAX measures for important KPIs.
- Designed interactive visualizations and charts.
- Added slicers and filters for dynamic customer analysis.
- Created a dashboard to monitor churn and revenue performance.

### Step 7: Project Report
- Prepared a detailed analytical report.
- Documented the project objectives and methodology.
- Included data cleaning and EDA findings.
- Presented important SQL analysis results.
- Added Power BI dashboard screenshots.
- Provided business recommendations to improve customer retention.

---

## 5. Power BI Dashboard

The interactive dashboard provides an overview of customer churn, subscription performance, and revenue trends.

**Key Performance Indicators (KPIs):**
- Total Customers
- Active Customers
- Churned Customers
- Overall Churn Rate
- Total Revenue
- Average Revenue Per Customer

**Dashboard Visualizations:**
- Customer Churn by Subscription Type.
- Monthly vs Annual Subscription Analysis.
- Churn Distribution by Age Group.
- Revenue by Subscription Category.
- Customer Distribution by Gender.
- Churn Trends and Customer Retention Analysis.
- Payment Method Analysis.

**Interactive Features:**
- Subscription Type Slicer.
- Gender Filter.
- Age Group Filter.
- Dynamic KPI Cards.
- Interactive Charts and Graphs.

## 6. Key Findings & Business Insights

The analysis helped identify important customer retention patterns and revenue trends.

**Key Findings:**
- Identified an overall customer churn rate of **28.6%**.
- Monthly subscribers experienced a higher churn rate of **55.6%** compared to **8.3%** for annual subscribers.
- Identified subscription duration as an important factor associated with customer retention.
- Analyzed customer segments with higher cancellation rates to identify potential retention opportunities.
- Evaluated subscription revenue patterns to understand recurring revenue performance.

**Business Recommendations:**
- Encourage monthly subscribers to migrate to annual subscription plans through exclusive discounts.
- Introduce personalized retention campaigns for high-risk customers.
- Offer loyalty rewards and subscription benefits to improve customer retention.
- Monitor customer engagement and viewing behaviour to identify potential churn risks.
- Improve subscription plans based on customer preferences and payment behaviour.

---

## 7. Project Results

- Successfully performed end-to-end data analysis using Python and PostgreSQL.
- Cleaned and transformed customer subscription data.
- Identified key churn patterns through EDA and data visualization.
- Extracted customer retention and revenue insights using SQL.
- Developed an interactive Power BI dashboard.
- Generated actionable recommendations to improve subscription retention and revenue performance.
- Prepared a comprehensive project report documenting the analysis.

---

## 8. How to Run the Project

Follow these steps to reproduce the analysis.

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/OTT-Customer-Churn-Analysis.git
```

### Step 2: Navigate to the Project Folder

```bash
cd OTT-Customer-Churn-Analysis
```

### Step 3: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter sqlalchemy psycopg2-binary
```

### Step 4: Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the Python notebook and execute the cells sequentially to perform data loading, cleaning, EDA, and visualization.

### Step 5: Run PostgreSQL Queries

- Install and open PostgreSQL using pgAdmin.
- Create a database for the OTT customer analysis.
- Import the cleaned dataset into PostgreSQL.
- Open the provided SQL script.
- Execute the queries to analyze churn and revenue patterns.

### Step 6: Open the Power BI Dashboard

- Open the `.pbix` file using Power BI Desktop.
- Update the dataset connection if required.
- Refresh the data.
- Explore the dashboard using interactive charts and slicers.

---

## 9. Repository Structure

```text
OTT-Customer-Churn-Analysis/
│
├── Dataset/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── Python/
│   └── customer_churn_analysis.ipynb
│
├── SQL/
│   └── churn_analysis_queries.sql
│
├── PowerBI/
│   └── OTT_Churn_Dashboard.pbix
│
├── Reports/
│   └── OTT_Churn_Analysis_Report.pdf
│
├── Screenshots/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 10. Conclusion

This project demonstrates practical knowledge of the end-to-end data analytics process, including data cleaning, exploratory data analysis, statistical visualization, SQL querying, and business intelligence reporting.

By combining Python, PostgreSQL, and Power BI, the project transforms raw customer subscription data into meaningful insights that help understand customer churn, improve retention strategies, and support data-driven business decisions.

---


---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
