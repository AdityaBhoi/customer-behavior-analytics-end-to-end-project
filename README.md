# 📊 Customer Behavior Analytics Dashboard — Power BI Project

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-blue?style=for-the-badge)
![Visualization](https://img.shields.io/badge/Data-Visualization-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**An interactive Power BI dashboard designed to analyze customer purchasing behavior, sales trends, subscription insights, and revenue performance using modern data visualizations.**

</div>

---

# 📌 Project Overview

This project focuses on building an interactive **Customer Behavior Analytics Dashboard** in **Power BI** to analyze:

- Customer purchasing patterns
- Revenue performance
- Product category sales
- Customer subscription behavior
- Age-group analysis
- Shipping preferences
- Review ratings

The dashboard helps businesses understand customer trends and make data-driven decisions using powerful visual analytics.

---

# 🖼️ Dashboard Preview

<div align="center">

![Dashboard Preview](Images/dashboard-preview.png)

</div>

---

# 📂 Dataset Information

| File Name | Description |
|---|---|
| `Customer Behavior.csv` | Contains customer purchase, subscription, category, and sales data |

---

# 📊 Key Dashboard Metrics

| Metric | Value |
|---|---|
| 👥 Total Customers | **3.9K** |
| 💰 Average Purchase Amount | **$59.76** |
| ⭐ Average Review Rating | **3.75** |
| 🛒 Total Revenue | **233K** |

---

# 📈 Dashboard Features

## 🟣 Customer Analysis
- Customer subscription insights
- Gender-wise customer segmentation
- Customer age-group analysis

## 🔵 Revenue Analysis
- Revenue by category
- Revenue by age group
- Revenue performance tracking

## 🟢 Sales Insights
- Sales by category
- Sales by age group
- Product performance analysis

## 🟠 Shipping Analysis
- Shipping type preferences
- Delivery method insights

---

# 📊 Visualizations Used

| Visualization | Purpose |
|---|---|
| KPI Cards | Display overall business metrics |
| Donut Chart | Subscription status distribution |
| Column Charts | Revenue & sales comparison |
| Bar Charts | Age-group analysis |
| Slicers | Interactive dashboard filtering |

---

# 🔍 Key Insights

| # | Insight |
|---|---|
| 👕 | Clothing category generated the highest revenue |
| 👥 | Young adults contributed the highest sales |
| ⭐ | Average customer review rating is 3.75 |
| 🚚 | Standard shipping is most preferred |
| 📊 | Non-subscribed customers dominate overall customer base |

---

# 🛠️ Tools & Technologies Used

- **Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **CSV Dataset**
- **Data Visualization Techniques**

---

# ⚙️ Power BI Features Implemented

## ✅ Data Cleaning
- Removed null values
- Corrected data types
- Formatted columns properly

## ✅ Data Modeling
- Structured dataset relationships
- Optimized dashboard performance

## ✅ DAX Measures
Used custom DAX calculations for:

```DAX
Total Revenue = SUM(customer[purchase_amount])

Total Customers = DISTINCTCOUNT(customer[customer_id])

Average Rating = AVERAGE(customer[review_rating])

Average Purchase = AVERAGE(customer[purchase_amount])
```

## ✅ Interactive Dashboard
- Dynamic slicers
- Category filtering
- Gender-based analysis
- Shipping analysis
- Subscription tracking

---

# 📁 Project Structure

```bash
customer-behavior-analytics-dashboard/
│
├── Dataset/
│   └── Customer Behavior.csv
│
├── Dashboard/
│   └── CUSTOMER BEHAVIOR ANALYTICS.pbit
│
├── Images/
│   └── dashboard-preview.png
│
├── README.md
│
└── LICENSE
```

---

# 🚀 How to Use

1. Download or clone this repository
2. Open the `.pbit` file in Power BI Desktop
3. Load the CSV dataset when prompted
4. Refresh the dashboard
5. Explore insights using slicers and filters

---

# 📌 Business Use Cases

This dashboard helps businesses:

- Understand customer purchasing behavior
- Analyze category-wise revenue
- Monitor customer subscription trends
- Improve shipping strategies
- Identify high-performing customer segments
- Enhance customer experience decisions

---

# 👤 Author

**Aditya Bhoi**

- 🔗 LinkedIn: www.linkedin.com/in/adityabhoi
- 🐙 GitHub: github.com/AdityaBhoi

---

<div align="center">

⭐ If you found this project useful, give it a star! ⭐

Made with ❤️ using Power BI

</div>