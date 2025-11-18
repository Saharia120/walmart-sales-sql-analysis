# walmart-sales-sql-analysis
SQL project analyzing Walmart sales data with feature engineering, revenue insights, customer segmentation, and performance metrics.


# 📊 Walmart Sales Data Analysis (SQL Project)

## 📝 Overview
This project is an end-to-end SQL analysis of Walmart sales data.  
It includes database creation, feature engineering, exploratory analysis, and business insights using SQL queries.  
The goal is to understand revenue trends, customer behavior, product performance, and operational patterns.

---

## 🗂️ Project Structure
1. **Database Creation**
2. **Feature Engineering**
   - Time of day (Morning/Afternoon/Evening)
   - Day name (Monday–Sunday)
   - Month name (January–December)
3. **Exploratory & Business Analysis**
   - Revenue trends  
   - COGS performance  
   - Product-line insights  
   - Payment method analysis  
   - Customer behavior  
   - Rating insights  

---

## 🛠️ Skills & Techniques Used
- SQL (MySQL)  
- Data cleaning  
- Feature engineering  
- Aggregation functions  
- `GROUP BY`, `ORDER BY`  
- Subqueries & `HAVING`  
- Date and time functions  
- Business analytics  

---

## 🧱 Database & Table Creation
Created a database named **salesdatawalmart** with structured fields including:
- Customer info (gender, type)  
- Product details  
- Unit price, COGS, total, VAT  
- Date & time fields  
- Feature-engineered fields  

---

## ⚙️ Feature Engineering Performed
### ✔ Time of Day  
Morning / Afternoon / Evening

### ✔ Day Name  
Using `DAYNAME()`

### ✔ Month Name  
Using `MONTHNAME()`

These help analyze customer behavior patterns.

---

## 📈 Key Business Questions Answered
- Unique cities and branches  
- Most common payment methods  
- Top-selling product lines  
- Monthly revenue trends  
- Highest COGS month  
- Revenue by city  
- Highest VAT product line  
- Customer type insights  
- Gender-based insights  
- Rating trends  

---

## 🧠 Insights Summary (example)
- Food & Beverages or Electronics generate the highest revenue.  
- E-wallet or Credit Card might be most popular.  
- Branch A or C may generate the most revenue.  
- Evenings have the highest traffic.  
- Weekends show strong average ratings.  

