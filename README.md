# Coffee_Shop_Sales_Data_Analysis (Interactive Dashboard Creation by Using PowerBI)
## Project Objective
  The objective of this project is to design an interactive Power BI dashboard for a Coffee Shop that provides business leaders with real-time insights into sales performance. The dashboard tracks key performance      indicators (KPIs) such as Total Sales, Total Orders, and Quantity Sold, while also analyzing:
  Sales trends over time
  Weekend vs Weekday sales performance
  Store-wise and product-wise sales contributions
  Peak sales hours to identify customer buying patterns
  This project demonstrates how raw transactional data can be transformed into actionable insights using Power BI, DAX, and data visualization techniques.

## Dataset Used
- <a href="https://github.com/ajith253/PowerBI_Dashboard_1/blob/main/Coffee%20Shop%20Sales.csv">Coffee Shop Sales Data</a>

## KPI’s Requirements
1. Total Sales Analysis:
Calculate the total sales for each respective month.
Determine the month-on-month increase or decrease in sales.
Calculate the difference in sales between the selected month and the previous month.

2. Total Orders Analysis:
Calculate the total number of orders for each respective month.
Determine the month-on-month increase or decrease in the number of orders.
Calculate the difference in the number of orders between the selected month and the previous month.

3. Total Quantity Sold Analysis:
Calculate the total quantity sold for each respective month.
Determine the month-on-month increase or decrease in the total quantity sold.
Calculate the difference in the total quantity sold between the selected month and the previous month.

# Charts Requirements
1. Calendar Heat Map:
Implement a calendar heat map that dynamically adjusts based on the selected month from a slicer.
Each day on the calendar will be color-coded to represent sales volume, with darker shades indicating higher sales.
Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day.

2. Sales Analysis by Weekdays and Weekends:
Segment sales data into weekdays and weekends to analyze performance variations.
Provide insights into whether sales patterns differ significantly between weekdays and weekends.

3. Sales Analysis by Store Location:
Visualize sales data by different store locations.
Include month-over-month (MoM) difference metrics based on the selected month in the slicer.
Highlight MoM sales increase or decrease for each store location to identify trends.

4. Daily Sales Analysis with Average Line:
Display daily sales for the selected month with a line chart.
Incorporate an average line on the chart to represent the average daily sales.
Highlight bars exceeding or falling below the average sales to identify exceptional sales days.

5. Sales Analysis by Product Category:
Analyze sales performance across different product categories.
Provide insights into which product categories contribute the most to overall sales.

6. Top 10 Products by Sales:
Identify and display the top 10 products based on sales volume.
Allow users to quickly visualize the best-performing products in terms of sales.

7. Sales Analysis by Days and Hours:
Utilize a heat map to visualize sales patterns by days and hours.
Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day-hour.


- Dashboard Interaction: [View Dashboard](https://github.com/ajith253/PowerBI_Dashboard_1/blob/main/PowerBi_Project.png)


## Process
- Data Ingestion & Discovery: Connected Power BI to the raw CSV sales data to assess its structure, volume, and initial quality issues.
- Data Transformation & Cleaning: Used Power Query to clean the data, create a Total Sales column (Qty * Unit Price), and build a date/time hierarchy for analysis.
- Data Modeling & DAX: Established a star schema model and authored key DAX measures (Total Revenue, Avg. Transaction Value, YTD Sales) to power the dashboard analytics.
- Interactive Visualization: Built an intuitive dashboard with slicers, KPI cards, and charts (line, bar, donut) to visualize trends, comparisons, and composition.
- Insight Generation: Analyzed the visualizations to derive actionable insights on peak hours, top-selling products, and store performance to guide business strategy.
  
## Dashboard
<img width="1228" height="745" alt="PowerBi_Project" src="https://github.com/user-attachments/assets/b553be03-634a-434b-8fef-430e8586b6e8" />

## Project Insight
- Top-Performing Store: Hell's Kitchen generates the highest total revenue.
- Best-Selling Category: Coffee is the dominant product category by sales volume, followed by Tea and Bakery items.
- Peak Business Hours: The busiest times are between 8:00 AM and 10:00 AM, indicating the morning rush.
- High-Value Product: "Sustainably Grown Organic Lg" Drinking Chocolate has the highest unit price and contributes significantly to revenue despite lower volume.

## Final Conclusion
- This Power BI project successfully transformed raw transactional data into an actionable, interactive business intelligence tool. The dashboard provides coffee shop management with a clear, data-driven view of performance across locations, products, and time.
- The insights gleaned confirm core business assumptions (coffee is king, mornings are busy) but also reveal nuanced opportunities, such as promoting premium products and optimizing afternoon offerings. The interactive nature of the report allows managers to explore these questions on the fly, moving from reactive reporting to proactive decision-making.
