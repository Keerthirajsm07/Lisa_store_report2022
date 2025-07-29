# Lisa_store_report2022
Annual sales analysis of Vrinda Store (2022) using Excel – includes data cleaning, processing, visualization, and reporting to understand customer behavior and improve 2023 sales.
# Vrinda Store Sales Analysis (Excel Project)

## 📌 Objective
Vrinda Store wants to create an annual sales report for 2022 to better understand its customers and improve sales in 2023.  
This project involves data cleaning, processing, analysis, visualization, and generating reports.

---

## 🛠 Project Workflow
- *Data Cleaning:* Fixed errors, replaced incorrect values.
- *Data Processing:*  
  - Created Age Group column using formulas  
  - Extracted Month from date  
- *Data Analysis:* Analyzed sales by gender, state, age group, and sales channels.
- *Data Visualization:* Created charts to show top states, gender-based sales, channels contribution, and more.
- *Reporting:* Generated insights and recommendations for improving sales.

---

## 📊 Insights & Findings
- Women contributed *65%* of the sales.
- Top 3 states: Maharashtra, Karnataka, Uttar Pradesh (*35%* combined).
- Age group *30–49 years* contributed the highest (*50%*).
- Sales channels Amazon, Flipkart, Myntra contributed *80%*.
- Recommendation: Target women (30–49 yrs) in MH, KA, UP with ads/coupons on Amazon, Flipkart, Myntra.

---

## ❓ Sample Questions Answered
- Compare sales and orders using a single chart.
- Identify the month with highest sales and orders.
- Gender-based purchase comparison.
- Top 10 states contributing to sales.
- Relation between age and gender based on orders.
- Sales contribution by channels.
- Highest selling product category.

---

## 🧮 Excel Formulas Used
- *Age Group:=IF(E2>=50,"Senior",IF(E2<=30,"Teenager","Adult"))* 

- *Month Extraction:=TEXT(G2,"mmm")     // short month (Feb),  =TEXT(G2,"mmmm")    // full month (February)*
