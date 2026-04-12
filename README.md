# 📊 Retail Sales & Profit Optimization Analysis
# 📊 Retail Sales & Profit Optimization Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Tools Used](#tools-used)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [SQL Analysis Performed](#sql-analysis-performed)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Tableau Dashboard](#tableau-dashboard)
- [Files Included](#files-included)
- [Conclusion](#conclusion)
- [Author](#author)


---

## 📊 Project Overview
This project analyzes retail sales data to evaluate business performance across product categories, sub-categories, customer segments, and regions. The main goal was to identify which products drive profit, which ones cause losses, and how discounting affects profitability.

Using SQL, I cleaned the dataset, checked for duplicates, and performed exploratory analysis to uncover key business insights. The findings show that some high-sales products were actually unprofitable, largely due to aggressive discounting.

---

## 💼 Business Problem
The business wants to improve profitability by understanding:

- Which categories and sub-categories generate the most sales  
- Which products generate the most profit  
- Which products are losing money  
- How discounts affect profit  
- Which customer segments and regions perform best  

---

## 🛠️ Tools Used
- PostgreSQL  
- pgAdmin 4  
- Tableau Public  
- GitHub  

---

## 📁 Dataset
This project uses a retail sales dataset with 9,994 records and the following fields:

- Ship Mode  
- Segment  
- Country  
- City  
- State  
- Postal Code  
- Region  
- Category  
- Sub-Category  
- Sales  
- Quantity  
- Discount  
- Profit  

---

## 🧹 Data Cleaning
Before starting the analysis, the data was cleaned in SQL.

Cleaning steps included:
- Imported CSV data into PostgreSQL  
- Standardized column names for easier querying  
- Checked total row count after import  
- Identified duplicate records  
- Removed **17 duplicate rows**  
- Confirmed cleaned dataset contained **9,977 unique records**  

---

## 🧠 SQL Analysis Performed
The analysis focused on answering key business questions through SQL queries such as:

- Total sales and total profit  
- Sales and profit by category  
- Sales and profit by sub-category  
- Profit by region  
- Profit by segment  
- Loss-making sub-categories  
- Discount impact on sales and profit  
- Profitability patterns by sub-category and discount level  

---

## 📈 Key Insights

- **High sales ≠ high profit:** Some products like Tables generate strong revenue but result in significant losses.

- **Loss-making sub-categories identified:** Tables, Bookcases, and Supplies contribute negatively to overall profit.

- **Top profit drivers:** Copiers, Phones, Accessories, and Paper generate the highest profits.

- **Discounts reduce profitability:** Discounts above 20% frequently lead to negative profit across multiple categories.

- **Profitability threshold:** Most products remain profitable within a 0%–20% discount range.

---

## 💼 Business Recommendations

- **Limit discounts:** Keep discounts below 20% to protect profit margins.

- **Fix loss-making products:** Review pricing and cost structure for Tables, Bookcases, and Supplies.

- **Focus on high-profit items:** Increase promotion and sales efforts for Copiers, Phones, and Accessories.

- **Use data-driven pricing:** Apply discounts strategically based on product profitability.
  
---

## 📊 Tableau Dashboard
The dashboard highlights:

- Profit by sub-category  
- Sales by category  
- Discount vs profit patterns  
- Regional and segment performance  

**Tableau Dashboard Link:**  
*(Add your Tableau Public link here)*

---

## 📁 Files Included
- README.md – project overview and findings  
- SQL queries used for analysis  
- Tableau dashboard (link or screenshots)  
- Dataset (or dataset source link)  

---

## 🏁 Conclusion
This project demonstrates how SQL can be used to clean data, analyze business performance, and generate actionable insights. The analysis revealed that high sales do not always lead to profitability, especially when discounting is not controlled. By identifying loss-making products and discount-sensitive categories, this project provides valuable recommendations for improving business performance.

---

## 👤 Author
Alaa Razaq
