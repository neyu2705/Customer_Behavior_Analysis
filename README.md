# Customer Purchase Behavior Analysis – Data Analytics Project

## Overview

This project is an **end-to-end Data Analytics project** focused on analyzing **customer shopping behavior** using Python, SQL, and Power BI.
The workflow includes data loading, exploratory data analysis (EDA), data cleaning, SQL querying, dashboard creation, and final reporting.

The goal of this project is to extract **business insights about customer purchases, revenue patterns, discounts, subscriptions, and product performance** and present them through a **Power BI dashboard and report**.

---

## Dataset

* File: `customer_shopping_behavior.csv`
* Contains customer purchase records including:

  * Customer ID
  * Gender
  * Age / Age group
  * Item purchased
  * Category
  * Purchase amount
  * Review rating
  * Discount applied
  * Subscription status
  * Shipping type
  * Previous purchases

The dataset was first analyzed in Python and then stored in SQL for advanced querying.

---

## Tools & Technologies

* **Python**

  * pandas
  * numpy
  * matplotlib / seaborn
  * Jupyter Notebook

* **SQL**

  * MySQL / PostgreSQL / SQL Server
  * Complex queries, aggregations, window functions

* **Power BI**

  * Dashboard creation
  * KPI analysis
  * Interactive visuals

* **Gamma**

  * PPT / Presentation creation

* **VS Code / Jupyter**

  * Development environment

---

## Project Steps

### 1. Data Loading in Python

* Loaded dataset using pandas
* Checked data types and structure
* Handled missing values
* Cleaned column names

Notebook used:

* `customer_purchase_behaviour.ipynb`

---

### 2. Exploratory Data Analysis (EDA)

* Summary statistics
* Purchase distribution
* Gender analysis
* Category analysis
* Rating analysis
* Discount usage analysis

Goal:

* Understand customer behavior
* Identify patterns

---

### 3. Data Cleaning

* Removed duplicates
* Fixed data types
* Handled null values
* Created new columns (age_group, segments, etc.)

Clean data used for SQL and Power BI.

---

### 4. SQL Database Analysis

SQL file used:

* `Customer_Behaviour.sql`

Key queries performed:

* Total revenue by gender
* Customers using discount but spending more than average
* Top rated products
* Average purchase by shipping type
* Subscriber vs non-subscriber revenue
* Discount usage per product
* Customer segmentation (New / Returning / Loyal)
* Top products per category
* Repeat buyers vs subscription
* Revenue by age group

Example query:

```sql
SELECT gender, SUM(purchase_amount) AS revenue
FROM customer
GROUP BY gender;
```

More queries available in the SQL file.


---

## Power BI Dashboard

File:

* `Customer Behavior Dashboard.pbix`

Dashboard includes:

* Total revenue KPI
* Purchase by category
* Purchase by gender
* Subscription analysis
* Discount analysis
* Top products
* Age group revenue
* Filters & slicers

Purpose:

* Interactive business insights
* Easy decision making

---

## Results / Insights

* Identified top selling products
* Found revenue contribution by gender
* Compared subscriber vs non-subscriber spending
* Analyzed discount impact
* Segmented customers based on purchase history
* Built interactive dashboard for visualization

This project demonstrates skills in:

* Python data analysis
* SQL querying
* Data cleaning
* Business analytics
* Power BI dashboard design
* Reporting & presentation

---

## How to Run

1. Clone the repository

2. Install Python libraries

```
pip install pandas numpy matplotlib seaborn
```

3. Run Jupyter Notebook

```
customer_purchase_behaviour.ipynb
```

4. Import dataset into SQL

5. Run SQL file

```
Customer_Behaviour.sql
```

6. Open Power BI file

```
Customer Behavior Dashboard.pbix
```

7. View dashboard

<img width="1234" height="671" alt="Png of Dashboard" src="https://github.com/user-attachments/assets/756e40c6-ab90-4e2e-88cd-1f08315e67a7" />



# Customer_Behavior_Analysis
