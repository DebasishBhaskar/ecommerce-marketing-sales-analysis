# ecommerce-marketing-sales-analysis
Mini project analyzing customer behavior, marketing effectiveness, and pricing strategies.

# E-commerce Marketing & Sales Analysis 📊

## 1. 📌 Business Problem

This project explores customer behavior, marketing effectiveness, pricing sensitivity, and seasonal patterns in an e-commerce dataset. The objective is to derive actionable insights to optimize marketing efforts, pricing strategies, and overall revenue.

---

## 2. 📦 Data Description

**Source**: Provided in-course datasets  
**Files Used**:
- `Online_Sales.csv` (https://github.com/DebasishBhaskar/ecommerce-marketing-sales-analysis/blob/main/Online_Sales.csv)
- Columns: [CustomerID,Transaction_ID,Transaction_Date,Product_SKU,Product_Description,Product_Category,Quantity,Avg_Price,Delivery_Charges,Coupon_Status]
- `Customers_Data.csv` (https://github.com/DebasishBhaskar/ecommerce-marketing-sales-analysis/blob/main/Customers_Data.csv)
- Columns: [CustomerID	Gender	Location	Tenure_Months]
- `Discount_Coupon.csv` (https://github.com/DebasishBhaskar/ecommerce-marketing-sales-analysis/blob/main/Discount_Coupon.csv)
- Columns: [Month	Product_Category	Coupon_Code	Discount_pct]
- `Marketing_Spend.csv` (https://github.com/DebasishBhaskar/ecommerce-marketing-sales-analysis/blob/main/Marketing_Spend.csv)
- Columns: [Date	Offline_Spend	Online_Spend]
- `Tax_Amount.csv` (https://github.com/DebasishBhaskar/ecommerce-marketing-sales-analysis/blob/main/Tax_amount.csv)
- Columns: [Product_Category	GST]

**Size**: ~10,000 records total  
**Key Variables**:
- CustomerID, Transaction_ID, Transaction_Date, Avg_Price, Delivery_Charges
- `CustomerID`, `Order_Value`, `Delivery_Charges`, `Coupon_Status`, Product_Category, GST
- `Demographics`: Gender, Location, Tenure_Months
- `Time variables`: Transaction_Date

---

## 3. 🔍 EDA & Business Questions

### 🎯 Goals:
- Analyze sales trends by category, location, and seasonality
- Study delivery charges and tax influence on spending
- Identify peak vs low-performing days
- Understand marketing ROI and coupon impacts

### 🧠 Key Analyses:
- Groupby aggregations on time, category, and demographics
- Pearson correlation & ANOVA tests to validate significance
- Line plots, heatmaps, and bar charts for storytelling

### 🧮 Methods:
- Merging multiple datasets
- Grouping and pivoting for temporal patterns
- Statistical testing: Pearson, ANOVA
- Visualization via matplotlib and seaborn

---

## 4. 📁 Contents

- `DebasishBhaskar_Ecommerce_Marketing_Analysis.ipynb` – Main Colab notebook


