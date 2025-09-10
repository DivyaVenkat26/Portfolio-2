# eCommerce Data Analysis

This project analyzes **customer behavior and sales patterns** in an eCommerce platform using a combination of **SQL and Python**. The goal is to derive business insights that help improve customer experience, optimize operations, and guide strategic decisions.  
The data was extracted from a **MySQL database** and analyzed using **Python libraries**.

---

## Objectives
- Connect to a **MySQL database** and extract relevant eCommerce data  
- Clean and preprocess the data using **Python (Pandas, NumPy)**  
- Perform **SQL-based analysis** for trends, customer geography, and product performance  
- Visualize key insights using **Matplotlib** and **Seaborn**  

---

## Methodology

### Data Collection
- Extracted data from a **MySQL eCommerce database** using `mysql.connector`  
- Queried key tables: `customers`, `orders`, `order_items`, `products`, and `payments`  

### Data Integration
- Joined multiple SQL tables in Python using `pd.read_sql()`  
- Built a comprehensive dataset combining **customer details, product purchases, and payment history**  

### Data Cleaning
- **Null Handling**:  
  - Text fields → `"Not Available"`  
  - Numeric fields → `0` or `-1`  
  - Used Pandas `fillna()`  
- **Duplicates**: Checked with `duplicated()` and removed with `drop_duplicates()`  

### Data Transformation
- Converted timestamp fields to datetime using `pd.to_datetime()`  
- Derived new columns: **year, month, weekday** for trend analysis  

### Data Analysis in SQL
- Executed SQL queries from Python using `cur.execute()`  
- Example queries included:  
  - Total orders per year  
  - Top customer states  
  - Revenue per product  

### Exploratory Data Analysis (EDA)
- **Order Trends**: Tracked number of orders and revenue by year and month  
- **Geographic Trends**: Identified top customer **cities and states**  
- **Product Performance**: Most frequently bought & highest-revenue products  

---

## Key Results & Insights
- Successfully integrated multiple SQL tables into a clean dataset  
- Cleaned dataset contained accurate **timestamps, customer locations, and sales metrics**  
- **Top states/cities**: São Paulo and Rio de Janeiro contributed the highest sales  
- **Peak purchase months**: November–December showed the highest activity  
- **Top-performing product categories** were identified by quantity & revenue  

---

## Tools & Libraries
- **SQL (MySQL)** – Data connection & queries  
- **Python** – Pandas, NumPy, Matplotlib, Seaborn  



