Power BI is a data visualization tool that converts data from various sources into interactive dashboards and analysis dashboards. Business intelligence tools are software programs that help companies understand their data in a much easier and smarter way. Power BI is a tool from Microsoft that gathers data from various data sources, allowing us to process, clean, and add queries to it, and we can also make dashboards using it.

Why Power BI?
Because it supports many data sources from which we can extract our data, whether it be from Excel, CSV files, or many databases like MySQL Workbench and Oracle. It is similar to Excel and has very good visualization capabilities (such as many charts, whether it be bar plots, pie charts, or stack plots). Not only plots, but if we are working on a dataset that represents the whole world, we can just put points on the world map to represent some data.

Why Not Excel?
Excel does not have the capacity and capability to work on large sets of data. So, Power BI is used because it has the capability to load large sets of data.

Project Overview
In this project, there is a client, Madhav, who sells his product online and wants a dashboard to track sales. The dataset consists of two tables:

Orders Table: Contains columns like OrderID, Order Date, Customer Name, State, and City.
Details Table: Contains OrderID, Amount (amount of the order), Profit (with some negative values representing losses), Quantity (order quantity), Category (electronics, furniture), Sub-category (e.g., electronics games, chairs, phones from furniture), and Payment Mode (payment made by credit card, debit card, or cash on delivery).
There is a relationship between these two tables using a many-to-one relationship. The OrderID in the Orders table has many repeated IDs (many), while the OrderID in the Details table has unique values (one).

Dashboard Components
1.Text Box: Used to create the heading.
2.Monthly Profit Chart: Created to show the sum of profit calculated according to the month.
3.Stacked Bar Graph: Shows the sum of profit by sub-category, which helps identify which sub-category is giving the most profit. We can see which product is performing well, allowing us to give discounts on that product or increase its stock. Only the top five values according to profit are selected.
4.Donut Charts:
One for the sum of quantity by category (to show the count of orders and category).
Another for the sum of quantity by payment mode.
5.Cards:
Sum of amount
Count of orders
Sum of profit
Average order value (calculated as [Amount]/[Quantity], meaning the average of total orders if 10 orders have been placed for rupees 100, the average is 100/10).
6.Bar Graphs:
Sum of amount by state
Sum of amount by customer name (top 5 customers)
By creating these charts and graphs, the dashboard provides a comprehensive view of sales performance, helping Madhav track and analyze key metrics effectively.

