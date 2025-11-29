# 📊 Pharma-Analytics-Insights-Dashboard

This project is an interactive  Power BI analytics dashboard  designed for a pharmaceutical company to track and analyze key business metrics across Sales, Sales Return, Marketing, and Collection operations. It provides actionable insights to support data-driven decision-making.

---

## 🚀  Project Overview 

The dashboard consolidates sales, marketing, and collection data to deliver a 360° analytical view. It highlights business performance across  States ,  HQs , and  Products , with trend analysis and KPI benchmarking.

---

## 🧼  Data Preparation 

###  Data Cleansing 

Conducted in  Power Query :

* Removed duplicates across Sales, Sales Return, Collection, and Marketing datasets
* Standardized column names and corrected inconsistent data
* Handled null values and invalid entries
* Performed data type conversions and transformations

###  Data Modeling 

Designed a robust  Star Schema  consisting of:

*  Fact Tables:  Sales, Sales Return, Collection, Marketing
*  Dimension Tables:  Date, State, HQ, Product, Party Name
* Optimized relationships for performant and accurate reporting

---

## 📊  Key Features & Metrics 

###  KPI Metrics 

*  Sales ,  Sales Return ,  Actual Sales 
*  Collection ,  Tax Figure ,  Net Collection 
*  Quantity Sold ,  Quantity Returned 
*  Marketing Expenditure 
*  DRR (Daily Run Rate) 
*  ROMI (Return on Marketing Investment) 
*  Collection Efficiency 
*  MOM (Month-over-Month) Comparisons 
*  YOY (Year-over-Year) Comparisons  *(if applicable)*

###  Dashboards 

✔  Overview Dashboard  – Summary KPIs, state-wise and HQ-wise performance
✔  Sales Dashboard  – MOM trends, product performance, HQ-wise & state-wise sales
✔  Collection Dashboard  – Monthly collection trends, efficiency analysis
✔  Marketing Dashboard  – ROMI calculations and marketing spend distribution

---

## 📈  Visualizations Used 

* Bar & Column Charts
* Line Charts (Monthly Trends)
* Pie & Donut Charts
* KPI Cards
* Tables & Matrices
* Slicers (State, HQ, Product, Date)

---

## 🧠  DAX Highlights 

Includes custom measures for:

* MOM % Change
* PM Sales, PY Sales
* DRR
* ROMI
* Collection Efficiency
* Total Actual Sales
* Percentage Contribution
* Product-wise / State-wise aggregations

---

## 🛠  Tools & Technologies 

*  Power BI Desktop 
*  Power Query 
*  DAX 
*  Excel 

---

## 📂  Project Structure 

```
📁 Pharmaceutical-Analytics-Project
│
├── 📄 README.md
├── 📊 Power BI Dashboard (.pbix)
```

---

## 👨‍💻  Author 

 Gaurav Pujari 


