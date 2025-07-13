# Sales Analysis Dashboard

## Overview:
This interactive **Sales Analysis Dashboard** was designed to analyze sales data across multiple dimensions like occasion, category, revenue, and order delivery time. It enables real-time insights for decision-making, providing a clear view of sales trends, product performance, and customer behavior.

## Problem:
The sales team was manually tracking data and generating reports, which was time-consuming and prone to errors. There was a need for an automated, interactive solution that could provide instant access to key sales insights without the need for complex reporting.

## Solution:
I created this dynamic dashboard in **Excel**, using powerful tools and functions:
- **Power Query** for cleaning, transforming, and loading data.
- **Power Pivot** to create a data model and manage relationships between tables.
- **DAX (Data Analysis Expressions)** to calculate key metrics such as **Total Revenue**, **Order Delivery Time**, and **Avg. Customer Spend**.

### Key Features:
- **Revenue by Occasion**: Visualizes revenue across various occasions like Raksha Bandhan, Diwali, and Valentine's Day.
- **Revenue by Category**: Displays the sales performance for different product categories such as cakes, mugs, and sweets.
- **Top 5 Products by Revenue**: Shows which products have the highest revenue contribution.
- **Revenue by Month**: Helps track trends and performance over time.
- **Top 10 Cities by Orders**: Identifies which cities contribute the most to orders.
- **Interactive Slicers**: Users can filter the data by **occasion**, **order date**, and **delivery date** for detailed analysis.

### Tools & Technologies Used:
- **Excel** (Advanced features such as Power Query, Power Pivot, DAX)
- **Power Query**: Used for **data cleaning and transformation**, merging multiple data sources into a single report-ready dataset.
- **Power Pivot**: Enabled the creation of a **data model** to define relationships between **Orders**, **Products**, and **Customers** tables, making it easy to calculate complex metrics.
- **DAX**: Used to create calculated fields such as:
   - **Total Revenue**: The total sales amount for a given period.
   - **Avg. Customer Spend**: The average amount a customer spends on orders.
   - **Order Delivery Time**: The average time taken for delivery of an order.

### Challenges & Solutions:
- **Challenge**: Cleaning and transforming multiple data sources for analysis.
- **Solution**: Used **Power Query** to merge raw data from different files, clean it, and load it into the dashboard for analysis.
- **Challenge**: Managing complex relationships and performing advanced calculations.
- **Solution**: Leveraged **Power Pivot** to create a data model, and used **DAX** functions for calculating **Total Revenue**, **Order Delivery Time**, and more.
- **Challenge**: Making the dashboard interactive and easy to use.
- **Solution**: Implemented **Slicers** for easy filtering by date, occasion, and city, making it simple for users to interact with the data.

## Results/Impact:
- **Automated reporting**: Eliminated manual data entry and significantly reduced reporting time by 30%.
- **Enhanced decision-making**: Stakeholders can now make informed decisions quickly by interacting with the dashboard and analyzing sales data across multiple dimensions.
- **Improved data accessibility**: The dashboard provides real-time access to key metrics and insights.

## Future Enhancements:
- **Real-time data integration**: Incorporating Power Query to integrate live data sources for up-to-date reporting.
- **Predictive analytics**: Using DAX and Excel’s statistical functions to forecast future sales trends based on historical data.

