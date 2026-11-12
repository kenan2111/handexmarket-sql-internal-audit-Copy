Project Overview

An Oracle SQL-based internal audit project focused on identifying inventory discrepancies, suspicious stock adjustments, and potential refund fraud through transactional data analysis.

Tools & Techniques

Database: Oracle SQL

SQL Skills: CTEs, JOINs, Subqueries, Window Functions, Aggregations, CASE WHEN, NOT EXISTS

Focus: Data Analysis, Internal Audit, Fraud Detection

Key Findings

Inventory Loss: Identified a 13,505-value inventory discrepancy at Warehouse 2.

Suspicious Adjustments: Flagged Employee 204 with 20 stock adjustments totaling −20,385 in value.

Refund Anomalies: Identified an unusually high proportion of NOT_RECEIVED claims (45.88%).

Delivery Risks: Flagged Courier 206 for further investigation based on delivery and refund inconsistencies.

Project Structure

The analysis uses 11 relational tables covering orders, products, employees, warehouses, deliveries, returns, and inventory movements.

Conclusion

Demonstrates the application of advanced SQL techniques to investigate operational anomalies, identify potential financial risks, and support data-driven audit decisions.
