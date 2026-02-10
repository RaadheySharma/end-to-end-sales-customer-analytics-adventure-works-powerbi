# 📊 End-to-End Sales & Customer Analytics Dashboard (Power BI)

## Project Overview
This project showcases a comprehensive end-to-end business dashboard developed using Power BI. The dashboard aims to provide a way to track KPIs (Sales,Orders,Profit,Returns), compare regional performance across 6 nations(USA,Canada,Australia, France, UK and Germany), analyze product level trends and identify high value customers. 

---

## 🎯 Business Objective
- Monitor revenue, profit, orders, and return rates and present them through KPI Cards 
- Identify top-performing products and categories 
- Analyze customer segments and identify the top customers according to their income level and occupation 
- Track global sales performance
- Compare performance against targets
- Simulate price adjustments using parameters based on “Numeric Range Parameters” 
- Adjusted the graphs according to the user’s needs by using parameters based on “Field Parameters” 

---

## 🛠 Tools & Technologies
- Power BI
- DAX (Data Analysis Expressions)
- Data Cleaning & Transformation
- CSV Data Processing
- Data Modeling
- Data Visualization

---

## 📂 Dataset Information
Dataset Used: AdventureWorks Dataset (Maven Analytics) 
Data Source: CSV files  

Data Includes:
- Sales data
- Customer data
- Product information
- Orders and returns
- Territory Data 

---

## ⚙️ Data Preparation & Modeling
- Imported multiple CSV datasets
- Cleaned and transformed raw data
- Handled missing and inconsistent values
- Created relationships between tables
- Created Calendar Table to create relationship of the calendar table with all the other tables that contains date 
- Created Calculated Columns 
- Created DAX Measure for
  -> Total Orders/Profit/Revenue/Cost/Returns/Customers
  -> Previous Month Revenue/Orders/Profit/Returns (Using "CALCULATE"  with "DATEADD" nested with it)
  -> Year To Date Revenue 
- Created New Paramters of "Numeric Range" named as "Price Adjustment(%)" to show the impact of adjustments of Price on Total Profit of the Company through a Line Chart 
- Created New Parameters of "Fields" named as "Customer Metric Selection" to show different charts according to the user's needs (Fields are Total Customers and Revenue per Customer)
- Created New Parameters of "Fields" named as "Product Metric Selection" to show different charts according to the user's needs (Fields are orders, revenue, return and return rate)
- Designed KPI metrics to show business performance 
- Presented the Total Customers by Country on Map (6 countries are USA,Canada,Australia, France, UK and Germany)

---

## 📊 Dashboard Features

### 🔹 Executive Dashboard
- Revenue, Profit, Orders, Return Rate KPIs
- Revenue trend analysis
- Monthly performance tracking through 3 parameters (Revenue,Orders and Returns)
- Orders by category
- Top Performing Products on the basis of Total Orders
- Most ordered & most returned product types
- Interactive filters and slicer pane

### 🔹 Geographic Analysis
- Global sales performance of the comapny on the basis of total orders presented through bubbles on the map across 6 Nations (USA,Canada,Australia, France, UK and Germany)
- Region-wise filtering (Europe, North America, Pacific)

### 🔹 Product Detail 
- Price adjustment parameter and its impact on total profit 
- Monthly Product performance vs Target Gauges
- Interactive filters and slicers
- Field Parameters to show graphs according to user needs 
- Interactive filters and slicer pane

### 🔹 Customer Analytics
- Revenue per customer 
- Total Customers 
- Field Parameters to show graphs according to user needs of Revenue per Customers and Total Customers 
- Top customers analysis
- Income-level segmentation through donut chart
- Occupation-based purchasing trends through donut charts
- Interactive filters and slicers

---

## 📈 Key Insights
- Total Revenue generated of $24.9 Million
- Total Profit of $ 10.5 Million 
- Total Orders of 25,200
- Return Rate of 2.1% 
- Accessories generated the highest order volume of 17000 out of 25200 
- Tires & Tubes were the most ordered product type
- Shorts had the highest return rate
- Revenue showed strong upward growth after 2021
- United States is the country from where most of the order were placed 
- Total Customers are 17400, with revenue per customer of $1,431 
- Professional customer segment generated major revenue
- Top customer of the company is Mr Maurice Shan that has placed a total of 6 orders and spent an amount of $12,400 on the comapny product

---

## 🖼 Dashboard Screenshots
![Dashboard Preview](https://github.com/RaadheySharma/end-to-end-sales-customer-analytics-adventure-works-powerbi/blob/main/Executive_Dashboard.png)
![Map](https://github.com/RaadheySharma/end-to-end-sales-customer-analytics-adventure-works-powerbi/blob/main/Total%20Customer%20by%20Country.png)
![Product Detail](https://github.com/RaadheySharma/end-to-end-sales-customer-analytics-adventure-works-powerbi/blob/main/Product%20Detail%20Summary.png)
![Customer Analytics](https://github.com/RaadheySharma/end-to-end-sales-customer-analytics-adventure-works-powerbi/blob/main/Customer%20Analysis.png)

---

