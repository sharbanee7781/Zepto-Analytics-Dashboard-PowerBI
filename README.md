# Zepto-Analytics-Dashboard-PowerBI
An interactive Power BI dashboard providing actionable insights into Zepto’s Sales, Customer, and Transaction performance — enabling data-driven decision-making through dynamic KPIs, DAX measures, and visual storytelling.

# 🚀 Zepto Analytics Dashboard – Power BI Project  

## 📘 Overview  
The **Zepto Analytics Dashboard** is an end-to-end **Power BI project** designed to provide actionable insights into business performance across **Sales**, **Customer**, and **Transaction** domains.  

This project focuses on transforming raw data into meaningful business intelligence through interactive visualizations, DAX-driven KPIs, and data storytelling techniques.  

---

## 🧩 Project Objectives  
- Develop a unified reporting dashboard to monitor key metrics across multiple business areas.  
- Identify high-performing regions, customer segments, and payment modes.  
- Enhance decision-making using real-time, filter-driven insights.  
- Demonstrate proficiency in Power BI, data modeling, and analytics storytelling.  

---

## 🧠 Data Source  
The dataset simulates **Zepto’s business operations**, including:  
- **Sales Data** – Orders, revenue, discount, delivery partners, etc.  
- **Customer Data** – Age, gender, city, engagement, and purchasing behavior.  
- **Transaction Data** – Payment mode, transaction success/failure, and revenue contribution.
- 

## 📊 Dashboard Components  

### **1️⃣ Sales Dashboard**
**Purpose:** Track business growth, sales trends, and product performance.  

**Key Insights:**  
- Total Sales Revenue: ₹36.78M  
- Total Orders: 15K  
- Average Order Value: ₹2.45K  
- Discount Given: ₹168K  
- Orders by State (Geographic heat map)  
- Sales by Delivery Partner (Xpressbees, Shadowfax, etc.)  
- Monthly Sales Trend Visualization  
- Top 10 Products Sold  
- Coupon Impact on Orders  

---

### **2️⃣ Customer Dashboard**
**Purpose:** Analyze customer behavior, demographics, and engagement.  

**Key Insights:**  
- Total Customers: 15K | Active Customers: 6.34K  
- Average Customer Age: 43.84 years  
- Average Spend per Customer: ₹2.45K  
- Engagement Level: 2.37  
- City-wise Customer Distribution  
- State-wise Customer Map  
- Gender Distribution (Male 50.2%, Female 49.8%)  
- Age Group Analysis (Young Adult, Adult, Mature, Senior)  
- Purchase Time Preferences (Morning, Afternoon, Evening, Night)  
- Orders by Gender & Age Group  

---

### **3️⃣ Transaction Dashboard**
**Purpose:** Evaluate transaction performance and payment success.  

**Key Insights:**  
- Total Transactions: 15K  
- Successful: 7,480 | Failed: 7,520  
- Transaction Success Rate: 49.87%  
- Revenue from Successful Transactions: ₹36.78M  
- Mode-wise Analysis (UPI, COD, Wallet, Debit & Credit Card)  
- Success vs. Failure Percentage per Mode  
- Monthly Transaction Trends  
- Average Revenue per Successful Transaction  

---

## ⚙️ Tools & Techniques Used  
| Tool | Purpose |
|------|----------|
| **Power BI** | Dashboard creation and visualization |
| **Power Query** | Data extraction, transformation, and cleaning |
| **DAX (Data Analysis Expressions)** | Calculated columns, KPIs, and measures |
| **Excel / CSV** | Data source |
| **Maps, Donut, Line, and Bar Charts** | Visualization techniques for insights |

---

## 🧮 DAX Measures Used (Examples)
- **Total Revenue:** `SUM(Sales[Revenue])`  
- **Average Order Value:** `DIVIDE([Total Revenue], [Total Orders])`  
- **Transaction Success Rate:** `DIVIDE([Successful Transactions], [Total Transactions])`  
- **Engagement Level:** Custom metric combining frequency and spend metrics  

---

## 📈 Business Impact  
✅ Unified view of company performance across sales, customers, and transactions  
✅ Data-driven insights to identify growth opportunities and bottlenecks  
✅ Improved understanding of customer demographics and preferences  
✅ Simplified monitoring of transaction reliability and payment performance  

---

## 🧩 Future Enhancements  
🔹 Integration with live SQL or API-based data sources  
🔹 Automated refresh scheduling via Power BI Service  
🔹 Predictive analytics for sales and churn forecasting  
🔹 Drill-through pages for detailed city and product-level insights  

---

## 📊 Sales Dashboard
![Sales Dashboard](https://github.com/sharbanee7781/Zepto-Analytics-Dashboard-PowerBI/blob/main/Sales.png?raw=true)
