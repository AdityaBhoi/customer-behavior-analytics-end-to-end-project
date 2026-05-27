# 📊 Customer Behavior Analytics — End-to-End Data Analyst Project

<div align="center">

![Python](https://img.shields.io/badge/Python-Analysis-blue?style=for-the-badge&logo=python)
![SQL](https://img.shields.io/badge/SQL-Database-orange?style=for-the-badge&logo=mysql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**An end-to-end Data Analytics project focused on analyzing customer purchasing behavior, sales trends, customer segmentation, and business insights using Python, SQL, Jupyter Notebook, and Power BI.**

</div>

---

# 📌 Project Overview

This project focuses on analyzing customer purchasing behavior and sales performance to uncover valuable business insights through data analysis and interactive visualizations.

The project includes:

- Data Cleaning using Python
- Exploratory Data Analysis (EDA)
- SQL Business Queries
- Customer Segmentation Analysis
- Revenue & Sales Trend Analysis
- Interactive Power BI Dashboard

The dashboard helps businesses make data-driven decisions by identifying customer trends, product performance, and purchasing patterns.

---

# 🖼️ Dashboard Preview

<div align="center">

![Dashboard Preview](Images/dashboard-preview.png)

</div>

---

# 📂 Dataset Information

| File Name | Description |
|---|---|
| `Customer Behavior.csv` | Contains customer purchase, sales, and behavioral data |

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
- Customer segmentation insights
- Age-group purchasing behavior
- Subscription analysis
- Customer review analysis

## 🟢 Revenue & Sales Analysis
- Total revenue tracking
- Product category performance
- Purchase amount trends
- Revenue contribution analysis

## 🔵 Product & Shipping Insights
- Best-performing product categories
- Shipping preference analysis
- Product demand analysis
- Customer buying trends

## 🟠 Interactive Dashboard
- Dynamic filtering
- Interactive slicers
- KPI monitoring
- Drill-down analysis

---

# 📊 Visualizations Used

| Visualization | Purpose |
|---|---|
| KPI Cards | Display business metrics |
| Donut Charts | Subscription distribution |
| Bar Charts | Customer & category analysis |
| Column Charts | Revenue comparison |
| Slicers | Interactive dashboard filtering |

---

# 🔍 Key Insights

| # | Insight |
|---|---|
| 👕 | Clothing category generated the highest revenue |
| 👥 | Young adults contributed the highest sales |
| 🚚 | Standard shipping is the most preferred shipping method |
| ⭐ | Average customer review rating is 3.75 |
| 📊 | Non-subscribed customers dominate the customer base |

---

# 🛠️ Tools & Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SQL**
- **Jupyter Notebook**
- **Power BI**
- **DAX (Data Analysis Expressions)**

---

# ⚙️ Power BI Features Implemented

## ✅ Data Cleaning
- Handled missing values
- Removed duplicate records
- Corrected data types
- Performed feature engineering

## ✅ Exploratory Data Analysis
- Revenue trend analysis
- Customer behavior analysis
- Product category analysis
- Shipping preference analysis

## ✅ SQL Analysis
Used SQL queries for:
- Revenue analysis
- Customer segmentation
- Product performance analysis
- Review analysis

### Example SQL Query

```sql
SELECT category,
SUM(purchase_amount) AS total_revenue
FROM customer
GROUP BY category
ORDER BY total_revenue DESC;
```

## ✅ DAX Measures

```DAX
Total Revenue = SUM(customer[purchase_amount])

Total Customers = DISTINCTCOUNT(customer[customer_id])

Average Rating = AVERAGE(customer[review_rating])

Average Purchase = AVERAGE(customer[purchase_amount])
```

## ✅ Interactive Dashboard
- Dynamic KPI cards
- Drill-down analysis
- Interactive filtering
- User-friendly dashboard design

---

# 📁 Project Structure

```bash
customer-behavior-analytics-end-to-end-project/
│
├── Dataset/
│   └── Customer Behavior.csv
│
├── SQL/
│   └── customer_analysis_queries.sql
│
├── Jupyter Notebook/
│   └── customer_behavior_analysis.ipynb
│
├── Power BI Dashboard/
│   └── CUSTOMER BEHAVIOR ANALYTICS.pbit
│
├── Images/
│   └── dashboard-preview.png
│
├── README.md
│
└── requirements.txt
```

---

# 🚀 How to Use

## Python & Jupyter Notebook

1. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

2. Open Jupyter Notebook

```bash
jupyter notebook
```

3. Run:

```bash
customer_behavior_analysis.ipynb
```

---

## Power BI Dashboard

1. Open the `.pbit` file in Power BI Desktop
2. Load the CSV dataset
3. Refresh the dashboard
4. Explore insights using slicers and filters

---

# 📌 Business Use Cases

This project helps businesses:

- Understand customer purchasing behavior
- Identify top-performing product categories
- Improve shipping strategies
- Monitor revenue performance
- Analyze customer satisfaction
- Make data-driven business decisions

---

## 👤 Author

**Aditya Bhoi**

- 🔗 [LinkedIn](https://www.linkedin.com/in/adityabhoi/)
- 🐙 [GitHub](https://github.com/AdityaBhoi/)

---

<div align="center">

⭐ If you found this project useful, give it a star! ⭐

Made with ❤️ using Python, SQL & Power BI

</div>
