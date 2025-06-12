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

Dataset description: Transaction data has been provided from 1st Jan 2019 to 31st Dec 2019. 

The datasets below have been provided.

Online_Sales.csv: This file contains actual orders data (point of Sales data) at the transaction level with the following variables.
1.	CustomerID: Customer unique ID
2.	Transaction_ID: Transaction Unique ID
3.	Transaction_Date: Date of Transaction
4.	Product_SKU: SKU ID – Unique Id for product
5.	Product_Description: Product Description
6.	Product_Cateogry: Product Category
7.	Quantity: Number of items ordered
8.	Avg_Price: Price per one quantity
9.	Delivery_Charges: Charges for delivery
10.	Coupon_Status: Any discount coupon applied

Customers_Data.csv: This file contains customer’s demographics.
1.	CustomerID: Customer Unique ID
2.	Gender: Gender of the customer
3.	Location: Location of Customer
4.	Tenure_Months: Tenure in Months

Discount_Coupon.csv: Discount coupons have been given for different categories in different
months
1.	Month: Discount coupon applied in that month
2.	Product_Category: Product category
3.	Coupon_Code: Coupon Code for the given Category and the given month
4.	Discount_pct: Discount Percentage for the given coupon

Marketing_Spend.csv: Marketing spend on both offline & online channels on day day-wise.
1.	Date: Date
2.	Offline_Spend: Marketing spend on offline channels like TV, Radio, NewsPapers, hoardings, etc.
3.	Online_Spend: Marketing spend on online channels like Google keywords, Facebook, etc.

Tax_Amount.csv: GST Details for given category
1.	Product_Category: Product Category
GST: Percentage of GST

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


