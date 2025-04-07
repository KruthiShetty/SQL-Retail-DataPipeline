# ETL-Driven Customer Segmentation & Retail Analytics : SQL Data Pipeline

## 🔍 Problem Statement  
Developed an **ETL pipeline** to extract, transform, and load **retail store data** into a structured database. Leveraged **SQL queries** to analyze **consumer behavior, sales trends, and operational performance**, providing actionable insights for **retail business decision-making**.  

## 📊 Data Points Used  
The dataset includes:  
- **Customers:** Customer ID, Name, Gender, City, State.  
- **Stores:** Store ID, City, Area, State.  
- **Products:** Product ID, Category, Price.  
- **Orders:** Order ID, Customer ID, Store ID, Order Date, Total Amount.  
- **Order Mapping:** Order ID, Product ID, Quantity.  

## ⚙️ Technology Stack  
- **ETL Pipeline:** Data extraction, transformation (via SQL), and loading.  
- **SQL:** Data transformation, querying, and analysis.  
- **Excel:** Initial data formatting before importing into SQL.  
- **Database Management:** Structured storage for retail data.  

## 🏗️ Methodology  

1. **Data Formatting:** Cleaned and structured raw data using Excel.  
2. **Data Loading:** Imported formatted data into a SQL database.  
3. **Data Transformation:** Established relationships between tables (e.g., Customers → Orders → Order Mapping → Products).  
4. **SQL Querying and Analysis:** Executed aggregations, joins, and filters to derive insights.  

## 📈 SQL Querying & Data Analysis  

### **Key SQL Operations Used:**  
- **Aggregation:** `SUM`, `COUNT`, `AVG` for sales and revenue analysis.  
- **Joins:** `INNER JOIN`, `LEFT JOIN` to connect customers, transactions, and stores.  
- **Conditions:** `CASE WHEN` for transaction classification.  
- **Filtering:** `WHERE`, `HAVING` for focused insights.  
- **Grouping:** `GROUP BY`, `ORDER BY` to rank and categorize data.  

## 🔎 Key Insights Generated  

### 🔹 **Customer Insights**  
- **Transaction by Gender:** Understands purchasing behavior.  
- **Loyalty Analysis:** Identifies customers shopping at multiple stores.  
- **State-wise Customer Distribution:** Determines demand by location.  
- **Gender-based Shopping Patterns:** Analyzes men vs. women shoppers.  

### 🔹 **Sales & Performance Analysis**  
- **Highest Order Volume City:** Aids store expansion decisions.  
- **Highest Sales Area:** Identifies high-revenue regions.  
- **Top-Selling Products and Categories:** Assists in inventory planning.  
- **Customer Segmentation:** Categorizes customers based on loyalty and frequency.  

## 📊 Business Impact & Benefits  
✅ **Optimized Inventory Management:** Aligns stock levels with demand patterns.  
✅ **Targeted Marketing:** Enables gender-based and location-based promotions.  
✅ **Operational Efficiency:** Identifies high-performing and underperforming stores.  
✅ **Revenue Growth:** Data-driven insights enhance pricing and sales strategies.  
✅ **Customer Retention:** Loyalty segmentation improves reward programs.  

## 🚀 Getting Started  
1. **Clone this repository**.  
2. **Load the dataset into a SQL database**.  
3. **Run the ETL pipeline** to clean and transform data.  
4. **Execute SQL queries** to generate insights.  

## 🤝 Contributing  
Open to feedback & collaborations! Feel free to submit improvements via pull requests.  

## 👨‍💻 Author & Contact  
**Kruthi Shetty**  
[**LinkedIn Profile**](https://www.linkedin.com/in/kruthi-s-9787512a1/)  

