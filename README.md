# 📊 AdventureWorks Sales Analytics Dashboard
A comprehensive Power BI dashboard analyzing sales performance, customer behavior, and product trends for AdventureWorks, a global cycling equipment manufacturer.

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/5472f96e-5218-460b-9cda-9d46e71516e9" />


## 🎯 Project Objective:
Management required a business intelligence solution to:

Track key performance indicators (KPIs) in real-time
Monitor sales performance across different territories
Analyze product-level trends and profitability
Identify high-value customers and purchasing patterns


## 📈 Key Metrics:  
Total Revenue: $24.9M  
Total Profit: $10.5M  
Total Orders: 25.2K  
Return Rate: 2.2%  
Unique Customers: 17.4K  
Revenue per Customer: $1.4K  


## 🗂️ Dashboard Pages:  
1.Executive Overview  
   Revenue trending analysis (Jan 2020 - Jan 2022)
   Monthly revenue, orders, and returns comparison
   Category-wise performance breakdown
   Top 10 products by orders and revenue
   Product type analysis (most ordered vs. most returned)

2.Geographic Analysis  
  Interactive map visualization showing global sales distribution
  Territory-based filtering (Europe, North America, Pacific)
  Bubble size represents sales volume by country
  Key markets: United States, Australia, UK, France, Germany

3.Product Deep Dive  
  Individual product performance tracking
  What-if analysis with price adjustment slider
  Performance vs. target gauges (Orders, Revenue, Profit)
  Total vs. Adjusted profit comparison over time
  Dynamic metric selection for flexible analysis

4.Customer Intelligence  
  Customer growth trend analysis
  Revenue per customer metric
  Customer segmentation by occupation and income level
  Top 100 customers ranked by revenue contribution
  Individual customer profile with order history

**Key Insights:**  
* Professional segment accounts for 41.41% of orders
* High-income customers drive significant revenue
* Top customer (Mr. Maurice Shan) generated $12.4K in revenue
* 33% month-over-month revenue growth
* Accessories category leads with 17.0K orders
* Tires and Tubes are the most ordered product type
* Shorts have the highest return rate


**🛠️ Technical Implementation**  
Power BI Desktop - Dashboard development  
Power Query - Data transformation and cleaning  
DAX (Data Analysis Expressions) - Calculated measures and KPIs  

**Key Features:**  
Data Modeling: Star schema with fact and dimension tables  
DAX Measures: Revenue, Profit, Returns, Growth %, Running totals  
Time Intelligence: MoM growth, YoY comparisons, trend analysis  
Interactive Filters: Slicers for date, territory, product category  
What-if Parameters: Price adjustment simulation  
Custom Visuals: Map visualization, gauge charts, KPI cards  
Drill-through: Navigation between summary and detailed views  

