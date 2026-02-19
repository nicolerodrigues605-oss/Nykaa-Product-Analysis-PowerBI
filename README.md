📊 Nykaa Product Analysis – Power BI Dashboard

📌 Project Overview
This project analyzes Nykaa product data to understand brand distribution, category trends, discount strategies, pricing patterns, and the impact of free gifts on customer engagement.
The dashboard provides business insights using data cleaning, transformation, and DAX measures in Power BI.

🎯 Project Objectives
Analyze product distribution by brand and category
Study discount trends across product types
Evaluate pricing and promotional strategies
Understand the impact of free gifts on customer reviews
Provide actionable business insights through visual analytics

🧹 Data Cleaning & Transformation
The dataset required several preprocessing steps before analysis:

1️⃣ Discount Column Cleaning
Removed “%” and text from discount values
Converted discount column to numeric format
Handled missing values

2️⃣ Price Cleaning
Removed “₹” symbol from Original Price and Offer Price
Converted price columns into numeric format

3️⃣ Extracting Brand Name
The Product column contained both brand name and product details
Extracted the Brand Name from the product text using transformation logic
Created a separate Brand column for brand-wise analysis

4️⃣ Extracting Category
Derived Category column from product names
Standardized category values (e.g., Serum, Cleanser, Lip Product, Facial Oil, etc.)
Enabled category-level insights and comparisons

5️⃣ Creating Discount Range Column
Grouped discount values into buckets:
0–10%
10–20%
20–30%
30–40%
Improved readability of visual analysis

6️⃣ Creating Discount Sort Column
Created a numeric helper column
Used “Sort by Column” to display discount ranges in logical order

📊 DAX Measures Created
Total Products
Average Original Price
Average Discount
Total Reviews
Product Count
These measures helped generate dynamic KPI cards and visual insights.

📈 Visualizations Used
Card Visuals – Display key KPIs
Column Charts – Brand and Category Distribution
Line Chart – Discount Analysis by Product Type
Treemap – Category proportion analysis
Slicers – Free Gift filter interaction

💡 Key Insights
Certain brands dominate product listings.
Serums and cleansers have the highest product distribution.
Roll-ons and facial oils receive higher average discounts.
Products with free gifts show increased customer engagement.
Discount strategies vary significantly across product types.

🛠 Tools & Technologies
Power BI
DAX
Power Query
Data Modeling

📁 Files Included

.pbix Power BI file
Dashboard screenshots

📌 Conclusion

This dashboard demonstrates end-to-end data handling — from data cleaning and transformation to DAX measure creation and business insight generation. It highlights practical Power BI skills including data modeling, calculated columns, sorting logic, KPI creation, and interactive reporting.
