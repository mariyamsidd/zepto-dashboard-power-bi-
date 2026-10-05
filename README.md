# zepto-dashboard-power-bi-
📊 Zepto Analysis Dashboard | Power BI

An interactive Zepto Sales & Product Analysis Dashboard built using Microsoft Power BI to analyze product sales, pricing, discounts, categories, stock availability, and product-wise performance.

This project transforms raw Zepto product data into an interactive business intelligence dashboard that helps understand sales performance, product quantity, pricing patterns, category contribution, and inventory availability.

---

📌 Project Overview

The Zepto Analysis Dashboard is a Power BI data visualization and business analytics project designed to provide a comprehensive overview of Zepto's product and sales data.

The dashboard combines multiple KPIs, charts, and interactive filters to make the data easier to understand and support data-driven decision-making.

The analysis focuses on:

- Total Revenue
- Total Products Sold
- Average Discount Price
- Average Selling Price
- Out-of-Stock Products
- Category-wise performance
- Product-wise quantity
- Product pricing trends
- Discount and selling-price analysis
- Inventory availability

---

🎯 Project Objectives

The main objectives of this project are:

1. Analyze overall sales and revenue performance.
2. Identify products contributing significantly to sales.
3. Compare product quantities across different categories.
4. Analyze average discount and selling prices.
5. Identify out-of-stock products by category.
6. Understand product pricing patterns.
7. Create an interactive dashboard for business analysis.
8. Present complex data through simple and meaningful visualizations.

---

🛠️ Tools & Technologies

Tool| Purpose
Microsoft Power BI| Dashboard development & data visualization
Power Query| Data cleaning and transformation
DAX| KPI calculations and measures
Data Visualization| Business insights and reporting

---

📊 Dashboard KPIs

The dashboard contains the following key performance indicators:

💰 Total Revenue

Displays the overall revenue generated from the products included in the dataset.

Dashboard Value: 12bn

📦 Total Product Sold

Shows the total quantity of products sold.

Dashboard Value: 796K

🏷️ Average Discount Price

Represents the average discount-related pricing metric across the products.

Dashboard Value: 7.62

💵 Average Selling Price

Shows the average selling price of the products.

Dashboard Value: 14.19K

🚨 Products Out of Stock

Displays the number of products/items currently marked as out of stock.

Dashboard Value: 453

---

📈 Dashboard Visualizations

1. Category by Product

A bar chart is used to compare the number of products across different categories.

This visualization helps identify:

- Categories with a larger product assortment
- Categories with fewer products
- Product distribution across the business

---

2. Number of Out-of-Stock Products by Category

A donut chart displays the distribution of out-of-stock products across different categories.

It helps identify:

- Categories experiencing higher stock-outs
- Categories with relatively better availability
- Potential inventory management issues

---

3. MRP vs Discount/Selling Price

A line/area visualization is used to analyze pricing patterns.

This visualization helps compare:

- MRP
- Discount/selling price
- Price variation across products
- Pricing patterns within the dataset

---

4. Category by Product

Another category-level visualization compares product distribution across categories.

This allows users to quickly identify categories with:

- Higher product availability
- Lower product availability
- Greater product variety

---

5. Product by Quantity

A bar chart compares products based on their quantity/sales volume.

This helps identify:

- Best-performing products
- High-quantity products
- Products contributing significantly to overall sales volume

---

🎛️ Interactive Filters

The dashboard includes interactive filtering options such as:

Category

Users can select a specific product category to analyze its performance.

Product Name

Users can select individual products and analyze their corresponding data.

These filters allow the dashboard to move from a high-level business overview to product-level analysis.

---

🔍 Key Business Questions Answered

The dashboard can help answer questions such as:

- What is the total revenue generated?
- How many products have been sold?
- What is the average selling price?
- What is the average discount?
- How many products are out of stock?
- Which categories contain the most products?
- Which categories have the highest number of out-of-stock products?
- Which products have the highest quantity?
- How does MRP vary across products?
- How are products distributed across different categories?
- Which products/categories may require inventory attention?

---

📌 Key Insights

Based on the dashboard, some of the major analytical observations include:

- The dataset contains a large product assortment distributed across multiple categories.
- Product quantities vary significantly across different products.
- A noticeable number of products are marked as out of stock.
- Out-of-stock products are distributed across multiple categories.
- Product pricing shows variation between MRP and selling/discounted prices.
- The dashboard makes it easier to identify high-quantity products and categories requiring attention.
- Category-level analysis can help businesses understand product assortment and inventory distribution.

«Note: Insights can change depending on the filters selected in the dashboard.»

---

🧹 Data Preparation

Before creating the dashboard, the data can be prepared using Power Query.

Typical data preparation steps include:

- Removing unnecessary columns
- Handling missing values
- Checking duplicate records
- Correcting data types
- Cleaning product/category names
- Formatting numerical fields
- Preparing pricing columns
- Creating analysis-ready data

---

🧮 Data Analysis & DAX

Power BI measures can be used to calculate important business metrics such as:

- Total Revenue
- Total Quantity Sold
- Average Discount
- Average Selling Price
- Out-of-Stock Count
- Category-wise metrics
- Product-wise metrics

Example DAX measures:

Total Revenue = SUM('Zepto'[Revenue])

Total Quantity = SUM('Zepto'[Quantity])

Average Selling Price = AVERAGE('Zepto'[Selling Price])

Out of Stock = 
CALCULATE(
    COUNTROWS('Zepto'),
    'Zepto'[Out of Stock] = TRUE()
)

«The exact DAX formulas should be adjusted according to the actual column names and data structure used in the project.»

---

🎨 Dashboard Design

The dashboard uses a clean business-oriented design with:

- KPI cards
- Bar charts
- Donut chart
- Area/line visualization
- Interactive slicers
- Category-based analysis
- Product-level analysis

The dashboard is designed to make important information visible at a glance while still allowing users to explore detailed product-level information.

---

📁 Suggested Repository Structure

Zepto-PowerBI-Dashboard/
│
├── README.md
│
├── PowerBI/
│   └── Zepto_Analysis_Dashboard.pbix
│
├── Dataset/
│   └── zepto_data.csv
│
├── Screenshots/
│   └── zepto_dashboard.png
│
└── Documentation/
    └── Project_Notes.pdf

---

🚀 How to Use This Project

1. Download or clone this repository.
2. Open the ".pbix" file using Microsoft Power BI Desktop.
3. If required, update the dataset/file path.
4. Refresh the data.
5. Use the Category and Product Name filters to explore the dashboard.
6. Interact with the visualizations to analyze sales, pricing, products, and inventory.

---

📸 Dashboard Preview

"Zepto Analysis Dashboard" (Screenshots/zepto_dashboard.png)

---

💡 Skills Demonstrated

This project demonstrates practical skills in:

- Power BI
- Data Visualization
- Business Intelligence
- Data Analysis
- Power Query
- DAX
- KPI Development
- Dashboard Design
- Product Analysis
- Sales Analysis
- Inventory Analysis
- Interactive Reporting
- Business Insights

---

📈 Future Improvements

The dashboard can be further enhanced by adding:

- Monthly/weekly sales trends
- Profit and margin analysis
- Geographic analysis
- Customer segmentation
- Top and bottom product analysis
- Inventory turnover analysis
- Profitability by category
- Time-based sales forecasting
- Advanced DAX measures
- Drill-through pages
- Tooltip pages
- Dynamic KPI cards

---

🎓 Project Type

Business Analytics | Data Visualization | Power BI | Business Intelligence

---

👩‍💻 Author

Mariyam Siddiqui

BBA – Business Analytics

Interested in Business Analytics, Data Analysis, Business Intelligence, and Data Visualization.

---

⭐ Conclusion

The Zepto Analysis Dashboard demonstrates how Power BI can be used to convert raw product and sales data into an interactive business intelligence solution.

By combining KPIs, category analysis, product-level analysis, pricing visualization, inventory insights, and interactive filters, the dashboard provides a simple and effective way to understand business performance and identify areas that may require attention.

---

⭐ If you find this project useful, feel free to explore the repository and connect with me!
