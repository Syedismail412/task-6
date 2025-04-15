# 📈 Sales Trend Analysis Using Aggregations

*Role*: Data Analyst Intern  
*Task*: Task 6 - Sales Trend Analysis  
*Tools Used*: PostgreSQL / MySQL / SQLite  
*Dataset*: online_sales  
(Columns: order_date, amount, product_id)

---

## 🎯 Objective

To analyze monthly sales performance by calculating:
- 📊 Monthly Revenue
- 📦 Monthly Order Volume

Using SQL aggregations and date-based grouping.

---

## 📁 Deliverables

- ✅ SQL Script containing all queries
- ✅ Results table (output or screenshot)
- ✅ README file (this document)

---

## 🧠 Key Concepts & Hints

- Use EXTRACT(MONTH FROM order_date) to get the month  
- Use EXTRACT(YEAR FROM order_date) to get the year  
- Group data using GROUP BY year, month  
- Calculate revenue using SUM(amount)  
- Calculate order volume using COUNT(DISTINCT order_id)  
- Sort results using ORDER BY  
- Limit data with LIMIT to focus on top results  
