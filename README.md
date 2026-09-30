# Data Analytics

A personal repository for learning and practicing **Data Analytics, SQL, PostgreSQL, Power BI, and Business Intelligence** using real-world and industry-standard datasets.

The repository contains datasets, SQL queries, data-cleaning scripts, Power BI projects, and analytical exercises.

---

## Repository Structure

```text
data-analytics/
│
├── data/
│   ├── adventureworks/
│   │   └── README.md
│   │
│   ├── superstore/
│   │   └── README.md
│   │
│   ├── northwind/
│   │   └── README.md
│   │
│   └── other-datasets/
│
├── sql/
│   ├── adventureworks/
│   ├── superstore/
│   ├── northwind/
│   └── ...
│
├── powerbi/
│   ├── adventureworks/
│   ├── superstore/
│   └── ...
│
└── README.md
```

---

## Datasets

### 1. AdventureWorks

**Domain:** Manufacturing & Retail
**Database:** PostgreSQL
**Primary use:** SQL, PostgreSQL, Power BI, Business Analytics

AdventureWorks is a fictional bicycle manufacturing and retail business dataset containing information about products, customers, sales, purchasing, employees, inventory, and territories.

**Important tables:**

* Customer
* Person
* Product
* ProductCategory
* ProductSubcategory
* SalesOrderHeader
* SalesOrderDetail
* SalesTerritory
* SalesPerson
* ProductInventory
* Vendor
* PurchaseOrderHeader
* PurchaseOrderDetail

**Key analytical areas:**

* Sales analysis
* Product performance
* Customer analysis
* Revenue analysis
* Regional sales
* Inventory analysis
* Salesperson performance
* Order analysis

**Dataset:**
See [`data/adventureworks/README.md`](data/adventureworks/README.md)

---

### 2. Superstore

**Domain:** Retail
**Primary use:** Power BI, Data Visualization, Business Analytics

Useful for practicing:

* Sales analysis
* Profit analysis
* Customer segmentation
* Regional performance
* Product performance
* Time-series analysis
* Power BI dashboards

---

### 3. Northwind

**Domain:** Wholesale / Trading
**Primary use:** SQL and Relational Database Practice

Useful for practicing:

* SQL JOINs
* Aggregations
* Subqueries
* CTEs
* Window functions
* Customer analysis
* Order analysis
* Product analysis

---

## SQL Practice

The `sql/` directory contains queries and analytical problems organized by dataset.

Topics include:

```text
Basic SQL
├── SELECT
├── WHERE
├── ORDER BY
├── GROUP BY
└── HAVING

Intermediate SQL
├── JOINs
├── CASE
├── Subqueries
├── CTEs
└── Date & String Functions

Advanced SQL
├── Window Functions
├── Ranking
├── Running Totals
├── Moving Averages
├── Recursive CTEs
└── Complex Analytical Queries
```

---

## PostgreSQL

The primary database used in this repository is **PostgreSQL**.

The goal is to practice PostgreSQL features including:

* CTEs
* Window functions
* Date/time functions
* String functions
* Aggregate functions
* `CASE` expressions
* Subqueries
* Views
* Indexes
* Constraints
* Query optimization
* `EXPLAIN` / `EXPLAIN ANALYZE`

---

## Power BI

The `powerbi/` directory contains Power BI projects and dashboards created using the datasets.

Typical workflow:

```text
Dataset
   ↓
PostgreSQL
   ↓
SQL / Data Cleaning
   ↓
Power BI
   ↓
Data Modeling
   ↓
DAX
   ↓
Visualization
   ↓
Dashboard
```

Power BI projects may include:

* Sales dashboards
* Customer analysis
* Product analysis
* Regional analysis
* KPI dashboards
* Time-series analysis
* Business performance reports

---

## Learning Goals

This repository is intended to build practical skills in:

* SQL
* PostgreSQL
* Data Cleaning
* Exploratory Data Analysis
* Data Modeling
* Power BI
* DAX
* Data Visualization
* Business Intelligence
* Analytical Thinking

---

## Tools & Technologies

| Tool       | Purpose                         |
| ---------- | ------------------------------- |
| PostgreSQL | Database                        |
| pgAdmin    | Database management             |
| SQL        | Data querying & analysis        |
| Power BI   | Visualization & BI              |
| DAX        | Power BI calculations           |
| Git        | Version control                 |
| GitHub     | Repository & project management |
| Python     | Data analysis & automation      |

---

## Project Workflow

For each dataset, the preferred workflow is:

```text
1. Understand the dataset
        ↓
2. Identify tables & relationships
        ↓
3. Load data into PostgreSQL
        ↓
4. Explore the data using SQL
        ↓
5. Clean / transform data
        ↓
6. Perform analytical queries
        ↓
7. Connect PostgreSQL to Power BI
        ↓
8. Build data model
        ↓
9. Create DAX measures
        ↓
10. Build dashboard
        ↓
11. Document insights
```

---

## Dataset Documentation

Each dataset should have its own `README.md` containing:

* Dataset description
* Source
* Download link
* Table list
* Column names
* Data types
* Primary keys
* Foreign keys
* Table relationships
* Important business questions
* PostgreSQL import instructions

Example:

```text
data/
└── adventureworks/
    └── README.md
```

---

## Goal

The long-term goal of this repository is to build a collection of practical **SQL and Business Intelligence projects** that demonstrate the complete data analytics workflow — from raw data to actionable insights.

---

## License & Data Sources

Datasets are obtained from their respective public sources and remain subject to their original licenses and terms of use.

This repository is intended for **learning, practice, and educational purposes**.
