#  Pizza Sales Analysis | SQL Data Analytics Project

A SQL-based data analytics project focused on exploring pizza sales, understanding customer ordering patterns, evaluating product performance, and generating business insights to support data-driven decisions.

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset](#-dataset)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [How to Run](#-how-to-run)
- [Analysis Pipeline](#-analysis-pipeline)
- [Data Cleaning and Preparation](#-data-cleaning-and-preparation)
- [SQL Analysis](#-sql-analysis)
- [Key Performance Indicators](#-key-performance-indicators)
- [Sales Analysis](#-sales-analysis)
- [Product Performance Analysis](#-product-performance-analysis)
- [Models Compared](#-models-compared)
- [Evaluation Metrics](#-evaluation-metrics)
- [Key Findings](#-key-findings)
- [Business Recommendations](#-business-recommendations)
- [Technologies Used](#-technologies-used)
- [Skills Demonstrated](#-skills-demonstrated)
- [Project Limitations](#-project-limitations)
- [Future Improvements](#-future-improvements)
- [License](#-license)
- [Author](#-author)

---

## 📊 Project Overview

The Pizza Sales Analysis project uses SQL to analyze pizza order and sales data and extract meaningful business insights.

The project focuses on understanding overall revenue, order volume, product popularity, sales trends, and customer ordering behavior. SQL queries help transform transactional data into useful information for business reporting and decision-making.

This project demonstrates the practical application of SQL for data exploration, aggregation, ranking, date-based analysis, and business performance measurement.

## 💼 Business Problem

Pizza businesses need to understand which products perform well, when customers place orders, and how sales are distributed across pizza categories and sizes.

Without structured analysis, it can be difficult to identify sales trends, monitor performance, and make informed inventory or promotional decisions.

This project aims to answer questions such as:

- What is the overall sales performance?
- How much revenue is generated from pizza orders?
- How many orders and pizzas are sold?
- Which pizza categories and sizes perform best?
- Which pizzas generate the highest revenue?
- What are the daily and monthly sales trends?
- Which products contribute most to total sales?
- How can sales data support better business decisions?

## 🎯 Project Objectives

- Analyze pizza sales data using SQL.
- Explore the structure and quality of transactional data.
- Calculate key sales performance indicators.
- Analyze revenue and order trends over time.
- Identify top-performing and low-performing products.
- Compare pizza categories and sizes.
- Apply SQL aggregation, joins, subqueries, and window functions where appropriate.
- Generate actionable insights for business planning.
- Strengthen practical SQL and business analytics skills.

## 🗂️ Dataset

The project uses pizza sales transaction data containing information about orders and pizza products.

Depending on the dataset schema, the data may include fields such as:

| Field | Description |
|---|---|
| `order_id` | Identifier for an order |
| `order_date` | Date of the order |
| `order_time` | Time of the order |
| `pizza_id` | Identifier for a pizza product |
| `pizza_name` | Name of the pizza |
| `pizza_category` | Category of the pizza |
| `pizza_size` | Size of the pizza |
| `quantity` | Number of pizzas ordered |
| `unit_price` | Price per pizza |
| `total_price` | Revenue associated with an order line |

These are common fields in pizza sales datasets, not a verified list of every column in this repository. Actual column names and data types should be confirmed from the project files.

## 📁 Project Structure

A typical structure for this SQL project is shown below. Adjust it to match your actual repository.

```text
SQL-Pizza_sales/
│
├── data/
│   └── pizza_sales.csv
│
├── sql/
│   ├── data_exploration.sql
│   ├── basic_analysis.sql
│   └── advanced_analysis.sql
│
├── results/
│   └── analysis_results/
│
├── README.md
└── LICENSE
```

*The folder and filenames above are illustrative. Retain only files that actually exist in your repository.*

## ⚙️ Installation

### Prerequisites

- A SQL database or SQL-compatible environment.
- A SQL client such as MySQL Workbench, SQL Server Management Studio, or another compatible tool.
- Access to the project's dataset.
- Basic knowledge of SQL queries and relational databases.

### Clone the Repository

```bash
git clone https://github.com/Sapna2026/SQL-Pizza_sales.git
```

Navigate to the project folder:

```bash
cd SQL-Pizza_sales
```

### Database Setup

1. Open your SQL client.
2. Create or select a database for the project.
3. Import the dataset into the database.
4. Confirm that the tables and columns match the SQL scripts.
5. Open the project's SQL files and prepare to execute the queries.

The exact import process depends on the database platform and the format of the supplied data.

## 🚀 How to Run

1. Clone or download the repository.
2. Open your SQL database environment.
3. Import the pizza sales dataset.
4. Verify the database and table names.
5. Open the SQL scripts included in the project.
6. Execute the queries in the appropriate order.
7. Review the result sets for sales KPIs, trends, and product comparisons.
8. Use the results to document verified business findings.

**Note:** The SQL dialect and file paths should match the actual implementation in the repository.

## 🔄 Analysis Pipeline

The project follows a structured SQL analytics workflow.

```text
Pizza Sales Dataset
        |
        v
Data Import
        |
        v
Data Inspection
        |
        v
Data Quality Checks
        |
        v
SQL Data Analysis
        |
        v
KPI Calculation
        |
        v
Sales Trend Analysis
        |
        v
Product Performance Analysis
        |
        v
Business Insights
        |
        v
Recommendations
```

### Pipeline Steps

1. **Data Import:** Load the pizza sales data into a SQL environment.
2. **Data Inspection:** Review the tables, columns, and available records.
3. **Data Quality Checks:** Investigate missing values, duplicates, and inconsistent data.
4. **Data Aggregation:** Calculate sales totals and order metrics.
5. **Trend Analysis:** Explore performance across available dates and periods.
6. **Product Analysis:** Compare pizza categories, sizes, and individual products.
7. **Ranking:** Identify leading products using SQL sorting and ranking.
8. **Interpretation:** Convert query results into meaningful business insights.

## 🧹 Data Cleaning and Preparation

Reliable analysis starts with consistent and accurate data.

Relevant data quality checks include:

- Inspecting missing or null values.
- Checking for duplicate records.
- Validating date and time formats.
- Reviewing numeric columns such as quantity and price.
- Checking the consistency of category and size labels.
- Verifying revenue calculations.
- Checking relationships between orders and pizza product details.
- Confirming that aggregations use the appropriate level of detail.

The actual cleaning steps should be documented according to the SQL scripts and dataset.

## 🧮 SQL Analysis

This project demonstrates how SQL can be used to answer business questions from transactional sales data.

### Basic Analysis

Potential queries include:

- Retrieving sample records.
- Counting orders and transaction rows.
- Calculating total revenue.
- Calculating total quantities sold.
- Identifying distinct pizza categories and sizes.

### Intermediate Analysis

Potential analyses include:

- Grouping revenue by pizza category.
- Comparing sales by pizza size.
- Calculating daily order volume.
- Summarizing revenue by month.
- Identifying top-selling products.
- Comparing average order values.

### Advanced Analysis

Where implemented, advanced SQL techniques may include:

- Common Table Expressions (CTEs).
- Subqueries.
- Window functions.
- Ranking and partitioning.
- Percentage contribution calculations.
- Period-over-period comparisons.
- Revenue and quantity rankings.

These techniques should be listed as completed work only when supported by the actual SQL scripts.

## 📈 Key Performance Indicators (KPIs)

The following KPIs are commonly used in pizza sales analysis.

| KPI | Description |
|---|---|
| Total Revenue | Total sales value from the analyzed transactions |
| Total Orders | Number of distinct orders |
| Total Pizzas Sold | Total quantity of pizzas sold |
| Average Order Value | Average revenue per order |
| Average Pizzas per Order | Average quantity of pizzas per order |
| Revenue by Category | Sales value grouped by pizza category |
| Revenue by Size | Sales value grouped by pizza size |
| Top-Selling Pizza | Product with the highest quantity sold |
| Top Revenue-Generating Pizza | Product generating the highest revenue |
| Sales Trends | Changes in sales over time |

### Example KPI Formulas

Total revenue:

\[
\text{Total Revenue} = \sum \text{Line Item Revenue}
\]

Average order value:

\[
\text{Average Order Value} =
\frac{\text{Total Revenue}}{\text{Distinct Orders}}
\]

Average pizzas per order:

\[
\text{Average Pizzas per Order} =
\frac{\text{Total Pizzas Sold}}{\text{Distinct Orders}}
\]

These calculations should use the correct revenue field and distinct order identifier from the actual dataset.

## 📅 Sales Analysis

Sales analysis helps evaluate business performance across different time periods.

Areas to investigate include:

- Daily order distribution.
- Monthly revenue trends.
- Changes in order volume.
- Average sales per order.
- Sales patterns by day of the week, if supported by the data.
- Periods with comparatively high or low sales activity.

These analyses can help businesses understand demand patterns and plan staffing, inventory, and promotions.

## 🍕 Product Performance Analysis

Product-level analysis helps identify which pizzas contribute most to sales and customer demand.

Potential areas of analysis include:

- Best-selling pizzas by quantity.
- Pizzas ranked by revenue.
- Sales distribution across pizza categories.
- Revenue by pizza size.
- Products with comparatively lower sales.
- Percentage contribution of each product to overall revenue.

The results can support product planning, menu optimization, and inventory decisions.

## 🤖 Models Compared

**Not applicable to this SQL-based descriptive analytics project.**

The project focuses on querying historical sales data, calculating business metrics, and identifying trends. It does not require machine-learning models.

Predictive techniques could be explored as a future extension if the objective expands to forecasting demand or predicting future sales.

## 📏 Evaluation Metrics

Since this is a descriptive SQL analysis project, model evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are not applicable unless predictive modelling is introduced.

Instead, the analysis can be assessed through:

- Correctness of SQL queries.
- Accuracy of revenue and quantity calculations.
- Correct identification of distinct orders.
- Consistency of grouped and aggregated results.
- Data quality and completeness.
- Reconciliation of reported totals with source data.
- Relevance and clarity of business insights.

## 💡 Key Findings

The purpose of this project is to uncover useful patterns in pizza sales data.

The final findings should be based on the actual SQL query results.

Recommended areas to document include:

- Overall sales and order performance.
- The strongest-performing pizza categories.
- Popular pizza sizes.
- Products with the highest sales quantities.
- Products generating the most revenue.
- Daily or monthly sales patterns.
- Opportunities to improve product and inventory planning.

**Important:** Add actual figures, product names, percentages, and rankings only after verifying the SQL output. This keeps the project credible and suitable for a professional portfolio.

## 💼 Business Recommendations

Depending on the verified results, the analysis may support recommendations such as:

1. **Inventory Optimization:** Align ingredient and stock planning with observed product demand.
2. **Menu Optimization:** Review the performance of individual pizzas and categories.
3. **Sales Strategy:** Use sales trends to guide promotions and operational planning.
4. **Demand Planning:** Consider historical ordering patterns when preparing for busier periods.
5. **Product Marketing:** Promote products based on validated sales and revenue performance.
6. **Performance Monitoring:** Track KPIs regularly to identify changes in business activity.
7. **Data-Driven Decisions:** Use SQL results to support evidence-based operational decisions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| SQL | Querying and analyzing sales data |
| Relational Database | Storing and querying structured data |
| SQL Aggregations | Calculating revenue, quantity, and order metrics |
| Joins | Combining related tables, where required |
| CTEs and Window Functions | Advanced analysis, where implemented |
| GitHub | Version control and project documentation |

Add the specific database platform, such as MySQL or SQL Server, only if it was actually used.

## 🧠 Skills Demonstrated

- SQL querying
- Data exploration
- Data aggregation
- Filtering and sorting
- Grouping and summarization
- Joins and subqueries
- KPI calculation
- Sales trend analysis
- Product performance analysis
- Business intelligence
- Analytical problem-solving
- Business insight generation

## ⚠️ Project Limitations

- Analysis is dependent on the quality and completeness of the source data.
- Historical sales patterns do not guarantee future demand.
- Descriptive analysis does not establish causation.
- Results depend on the correctness of the SQL logic and data granularity.
- Predictive forecasting is outside the scope of a descriptive analysis project.

## 🚀 Future Improvements

Potential improvements include:
- Add a data dictionary for all columns.
- Include verified KPI values and business findings.
- Build a Power BI dashboard using the analyzed data.
- Extend the project with advanced SQL queries.
- Develop sales forecasting models using historical trends.
- Automate recurring sales reports.
- Compare sales performance across additional time periods.

## 📄 License

No license has been used for this repository.

## 👩‍💻 Author

**Sapana Yadav**

Aspiring Data Analyst

**Skills:** Excel | SQL | Python | Power BI

**GitHub Profile:** [Sapna2026](https://github.com/Sapna2026)

**Repository:** [EDA_Customer_Churn_Analysis](https://github.com/Sapna2026/SQL-Pizza_sales/tree/main)

Explore my GitHub profile for additional data analytics projects and business intelligence work.

---

⭐ If you find this project useful, consider starring the repository!
