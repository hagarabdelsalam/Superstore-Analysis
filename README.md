# Superstore-Analysis

Overview
This project, A Deep Dive into Superstore Sales, Profit, and Customer Behavior, analyzes the performance of Superstore, a retail supermarket chain offering groceries, household items, electronics, and personal care products. The analysis focuses on sales trends, product performance, customer behavior, and profitability to provide actionable insights for business optimization.

Prepared by: Hagar Abdelsalam

Contact: hagarabdelsalam64@gmail.com

Objectives
The project aims to answer the following key questions:
What is the overall sales trend?
Which are the top 10 products by sales?
Which are the most selling products (by quantity)?
What is the most preferred shipping mode?
Which are the most profitable categories and sub-categories?
Tools and Technologies
The analysis was conducted using the following tools:

Python: For data cleaning, exploratory data analysis (EDA), and visualization.
Libraries: pandas, matplotlib, seaborn
Power BI: For data modeling, creating key measures with DAX, and interactive visualizations.
Techniques: Star schema modeling, DAX measures (e.g., Profit Growth, Sales Growth %, AOV, Customer LTV)
Project Structure

The project is divided into two main components:
1-Python Analysis:
Data Cleaning and Audit: Checking dataset structure, missing values, and descriptive statistics.
Exploratory Data Analysis (EDA):
Sales trends (2011–2014)
Top 10 products by sales
Most selling products by quantity
Preferred shipping mode
Most profitable categories and sub-categories
Key Performance Indicators (KPIs):
Total Sales
Total Orders
Number of Unique Customers
Total Profit
Average Order Value (AOV)
Average Profit Margin
Top 5 Selling Products (by Quantity)
Sales by Region
Average Shipping Time
Discount Impact

2-Power BI Analysis:
Data Modeling: Built a star schema with a central fact table (Orders) linked to dimension tables (Returns, Date).
DAX Measures: Created metrics like Profit Growth, Sales Growth %, AOV, Customer LTV, and Total Shipping Cost.
Visualizations: Interactive dashboards showing sales trends, regional performance, and customer behavior insights.

Key Findings :
Sales Trends
Overall Growth: Sales increased significantly from 2011 to 2014, with seasonal fluctuations indicating peak periods (e.g., holidays).
Volatility: Sharp rises and drops suggest promotional events or external market factors.
Top Products by Sales
Smartphones Dominate: 6 of the top 10 products are smartphones, with Apple Smart Phone, Full Size leading at $86,935.78.
Other High Performers: Copiers and executive leather armchairs also rank highly.
Most Selling Products (by Quantity)
Top Product: Staples (876 units), followed by index tabs and file carts.
Category Focus: Office supplies (filing, writing tools, fasteners) show high demand.
Shipping Preferences
Standard Class Dominates: Used in ~30,000 orders, indicating customer preference for cost-effective delivery.
Low Usage of Faster Options: Same Day and First Class are less popular, possibly due to cost or lack of urgency.
Profitability
Most Profitable Category: Technology, with Copiers ($258,567.55) and Phones ($216,717.01) leading.
Loss-Making Sub-Category: Furniture - Tables (-$64,083.39), suggesting a need for cost optimization or discontinuation.
Recommendation: Expand Technology offerings and optimize low-margin Office Supplies.
Customer Behavior
High-Profit Regions: North America and Europe (e.g., England, California).
Corporate Segment: Strong performance in key states.
Shipping Strategy: Incentivize First Class for high-value customers and reduce shipping costs in profitable regions.
Business Insights
Sales Growth: 51.54% growth offers opportunities for targeted marketing and upselling to increase AOV ($504.99).
Inventory Optimization: Reduce low-profit Furniture items and focus on high-demand Technology products like Canon imageCLASS.
Regional Strategy: Prioritize expansion in high-growth regions and balance shipping costs with profitability.

Dataset 
The dataset includes Superstore's sales, orders, and customer data, covering:
Product details (name, category, sub-category)
Sales and profit metrics
Order and shipping information
Customer and regional data
The data was audited for structure, missing values, and quality before analysis.

How to Run the Project
Python Analysis:
Install required libraries: pip install pandas matplotlib seaborn
Load the dataset (CSV or similar format) using pandas.
Run the EDA scripts to generate insights and visualizations.
Power BI Analysis:
Import the dataset into Power BI.
Set up the star schema by linking fact and dimension tables.
Use the provided DAX measures to create metrics.
Explore the interactive dashboards for visualizations.
Future Improvements
Predictive Analytics: Use machine learning to forecast sales trends and customer behavior.
Real-Time Data: Integrate live data feeds for up-to-date insights.
Customer Segmentation: Deepen analysis of customer segments to tailor marketing strategies.
Cost Analysis: Further investigate unprofitable sub-categories (e.g., Tables) for pricing or supplier adjustments.

Contact :
Email: hagarabdelsalam64@gmail.com
Phone: +201110434578
LinkedIn: www.linkedin.com/in/hagar-abd-el-salam-863a98259

Acknowledgments :
This project leverages open-source tools (pandas, matplotlib, seaborn) and Power BI for comprehensive data analysis and visualization. Special thanks to the Superstore dataset providers for enabling this analysis.
