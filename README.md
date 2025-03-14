# BlinkIt Analysis

This project presents a comprehensive Power BI dashboard for analyzing Blinkit's sales performance, customer satisfaction, and inventory distribution.
### Dashboard Link : https://1drv.ms/u/c/9daa1ce0b232a7e2/EYE6N-Zv1pZMkq0DYSwTcigB_is4sMe48jTtADcInLCtTA?e=wPe9wh


## Overview
The dashboard provides key insights and opportunities for optimization using various KPIs and visualizations. It is designed to help stakeholders make informed, data-driven decisions.

## Key Features
1. Total Sales: Displays the overall revenue generated from all items sold.

2. Average Sales: Shows the average revenue per sale.

3. Number of Items: Highlights the total count of different items sold.

4. Average Rating: Provides the average customer rating for items sold.

5. Sales by Fat Content: Breaks down sales into low-fat and regular-fat categories.

6. Item Type Distribution: Displays sales distribution across various product categories.

7. Outlet Size and Location Analysis: Offers insights on sales performance by outlet size and location tier.

8. Outlet Type Comparison: Compares different outlet types based on sales, number of items, average sales, ratings, and item visibility.

## Visualizations
* Pie Chart: Sales by Fat Content

* Bar Chart: Item Type Distribution

* Donut Chart: Sales by Outlet Size

* Funnel Map: Sales by Outlet Location (Note: This might require a different visualization tool or customization)

* Matrix Card: All Metrics by Outlet Type

![Dashboard Screenshots]![Screenshot 2025-03-14 224631](https://github.com/user-attachments/assets/0a1f1b39-598b-4527-a80b-dc4fb09dc1ec)





## How to Use?
Install Power BI: Ensure you have Power BI installed on your system.

Download the Dashboard: Clone or download this repository.

Import Data: Connect your data sources to Power BI.

Interact with the Dashboard: Use the interactive filters to explore different aspects of Blinkit's sales performance.

Contributing
Contributions are welcome! Feel free to submit pull requests or issues.

* License
[Insert License Here]

Additional Tips for Including Pictures
Replace insert_image_here.png with the actual path to your screenshot.

Ensure the image is in the same directory as your README file or provide a relative path.

Use Markdown syntax to include images, as shown above.

Example Code for Data Visualization (Power BI)
While Power BI primarily uses a GUI for creating visualizations, you can use DAX expressions to create measures. Here's an example of how to create basic measures in Power BI:

// Total Sales
Total Sales = SUM(Sales[Amount])

// Average Sales
Average Sales = AVERAGE(Sales[Amount])

// Number of Items
Number of Items = COUNT(Sales[ItemID])

// Average Rating
Average Rating = AVERAGE(Sales[Rating])



