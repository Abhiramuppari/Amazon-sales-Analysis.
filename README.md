# Amazon-sales-Analysis.
📊 Amazon Sales Data Analysis Project
📝 Overview

This project focuses on performing Exploratory Data Analysis (EDA) on Amazon's sales report dataset to uncover key business insights such as product performance, order fulfillment trends, and customer purchasing patterns.
The goal of this analysis is to identify the most profitable product categories, understand shipment trends, and gain data-driven insights that can help optimize e-commerce strategies.

🎯 Objectives

Clean and preprocess raw Amazon sales data.

Analyze order status, fulfillment methods, and courier performance.

Identify the best-selling product categories and sizes.

Understand customer type distribution (B2B vs B2C).

Find top-performing shipping states and regions.

Draw business insights for improving operational efficiency and sales performance.

📂 Dataset Description

Dataset Name: Amazon Sale Report.csv
Total Records: 128,976
Final Cleaned Records: 37,514
Columns: 21 → reduced to 19 after removing unnecessary features

Key Columns:
Column	Description
Order ID	Unique identifier for each order
Date	Date of order placement
Status	Current order status (Shipped, Cancelled, etc.)
Fulfilment	Type of fulfillment (Merchant or Amazon)
Sales Channel	Platform through which the sale occurred
ship-service-level	Shipping priority (Standard, Expedited, etc.)
Category	Product category
Size	Size of the product
Courier Status	Current delivery status
Qty	Quantity ordered
Amount	Total value of the order
ship-city, ship-state, ship-country	Shipping location details
B2B	Indicates whether the order is Business-to-Business or Retail
fulfilled-by	Who fulfilled the order (Amazon or Merchant)
🧹 Data Cleaning & Preprocessing

Steps performed:

Loaded dataset using Pandas.

Removed empty and irrelevant columns (New, PendingS).

Checked for missing values and dropped records with missing critical data.

Converted data types for consistency (e.g., postal code to integer, date to datetime).

Renamed columns for better readability.

Final dataset shape: 37,514 rows × 19 columns.

🔍 Exploratory Data Analysis (EDA)

Performed data visualization and trend analysis using:

Matplotlib and Seaborn for graphical exploration.

Count plots, bar charts, pie charts, histograms, and scatter plots for visual insights.

📈 Key Insights:

Size Analysis:

Most purchased size: M, followed by L.

Indicates M-size T-shirts are in high demand.

Category Analysis:

T-shirts were the most purchased product category.

Fulfillment and Status:

Most orders were fulfilled by Amazon and successfully shipped.

Customer Type:

99.2% Retail customers, only 0.8% B2B buyers.

Geographical Insights:

Highest sales volume from Maharashtra, followed by other major states.

Courier Performance:

Most shipments are in “Shipped” status, indicating efficient dispatch but some pending/cancelled cases exist.

🧠 Business Insights

The business enjoys a strong retail customer base, dominated by individual buyers.

T-shirts and M-size apparel are top-performing products, suggesting an opportunity to expand inventory in these segments.

Maharashtra shows the highest engagement, indicating strong demand potential in western India.

The company relies heavily on Amazon Fulfillment, ensuring faster delivery and customer trust.

🧰 Tools & Technologies Used
Tool / Library	Purpose
Python	Programming language for analysis
Pandas	Data manipulation and preprocessing
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Statistical and aesthetic visualization
Jupyter Notebook	Code development and documentation
📊 Visualizations

Count Plots: To visualize product size and courier status distributions.

Bar Charts: To identify top-selling sizes and categories.

Pie Charts: To represent customer type ratio (Retail vs B2B).

Scatter Plots: To analyze category-wise size distribution.

State-wise Sales Plot: To observe regional demand variation.

💡 Conclusion

The analysis revealed:

Strong customer base in Maharashtra, mostly retail buyers.

M-size T-shirts dominate the sales.

Amazon Fulfillment ensures the majority of deliveries.

Business can increase revenue by expanding stock in high-demand categories and focusing on top-performing states.
