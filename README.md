## Task 1: Data Inspection

### Date Fields
- Order Date
- Ship Date

### Geographic Fields
- State
- City

### Categorical Fields
- Customer Segment
- Category
- Product Name
- Region
- Ship Mode
- Campaign Channel
- Customer ID
- Order ID
- Sub Category

### Numerical Measures
- Sales
- Profit
- Discount
- Quantity
- Customer Rating
- Delivery Days

### Assumptions
- Order Date and Ship Date were correctly recognized as Date fields.
- State and City were identified as Geographic fields.
- Sales, Profit, Quantity, Discount, Customer Rating and Delivery Days are numerical measures.
- Customer and product-related columns are treated as categorical dimensions.


## Task 2: Calculated Fields

1. Profit Margin = Profit / Sales
2. Cost = Sales - Profit
3. Average Order Value = Sales / Total Orders
4. Return Rate = Returned Orders / Total Orders
5. Shipping Delay Bucket = Categorizes delivery days into Fast, Medium, and Slow.


## Task 3: Create Required Tableau Sheets

The objective of this task was to create different Tableau worksheets to understand sales data from multiple perspectives. Each sheet focuses on a different business aspect such as sales, profit, customer segments, shipping performance, discounts, and returns.

## Work Completed

### Sales Trend View
Created a line chart using Order Date and Sales to observe how sales changed over different months.

### Regional Performance View
Compared sales and profit across different regions using a horizontal bar chart to identify the best-performing region.

### Category Profitability View
Created a chart to compare profit across different categories and sub-categories to understand which products contribute more to profit.

### Customer Segment View
Compared sales and profit for different customer segments to analyze their overall performance.

### Shipping Performance View
Created a chart showing the average delivery days for each shipping mode. This helps in understanding shipping efficiency.

### Discount vs Profit View
Used a scatter plot to study the relationship between discount and profit. Different categories were highlighted using colors for better comparison.

### Return Analysis View
Created a bar chart using the calculated Return Rate field to compare product return rates across different categories.

## Conclusion

All the required Tableau worksheets were created successfully. These visualizations provide useful insights into sales performance, profitability, customer behavior, shipping efficiency, and product returns. These sheets will be used together in the dashboard created in the next task.   
