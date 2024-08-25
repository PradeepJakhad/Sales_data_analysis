# Sales_data_analysis

## Data Definition

The salesdata sheet contains detailed transactional data, with each row representing a single order. The key attributes of the data are:

+ Order Date: The specific date on which an order was placed.
+ Year: The year derived from the order date.
+ Month: The month derived from the order date.
+ Customer Name: The name of the customer placing the order.
+ State: The state where the customer is located.
+ Category: The broad category under which the product falls, such as Office Supplies.
+ Sub-Category: A more detailed classification within the category, such as Paper or Binders.
+ Product Name: The specific name of the product sold.
+ Sales: The revenue generated from the sale.
+ Quantity: The number of units sold.
+ Profit: The profit made from the sale, calculated as Sales minus the Cost of Goods Sold.

**This data is used as the foundation for the pivot tables and graphs in the file.**

## Pivot Tables and Graphs Documentation

### Pivot Table 1: Sales by Product Category
**Pivot Table Definition:**
+ Purpose: This pivot table summarizes total sales by product category, allowing you to see which categories contribute the most to overall sales.
+ Row Labels: The rows are categorized by the product categories such as Phones, Chairs, Storage, etc.
+ Values: The pivot table displays the sum of sales for each category.

**Corresponding Graph:**
+ Graph Type: Bar Chart (or Column Chart)
+ Description: This chart displays the total sales for each product category. Each bar represents a different category, with the height of the bar corresponding to the total sales value. The categories with the tallest bars are the ones generating the most sales.
+ Interpretation: The graph allows for a quick visual comparison of sales performance across different product categories. For example, if the "Phones" bar is the tallest, it indicates that Phones are the top-selling category.

### Pivot Table 2: Sales by State
**Pivot Table Definition:**
+ Purpose: This pivot table aggregates sales by state, helping you identify where the strongest markets are located geographically.
+ Row Labels: The rows are categorized by states such as Texas, Illinois, Pennsylvania, etc.
+ Values: The table displays the sum of sales for each state.

**Corresponding Graph:**
+ Graph Type: Map Chart or Bar Chart
+ Description: If a map chart is used, it shows the sales data geographically, with states shaded based on the total sales volume. Alternatively, a bar chart lists states along the horizontal axis with bars showing the corresponding sales. Darker shades or taller bars indicate higher sales.
+ Interpretation: This visualization makes it easy to see which states are the top performers in terms of sales. For example, if Texas is shaded darkest on the map or has the tallest bar, it indicates that Texas has the highest sales volume.

### Pivot Table 3: Profit by Product Category
**Pivot Table Definition:**
+ Purpose: This pivot table focuses on profit, showing which categories not only generate sales but also contribute the most to profitability.
+ Row Labels: The rows list product categories like Phones, Chairs, Storage, etc.
+ Values: The table displays the sum of profit for each category.

**Corresponding Graph:**
+ Graph Type: Pie Chart or Bar Chart
+ Description: If a pie chart is used, each slice represents a product category, with the size of the slice showing the proportion of total profit contributed by that category. A bar chart would show the total profit by category, similar to the sales bar chart but focused on profitability.
+ Interpretation: This graph helps identify the most profitable categories at a glance. For example, if the "Phones" slice is the largest in the pie chart, it suggests that Phones are the most profitable category.

## Summary of Analysis:
**Sales by Product Category:** This analysis identifies which product categories are driving the most revenue.

**Sales by State:** This analysis helps in understanding geographical performance, indicating strong markets.

**Profit by Product Category:** This analysis reveals which categories are the most profitable, which is crucial for strategic decision-making.

**These pivot tables and their corresponding graphs provide a comprehensive view of the sales data, making it easier to analyze performance and make informed decisions.**
