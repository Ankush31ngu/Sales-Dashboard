Power BI Dashboard Project:- Sales Dashboard Report

Objective:-  The objective was to find out how many sales were made, in which product we had the highest sales, in which state we had the highest sales, how much profit was made in each state, how much average delivery days did we make monthly wise, how much sales or profit did we make?

Steps:- First clean the data and remove duplicates by power quary. 
        Create a column Average Delivery Days with DAX Quary:- Average Delivery = DATEDIFF('Orders'[Order Date],'Orders'[Ship Date],DAY)
        Then after that Started creating the dashboard.

Insights:- Sales Card, Profit Card, Count of Order Card, Count of Returned Card, Sum of Quantity Card, Count of Average Delivery Card, Sum of Discount Card, Sum of Sales by State Map Chart, Slicer by Year, Slicer by Region, Sales and Profit by year and month line Chart, Sales and Profit by Category Pie Chart, Sales and Profit by Segment Pie Chart, Sales by Product Name Bar Chart.
