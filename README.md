# 🛍️ ShopEase E-Commerce Sales Analysis

## 📌 Project Overview
This project analyzes an e-commerce sales dataset to explore sales performance, product categories, customer demographics, order details, and business insights using Python.

The goal of this project is to practice data analysis techniques and transform raw data into meaningful insights that can help businesses make better decisions.
## 📈 Project Visualization
![ShopEase Ecommerce_sales analysics(https://github.com/Veerpal-gill/ShopEase_ECommerce-Sales-Analysics/blob/33d43682b6b45cfa4f5494aa94eeffba6302e47f/Screenshot%202026-11-26%20203247.png)]

## 🎯 Project Objectives
- Explore and understand the e-commerce dataset.
- Analyze total order value across product categories.
- Identify the highest-performing product category.
- Explore customer and order information.
- Visualize sales data using charts.
- Practice Python data analysis skills.

## 🛠️ Tools & Technologies
- Python 🐍
- Pandas
- Matplotlib
- Google Colab
- Excel

## 📂 Dataset Overview
The dataset contains **100 records and 18 columns**.

| Column Name | Description |
|---|---|
| Order_ID | Unique order identification |
| Order_Date | Date of the order |
| Customer_ID | Unique customer identification |
| Customer_Age | Age of the customer |
| Gender | Customer gender |
| City | Customer city |
| State | Customer state |
| Product_Category | Category of the product |
| Product_Name | Name of the product |
| Order_Value | Order value |
| Quantity | Number of items ordered |
| Discount | Discount applied |
| Shipping_Cost | Shipping cost |
| Delivery_Days | Delivery time |
| Customer_Rating | Customer rating |
| Payment_Method | Payment method |
| Return_Status | Return status |
| Membership_Type | Customer membership type |

## 🔍 Data Analysis Process

### 1. Data Loading
Imported the dataset into Python using Pandas.

### 2. Data Exploration
- Viewed the first five rows using `df.head()`.
- Checked dataset dimensions using `df.shape`.
- Reviewed column names using `df.columns`.
- Checked data types and missing values using `df.info()`.

### 3. Sales Analysis
Grouped order values by product category and calculated total sales for each category using Pandas.

```python
category_sales = df.groupby("Product_Category")["Order_Value"].sum()
category_sales
```

### 4. Data Visualization
Created a bar chart using Matplotlib to compare total order value across product categories.

```python
category_sales.plot(kind="bar", figsize=(6,4))

plt.title("Total Sales by Product Category")
plt.xlabel("Product Category")
plt.ylabel("Total Order Value")
plt.show()
```

## 📊 Key Findings

### Total Order Value by Product Category

| Product Category | Total Order Value |
|---|---:|
| 🏠 Home | $10,284.44 |
| 💄 Beauty | $8,451.71 |
| 👗 Fashion | $7,912.98 |
| ⚽ Sports | $7,812.98 |
| 📱 Electronics | $7,165.50 |

### Key Insights
- 🏆 **Home** generated the highest total order value of **$10,284.44**.
- 💄 Beauty ranked second with **$8,451.71**.
- 📱 Electronics generated the lowest total order value among the categories, at **$7,165.50**.
- Product category analysis helps identify which categories contribute more to overall sales.

## 📈 Visualization

A bar chart was created to visualize total order value across product categories and compare category performance.

## 💡 Business Recommendation
Businesses can use these insights to understand category performance, plan inventory, focus marketing strategies on high-performing categories, and identify opportunities to improve sales in lower-performing categories.

## 📚 Skills Demonstrated
- Data Exploration
- Data Analysis
- Data Grouping and Aggregation
- Python Programming
- Pandas
- Data Visualization
- Business Insights
- Analytical Thinking

## 🚀 What I Learned
Through this project, I practiced exploring datasets, grouping and summarizing data, calculating sales totals, creating visualizations, and communicating findings.

This project helped me strengthen my practical Python and data analytics skills.

## 📬 Author and Contact with me 
veerpal Gill

Aspiring Data Analyst

Email veerpalgill963@gmail.com

www.linkedin.com/in/veerpal-gill

I am open to entry-level opportunities, internships, and learning experiences in Data Analytics, MIS, and Reporting.

Thank you for visiting my project! ⭐
