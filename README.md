## E-Commerce-Customer-Churn-Analysis Using MySQL
##📌 Project Overview
Customer churn is a major challenge in the e-commerce industry. This project focuses on analyzing customer behavior and identifying churn patterns using MySQL. The dataset contains customer demographics, transaction details, satisfaction scores, device usage, payment preferences, complaints, and cashback information.

The project covers the complete data analysis workflow, including data cleaning, transformation, exploration, and business-driven insights generation using SQL.

##🎯 Objectives
• Analyze factors influencing customer churn.
• Clean and preprocess raw customer data.
• Handle missing values and outliers.
• Standardize inconsistent records.
• Transform data for easier analysis.
• Generate actionable business insights using SQL.
• Support customer retention strategies through churn analysis.
##🗂 Database Schema
Table: customer_churn
Column Name	Description
CustomerID	Unique customer identifier
Tenure	Customer relationship duration
PreferredLoginDevice	Login device used by customer
CityTier	Customer city category
WarehouseToHome	Distance from warehouse to home
PreferredPaymentMode	Customer payment preference
Gender	Customer gender
HoursSpentOnApp	App usage duration
NumberOfDeviceRegistered	Registered devices
PreferredOrderCat	Preferred product category
SatisfactionScore	Customer satisfaction rating
MaritalStatus	Marital status
NumberOfAddress	Number of addresses
OrderAmountHikeFromLastYear	Increase in order amount
CouponUsed	Coupons utilized
OrderCount	Total orders
DaySinceLastOrder	Days since last purchase
CashbackAmount	Cashback received
ComplaintReceived	Complaint indicator
ChurnStatus	Customer churn status
🧹 Data Cleaning
Missing Value Treatment
Applied Mean Imputation for:

WarehouseToHome
HoursSpentOnApp
OrderAmountHikeFromLastYear
DaySinceLastOrder
Applied Mode Imputation for:

Tenure
CouponUsed
OrderCount
Outlier Handling
Removed records where:

WarehouseToHome > 100
🔄 Data Transformation
Standardization
Phone → Mobile Phone
Mobile → Mobile Phone

COD → Cash on Delivery
CC → Credit Card
Renamed Columns
PreferedOrderCat → PreferredOrderCat
HourSpendOnApp → HoursSpentOnApp
Created New Columns
ComplaintReceived
Yes
No
ChurnStatus
Churned
Active
Dropped Columns
Churn
Complain
📊 Business Analysis Performed
Customer Churn Analysis
Count of active customers vs churned customers
Percentage of churned customers who raised complaints
Average tenure of churned customers
Total cashback received by churned customers
Customer Behavior Analysis
Most preferred payment method among active customers
Average registered devices for UPI users
Coupon utilization analysis
Order frequency analysis
Satisfaction score analysis
Product & Category Analysis
Preferred product categories
Top categories by average cashback
Customer count per category
Maximum app usage by category
Geographic Analysis
Customer distribution across city tiers
Churn analysis by city tier
Distance-based customer segmentation
Customer Returns Analysis
Created customer_returns table
Joined churn and returns data using INNER JOIN
Analyzed returned orders from churned customers with complaints
🛠 SQL Concepts Used
Database Operations
CREATE DATABASE
CREATE TABLE
ALTER TABLE
INSERT
UPDATE
DELETE
Querying Techniques
SELECT
WHERE
GROUP BY
ORDER BY
LIMIT
DISTINCT
Advanced SQL
Aggregate Functions

AVG()
SUM()
COUNT()
MAX()
CASE Statements

Subqueries

Joins

Data Cleaning Techniques

Data Transformation

Customer Segmentation

📈 Key Insights Generated
✅ Identified churned and active customer distribution

✅ Measured complaint behavior among churned customers

✅ Determined preferred payment methods and order categories

✅ Segmented customers based on warehouse distance

✅ Analyzed customer cashback and coupon behavior

✅ Explored customer return patterns through relational analysis

💻 Technologies Used
MySQL
SQL
Relational Database Management System (RDBMS)
🚀 Learning Outcomes
Database Design and Management
Data Cleaning using SQL
Missing Value Treatment
Outlier Handling
Data Transformation
Data Exploration
Business Intelligence Reporting
Customer Churn Analytics
Advanced SQL Query Writing
Join & Subquery Operations
👩‍💻 Author
Aleena Mathew



✅ Explored customer return patterns through relational analysis
