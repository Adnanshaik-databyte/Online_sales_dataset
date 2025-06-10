# 📊 TASK 6: Sales Trend Analysis Using Aggregations

## 🎯 Objective
To analyze **monthly revenue** and **order volume** using SQL aggregations to identify trends in the `online_sales` dataset.

---

## 🛠️ Tools Used
- PostgreSQL / MySQL / SQLite  
(*This task is compatible with any of the above relational database systems.*)

---

## 📂 Dataset Overview
- **Table Name:** `online_sales`()https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset
- **Important Columns:**
  - `order_date` – Date of order
  - `amount` – Revenue from a single order
  - `order_id` – Unique order identifier
  - `product_id` – Product involved in the order

---

## ✅ Task Instructions

### a. Extract Time Components
- Use SQL date functions (e.g., `EXTRACT(MONTH FROM order_date)` or `strftime('%m', order_date)`) to extract **month** and **year** from the `order_date`.

### b. Group Data
- Group records **by year and month** to prepare the data for time-based analysis.

### c. Calculate Revenue
- Use `SUM()` on the `amount` field to get **total revenue per month**.

### d. Calculate Order Volume
- Use `COUNT(DISTINCT order_id)` to determine the **number of unique orders per month**.

### e. Sort Results
- Use `ORDER BY` to **chronologically sort** the results (first by year, then by month).

### f. Limit Results
- Apply filters or limits to analyze data for **specific time periods**, such as the last 12 months or a selected year.

---

## 📤 Deliverables
- **SQL Script** implementing the above aggregations and filters.
- **Results Table** showing:
  - Year  
  - Month  
  - Total Revenue  
  - Order Volume

---

## 📘 Learning Outcome
By completing this task, you'll gain hands-on experience in:
- Using SQL aggregation functions (`SUM`, `COUNT`)
- Extracting and formatting date components
- Grouping and analyzing time-series data
- Producing clean and structured analytical reports from raw sales data

---

# Online_sales_dataset
1.Query to analyze monthly revenue and order volume
  ![image](https://github.com/user-attachments/assets/d523bf25-6fc5-48a8-880f-4712baeaa1e3)
2. GROUP BY year/month
  ![image](https://github.com/user-attachments/assets/11a2326d-eca3-41d0-8d81-4b9ee6aaabaf)
3.SUM() for revenue
  ![image](https://github.com/user-attachments/assets/3af8c0e8-6813-4f64-8709-8048073e327e)
4.COUNT(DISTINCT order_id) for volume
  ![image](https://github.com/user-attachments/assets/28607359-0595-41da-8926-86db76e0390d)
5.Use ORDER BY for sorting
  ![image](https://github.com/user-attachments/assets/28c4d2dd-53df-41bd-a5f6-1dab6ae4907d)
6.Limit results for specific time periods
  ![image](https://github.com/user-attachments/assets/6a261441-24c7-4e4f-b504-96b342cf8c59)
7. Filter last 1 year using WHERE
  ![image](https://github.com/user-attachments/assets/a116f269-9911-412d-8c82-b55e652c403c)
-----------------------------------------------------
Contact(LinkedIn):(Adnan Shaik) http://www.linkedin.com/in/mohammed-adnan-shaik-310092366





