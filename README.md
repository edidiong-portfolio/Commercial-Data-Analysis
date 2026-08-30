# Commercial-Data-Analysis
An end-to-end analysis of **14,705 commercial transactions** using PostgreSQL, SQL, and Power BI to analyze revenue, products, customers, and returns.

---

## Table of Contents

* [Project Overview](#project-overview)
* [Tools Used](#tools-used)
* [Skills Demonstrated](#skills-demonstrated)
* [Dashboard Preview](#dashboard-preview)
* [Table Used](#table-used)
* [Main Columns](#main-columns)
* [Key Performance Indicators](#key-performance-indicators)
* [Key Insights](#key-insights)
* [Recommendations](#recommendations)
* [Business Outcome](#business-outcome)
* [Conclusion](#conclusion)

---

## Project Overview

The data was **cleaned and validated in PostgreSQL**, analyzed using SQL, and presented in an interactive Power BI dashboard.

The analysis focuses on **sales trends, top products, customer spending, revenue, and return patterns**.

---

## Tools Used

* **PostgreSQL / pgAdmin** – Data cleaning, validation, and querying
* **SQL** – Data analysis, aggregation, joins, and validation
* **Power BI** – Dashboard creation and visualization
* **Data Cleaning** – Handling null values and checking data quality

---

## Skills Demonstrated

* Data cleaning and validation
* Null value handling
* SQL aggregation and joins
* Business analysis
* KPI development
* Dashboard design
* Data visualization

---

## Dashboard Preview

<img width="1599" height="835" alt="Capture Commercial Data SQL" src="https://github.com/user-attachments/assets/4e506a3f-c047-42ad-b653-46d997d6ea13" />


<img width="1597" height="860" alt="Capture Commercial_data_ sql 2" src="https://github.com/user-attachments/assets/1018ef71-e7fd-47d2-b80c-45220ead5d53" />


<img width="1600" height="860" alt="Capture Commercial_data_ sql 3" src="https://github.com/user-attachments/assets/1e89b854-c4f4-4bf3-b489-e45846cb0fec" />


<img width="989" height="640" alt="Capture COMMERCIAL_DATA _SQL-POWER BI" src="https://github.com/user-attachments/assets/4c4c9f6b-0b39-4f33-bb78-ba17e806fe5c" />





---

## Table Used

| Table | Description |
|---|---|
| **commercial_data** | 14,705 rows and 15 columns containing commercial transaction data |

---

## Main Columns

### commercial_data

* transaction_id
* customer_name
* email
* phone
* product
* category
* quantity
* unit_price
* total_amount
* purchase_date
* payment_method
* country
* return_status
* return_reason
* sales_rep

---

## Key Performance Indicators

## Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Revenue** | **74.90M** |
| **Total Transactions** | **14,705** |
| **Highest Monthly Revenue** | **6.48M (July)** |
| **Top Product by Revenue** | **Smartwatch (11.1M)** |
| **Top Spending Customer** | **Michael Jones (60,401.99)** |
| **Highest Returns by Country** | **Unknown Country (742)** |
| **Highest Return Reason** | **Unknown (59K)** |
| **Highest Transaction Year** | **2022 / 2024 (2,458)** |

---

## Key Insights

* **July** had the highest revenue at **6.48M**.
* **Smartwatches** generated the most revenue.
* **James Lopez** was the top customer with spending of **44,416**.
* The **UK and Canada** had high return counts.
* Many returns had **no recorded reason**.

---

## Recommendations

1. Investigate lower sales in February and May.
2. Promote top-performing products.
3. Improve return-reason data collection.
4. Review returns from the UK and Canada.

---

## Business Outcome

The project provides clear visibility into:

* Revenue performance
* Product performance
* Customer spending
* Return patterns
* Country-level sales activity

This supports faster and better business decisions.

---

## Conclusion

> **Clean the Data → Analyze the Trends → Visualize the Insights → Support Better Decisions**

PostgreSQL, SQL, and Power BI transform commercial transaction data into clear and actionable business insights.
```
