# Apple Product Sales Analytics Dashboard

> An end-to-end Business & Product Analytics project that transforms raw Apple product sales data into actionable business insights through SQL, Python, and Power BI.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![Python](https://img.shields.io/badge/Python-Analytics-blue?logo=python)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)
![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📌 Project Overview

Apple sells multiple product categories across different countries, sales channels, and customer segments. However, business leaders require more than sales reports—they need meaningful insights to understand performance drivers and make strategic decisions.

This project builds an Executive Analytics Dashboard that enables stakeholders to:

- Monitor overall business performance
- Analyze product-level performance
- Identify revenue drivers
- Explore customer behavior
- Perform root cause analysis
- Generate strategic business recommendations

The project follows a complete analytics workflow from data cleaning to executive decision support.

---

# 🎯 Business Objectives

- Analyze Apple's global sales performance
- Identify top-performing products and categories
- Evaluate customer ratings and return behavior
- Compare regional and sales channel performance
- Discover high-value customer segments
- Support strategic business decision-making

---

# 🛠 Tech Stack

- **Power BI**
- **PostgreSQL**
- **SQL**
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**
- **Excel**

---

# 📂 Dataset Information

The dataset contains Apple product sales records from multiple countries with information regarding:

- Product Category
- Product Name
- Revenue
- Units Sold
- Customer Rating
- Return Status
- Sales Channel
- Customer Segment
- Country
- Region
- Storage Variant
- Payment Method
- Previous Device
- Discounts

---

# 📊 Key Business KPIs

| KPI | Value |
|------|--------|
| 💰 Total Revenue | **$18.04 Million** |
| 🛒 Total Orders | **11.50K** |
| 📦 Units Sold | **23.27K** |
| 💵 Average Selling Price | **$777.37** |
| ⭐ Average Customer Rating | **4.00 / 5** |
| 🔁 Return Rate | **11.80%** |

---

# 🔍 Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning (Python + SQL)
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Business KPI Generation
      │
      ▼
Power BI Dashboard
      │
      ▼
Executive Insights
      │
      ▼
Strategic Recommendations
```

---
### Business Question Answered

1. Measure overall business performance using key KPIs.
2. Identify top revenue-generating product categories.
3. Find the best-selling product categories by units sold.
4. Compare revenue across sales channels.
5. Identify the highest revenue-generating countries.
6. Compare performance across customer segments.
7. Identify categories exceeding $1M in revenue.
8. Compare average selling price across categories.
9. Analyze purchasing patterns by customer age group.
10. Find sales channels outperforming the company average.
11. Calculate revenue contribution by product category.
12. Rank product categories by total revenue.
13. Rank countries by revenue generated.
14. Identify channels with the highest average order value.
15. Rank product categories by customer ratings.
16. Analyze month-over-month revenue trends.
17. Track cumulative revenue growth over time.
18. Detect high-revenue countries with high return rates.
19. Identify profitable categories with high product returns.
20. Compare customer segments by revenue and returns.
21. Find the top product in each category.
22. Identify the best-performing country for each category.
23. Find highly rated products with low revenue.
24. Detect profitable products with high return rates.
25. Evaluate revenue across different price bands.
26. Assess the impact of discounts on sales performance.
27. Rank the top three products within each category.


# 📈 Dashboard Overview

## 🏠 Page 1 — Executive Overview

Provides a high-level business summary through executive KPIs.

### Highlights

- Total Revenue
- Total Orders
- Units Sold
- Average Selling Price
- Customer Rating
- Return Rate
- Monthly Revenue Trend
- Revenue by Category
- Revenue by Country
- Revenue by Sales Channel
- Top Selling Products

# 📦 Page 2 — Product Analytics

A detailed analysis of Apple's product portfolio.

### Highlights

- Revenue Contribution by Category
- Product Rating vs Return Rate
- Average Selling Price by Category
- Return Rate by Category
- Return Rate by Customer Segment

### Key Insights

- Mac contributes **46.4%** of total revenue.
- Premium-priced Macs achieve the highest ASP.
- Customer ratings remain consistently around **4.0**.
- Return rates show limited variation across categories.
- Education customers contribute the highest revenue.
- Accessories generate the lowest standalone revenue.


# 🎯 Page 3 — Executive Decision Center

The final dashboard enables executives to investigate revenue drivers through an interactive Decomposition Tree.

### Highlights

- Interactive Revenue Driver Analysis
- Opportunities
- Risks
- Strategic Recommendations
- AI Decision Assistant (Future Scope)


### Dashboard Preview
---


# 📌 Major Insights

### Revenue

- Mac contributes nearly **46%** of total company revenue.
- iPhone remains the second-largest revenue contributor.
- Accessories contribute the least revenue.

---

### Customers

- Education segment generates the highest revenue.
- Business customers strongly contribute to premium product sales.

---

### Product Performance

- Premium Mac devices maintain both high revenue and premium pricing.
- Customer ratings remain consistently high (~4.0).

---

### Returns

- Overall return rate is **11.8%**.
- Premium iPhones require closer monitoring for return reduction.

---

### Sales Channels

- Authorized Resellers and Apple Stores generate significant revenue.
- Channel-wise performance varies across regions.

---

# 💼 Business Recommendations

### 🚀 Growth Opportunities

- Expand Mac marketing campaigns targeting Education customers.
- Increase cross-selling through Apple ecosystem bundling.
- Strengthen premium positioning of Mac products.

---

### ⚠ Risk Areas

- Investigate causes behind premium iPhone returns.
- Reduce dependency on a single product category.
- Improve Accessories contribution through bundle pricing.

---

### Strategic Actions

| Priority | Recommendation | Expected Impact |
|-----------|----------------|----------------|
| 🔴 High | Expand Mac marketing in Education | Increase premium sales |
| 🔴 High | Reduce premium iPhone returns | Lower return costs |
| 🟡 Medium | Bundle AirPods with Mac purchases | Increase Average Order Value |
| 🟢 Low | Optimize Accessories pricing | Improve category contribution |

---

# 📁 Repository Structure

```
Apple-Product-Sales-Analytics/

│
├── Dashboard/
│     Apple Product Sales Analysis.pbix
│
├── Dataset/
│     apple_sales.csv
│     cleaned_dataset.csv
│
├── SQL/
│     Data_Cleaning.sql
│     Business_Queries.sql
│
├── Python/
│     EDA.ipynb
│     Data_Cleaning.ipynb
│
├── Images/
│     Page1.png
│     Page2.png
│     Page3.png
│
└── README.md
```

---

# 📚 Skills Demonstrated

- Data Cleaning
- SQL Query Writing
- PostgreSQL
- Exploratory Data Analysis
- Data Visualization
- KPI Design
- Dashboard Development
- Business Analytics
- Product Analytics
- Executive Reporting
- Root Cause Analysis
- Data Storytelling

---

# 🚀 Future Enhancements

The project will be extended with an AI-powered Executive Decision Assistant.

Planned features include:

- 🤖 AI-generated executive summaries
- 💬 Natural language business queries
- 📄 Automated PDF report generation
- 📈 Sales forecasting
- 🔮 Predictive analytics
- 🌍 Dashboard deployment
- ☁️ Cloud hosting

---

# 👩‍💻 Author

**Aditi Jha**

B.Tech  
PDPM IIITDM Jabalpur

**Interested in**

- Business Analytics
- Product Analytics
- Data Analytics
- AI-powered Decision Intelligence

---

⭐ If you found this project useful, feel free to star the repository.
