# global-sales-performance-dashboard-tableau
Interactive Tableau dashboard for global sales and profitability analysis with KPI tracking and business insights.
# 🌍 Global Sales Performance & Profitability Dashboard

An industry-oriented Tableau Business Intelligence project designed to analyze global sales performance, profitability trends, customer segmentation, and regional business growth using interactive dashboards and KPI-driven analytics.

---

# 📌 Project Overview

The **Global Sales Performance & Profitability Dashboard** is a professional Tableau analytics project that helps businesses monitor worldwide sales operations, profitability metrics, customer insights, and regional performance.

This dashboard simulates how multinational companies use Business Intelligence (BI) tools to support strategic decision-making through interactive visualizations and KPI tracking.

---

# 🎯 Project Objective

The main objectives of this project are:

✅ Analyze global sales performance  
✅ Monitor profitability across regions and product categories  
✅ Identify top-performing countries and customer segments  
✅ Track sales trends over time  
✅ Evaluate discount impact on profits  
✅ Create executive-level interactive dashboards  
✅ Improve business decision-making using data visualization  

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Tableau | Dashboard Development |
| Excel / CSV | Dataset Management |
| Tableau Calculated Fields | KPI Creation |
| Tableau Maps | Geographic Visualization |
| GitHub | Project Hosting |
| Business Intelligence | Data Analysis |

---

# 📂 Dataset Description

The dataset contains global sales transaction records with the following fields:

- Order ID
- Order Date
- Month
- Quarter
- Year
- Region
- Country
- City
- Customer Segment
- Product Category
- Product Name
- Sales Channel
- Sales Amount
- Cost
- Profit
- Profit Margin %
- Quantity Sold
- Discount %
- Shipping Cost
- Delivery Status

---

# 📊 Dashboard Features

## ✅ KPI Cards
The dashboard includes major business KPIs:

- Total Sales
- Total Profit
- Profit Margin %
- Quantity Sold
- Average Order Value (AOV)

---

## ✅ Sales Analysis
- Regional Sales Comparison
- Country-wise Sales Performance
- Monthly Sales Trend Analysis
- Customer Segment Distribution

---

## ✅ Profitability Analysis
- Profit by Product Category
- Profit Margin Analysis
- Discount Impact Analysis
- Regional Profitability Heatmap

---

## ✅ Interactive Features
- Dynamic Filters
- Dashboard Actions
- Drill-Down Analysis
- Parameter Controls

---

# 📈 Tableau Concepts Used

This project demonstrates practical implementation of:

- Dimensions & Measures
- Calculated Fields
- Filters
- Parameters
- Sets & Groups
- Aggregation
- Dashboard Actions
- Geographic Mapping
- Interactive Dashboards

---

# 🧮 Calculated Fields Used

## Profit Margin %

```tableau
SUM([Profit]) / SUM([Sales Amount]) * 100
```

---

## Average Order Value (AOV)

```tableau
SUM([Sales Amount]) / COUNTD([Order ID])
```

---

## Sales Growth %

```tableau
(SUM([Sales Amount]) - LOOKUP(SUM([Sales Amount]), -1))
/
LOOKUP(SUM([Sales Amount]), -1)
```

---

## Shipping Cost Ratio

```tableau
SUM([Shipping Cost]) / SUM([Sales Amount])
```

---

# 📌 Dashboard Layout

## 🔹 Top Section
KPI Cards:
- Total Sales
- Total Profit
- Profit Margin
- Quantity Sold
- Average Order Value

---

## 🔹 Middle Section
Charts:
- Bar Chart
- Line Chart
- Donut Chart
- Heatmap
- Geographic Sales Map

---

## 🔹 Bottom Section
- Sales Performance Table
- Profitability Insights
- Summary Analysis

---

## 🔹 Sidebar
Interactive Filters:
- Region
- Country
- Product Category
- Customer Segment
- Sales Channel

---

# 🌎 Business Insights Derived

The dashboard helps identify:

✅ Highest sales-generating regions  
✅ Most profitable countries  
✅ Best-performing product categories  
✅ Monthly and quarterly sales trends  
✅ Impact of discounts on profitability  
✅ Delivery performance efficiency  

---

# 💼 Real-World Applications

This project is highly relevant for industries such as:

- Retail
- E-Commerce
- FMCG
- SaaS
- Manufacturing
- Supply Chain
- Consulting

---

# 📷 Project Screenshots

## 🖥️ Main Dashboard<img width="1920" height="1080" alt="TABLEAU-P1-OUTPUT-SS1" src="https://github.com/user-attachments/assets/5206bbc5-e08a-4c52-ba1d-8a333ee9799a" />


```markdown
![Main Dashboard](Dashboard%20Screenshots/main_dashboard.png)
```

---

## 📊 KPI Section

```markdown
![KPI Section](Dashboard%20Screenshots/kpi_section.png)
```

---

## 🌍 Sales Map

```markdown
![Sales Map](Dashboard%20Screenshots/sales_map.png)
```

---

## 📈 Profit Analysis

```markdown
![Profit Analysis](Dashboard%20Screenshots/profit_analysis.png)
```

---

# 📁 Project Folder Structure

```plaintext
Global-Sales-Performance-Dashboard/
│
├── Dataset/
│   └── global_sales_data.csv
│
├── Tableau Workbook/
│   └── Global_Sales_Dashboard.twbx
│
├── Dashboard Screenshots/
│   ├── main_dashboard.png[https://chatgpt.com/s/m_6a1861e3752c8191998b6ca8f183acaf]
[https://chatgpt.com/s/m_6a18618b45b48191921cc927878db4af]
│   ├── kpi_section.png[
│   ├── sales_map.png
│   ├── profit_analysis.png
│   └── charts_overview.png[https://chatgpt.com/s/m_6a186248d5608191a796c4636fb84f6b]
│
├── README.md
│
├── Project Report/
│   └── Project_Summary.pdf
│
└── Presentation/
    └── Tableau_Project_Presentation.pptx
```

---

# 🚀 How to Run the Project

## Step 1
Download or clone the repository.

```bash
git clone https://github.com/your-username/global-sales-performance-dashboard.git
```

---

## Step 2
Open Tableau Desktop or Tableau Public.

---

## Step 3
Open the Tableau workbook:

```plaintext
Global_Sales_Dashboard.twbx
```

---

## Step 4
Refresh the dataset connection if required.

---

## Step 5
Use filters and dashboard actions to explore insights.

---

# 🏆 Key Learnings

Through this project, I gained practical experience in:

- Tableau Dashboard Development
- Business Intelligence
- Data Visualization
- KPI Reporting
- Profitability Analysis
- Interactive Dashboard Design
- Business Storytelling
- Data Analytics

---

# 📌 Resume Project Description

## Short Version

Developed an interactive Tableau dashboard for global sales and profitability analysis using KPI-driven business intelligence techniques.

---

## Professional ATS-Friendly Version

Designed and developed a comprehensive Tableau-based Global Sales Performance & Profitability Dashboard integrating KPI analytics, geographic visualizations, profitability tracking, customer segmentation, and interactive business intelligence reporting for strategic decision-making.

---

# 🔮 Future Enhancements

Possible future improvements include:

- Predictive Sales Forecasting
- Real-Time Data Integration
- AI-Based Recommendations
- Customer Churn Analysis
- Executive Summary Reports
- Advanced Drill-Through Analytics

---

# 📌 GitHub Repository Name

```plaintext
global-sales-performance-profitability-dashboard
```

---

# 📌 Repository Description

```plaintext
Interactive Tableau dashboard for analyzing global sales performance, profitability trends, KPI metrics, and regional business insights.
```

---

# ✅ Final Checklist Before Publishing

- [x] Dataset added
- [x] Tableau workbook included
- [x] Dashboard screenshots uploaded
- [x] README completed
- [x] Folder structure organized
- [x] Repository set to Public
- [x] Files tested successfully

---

# 🤝 Connect With Me

If you found this project helpful, feel free to connect and provide feedback.

⭐ Star this repository if you liked the project!

---

# 📢 Hashtags

#Tableau #BusinessIntelligence #DataAnalytics #Dashboard #SalesAnalytics #DataVisualization #BusinessAnalysis #Analytics #GitHub #MBA #TableauDashboard
