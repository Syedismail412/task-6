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
- RESULTS:
![Screenshot (54)](https://github.com/user-attachments/assets/19ec94b4-8ad0-4b29-9d6e-dd678f262ba5)
![Screenshot (55)](https://github.com/user-attachments/assets/30fcb92e-fd62-4a4f-be64-96b529342d7d)
![Screenshot (56)](https://github.com/user-attachments/assets/7299ccbe-ba50-4643-85a8-3ddba7a422a0)


