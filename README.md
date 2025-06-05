# ☕ Cafe Sales Analysis

An end-to-end data analysis project on café sales using Python and Power BI. The project involves cleaning messy sales data, performing exploratory data analysis, engineering useful features, and developing an interactive dashboard to uncover valuable business insights.

---

## 📌 Table of Contents

- [Business Problem](#business-problem)
- [Objective](#objective)
- [Tools Used](#tools-used)
- [Business Questions](#business-questions)
- [Dataset](#dataset)
- [Important Features](#important-features)
- [Data Preprocessing](#data-preprocessing)
- [Power BI Dashboard](#power-bi-dashboard)
- [Key Insights](#key-insights)
- [Author](#author)

---

## 🧩 Business Problem

The café business faces challenges understanding its sales performance due to messy and inconsistent data. This makes it difficult to effectively identify customer preferences, product demand trends, and payment behaviors.

---

## 🎯 Objective

- Clean and preprocess dirty café sales data
- Analyze customer and product sales trends
- Identify top-performing products and sales periods
- Build an interactive dashboard for business insights

---

## 🛠️ Tools Used

- **Python (Google Colab)** – Data Cleaning, EDA, Feature Engineering
- **Power BI** – Visualization and Interactive Dashboard

---

## ❓ Business Questions

- Which items are selling the most and the least?
- What are the most common payment methods?
- When do customers spend the most (days, months)?
- Which locations perform better in sales?
- How does customer behavior change over the week?

---

## 📂 Dataset

- **Source**: [Kaggle – Dirty Cafe Sales Dataset](#)
- **File**: `dirty_cafe_sales.csv`
- **Records**: 10,000
- **Features**: 8

---

## 🧾 Important Features

| Feature            | Description                                  |
|--------------------|----------------------------------------------|
| Transaction ID     | Unique transaction identifier                |
| Item               | Name of the product sold(Menu)                     |
| Quantity           | Number of units sold                         |
| Price Per Unit     | Price of each unit                           |
| Total Sales        | Total amount = Quantity × Price per unit              |
| Payment Method     | Mode of payment (Cash, Card, etc.)           |
| Location           | Sale location (In-store or Takeaway)         |
| Transaction Date   | Date of transaction                          |

---

## 🧹 Data Preprocessing

Performed in Python (Google Colab):
- Removed invalid values (e.g., `"UNKNOWN"`, `"ERROR"`)
- Filled missing values using appropriate techniques
- Converted data types for analysis
- Created new features: `Day_Name`, `Month`, `Is_Month_End`
- Exported cleaned data to Excel for Power BI

---

## 📊 Power BI Dashboard

Power BI dashboard includes:
- **KPIs**: Total Sales, Average Sales, Total orders, Total items in meanu, Top performing product 
- **Trends**: Monthly & Daily Sales, Top Items
- **Distribution**: Payment Methods, Locations, Sales by item
- **Filters**: Dynamic slicers for Item, month, Location and Payment Method

> 🔗 [Dashboard Screenshot]
![image](https://github.com/user-attachments/assets/17cedf59-7350-4613-8329-dce24eeced64)


---

## 📈 Key Insights

- **Top Products**: Salad, Sandwich, Smoothie lead in sales
- **Peak Days**: Weekends and month-ends show higher sales
- **Digital Payments** dominate over cash
- **Takeaway Sales** outperform In-store
- **Recommendation**: Consider weekday promotions and bundling bestsellers

---

## 👨‍💻 Author

**Pravin Paradkar**  
- 📧 pravindparadkar2003@gmail.com  
- 💼 Aspiring Data Analyst | Skilled in Advanced Excel, Python, SQL, Power BI  
- 🌐 [LinkedIn](https://www.linkedin.com/in/pravinparadkar/)

---

## 📜 License

This project is licensed under the CC BY-SA 4.0 License.

---
