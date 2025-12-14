🛒 E-commerce Inventory Data Analysis (Zepto Product Listings)
📌 Project Overview

This project analyzes e-commerce inventory data from a simulated Zepto product listings dataset.

The goal is to practice real-world Data Analyst work by:

Cleaning raw product data using Python

Storing data in MySQL

Writing SQL queries to generate business insights related to pricing, inventory, and revenue

---

💾 Dataset

Dataset: Zepto Product Listings

https://github.com/VishalJaiswal-analyst/zepto_analysis/blob/main/zepto_v2.csv

---

🛠 Tools Used

Python (Pandas, NumPy) – Data loading, cleaning, and EDA

MySQL – Storing data and running SQL queries

MySQL Connector – Python to MySQL connection

Git & GitHub – Version control

---

⚙️ Steps Performed

1️⃣ Data Loading & EDA (Python)

    Loaded CSV data using Pandas
    
    Checked data types, missing values, and distributions
    
    Found that price values were stored in paise

2️⃣ Data Cleaning & Transformation

    Removed invalid rows (MRP = 0)
    
    Converted all prices from paise to rupees
    
    Prepared clean data for database storage

https://github.com/VishalJaiswal-analyst/zepto_analysis/blob/main/zepto_sql_analysis.ipynb

3️⃣ SQL Analysis (MySQL)

    Loaded cleaned data into MySQL table (zepto)
    
    Wrote SQL queries to analyze:
    
    Revenue potential
    
    Discount patterns
    
    Inventory gaps
    
    Product segmentation

https://github.com/VishalJaiswal-analyst/zepto_analysis/blob/main/Zepto_Analysis.sql

---

📊 Key Business Insights

    Fruits & Vegetables had the highest average discounts
    
    Found high-value products with very low discounts
    
    Identified out-of-stock high-revenue items
    
    Segmented products by weight category for logistics planning

---    

🧠 SQL Concepts Used

    WHERE
    
    GROUP BY
    
    ORDER BY
    
    LIMIT
    
    CASE

---

Aggregate functions (SUM, AVG)

🚀 How to Run the Project

# Install required libraries

pip install pandas numpy mysql-connector-python

# Run data cleaning & upload script

python data_prep.py

# Run SQL queries

Open analysis.sql in MySQL Workbench and execute

---

📈 Conclusion

This project shows how Python + SQL can be used together to solve real e-commerce business problems.
It highlights skills in data cleaning, database handling, and SQL analytics, which are essential for a Data Analyst fresher.

---

🔮 Future Improvements

    Add Power BI dashboard
    
    Automate daily inventory updates
    
    Perform demand forecasting
    
---

👤 Author

Vishal Jaiswal

LinkedIn: www.linkedin.com/in/vishal-jaiswal-analyst

Email: vishal.jaiswal.data@gmail.com
