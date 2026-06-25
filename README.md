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

# Work Completed

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


## Task 4 – Use Appropriate Chart Types

The aim of this task was to use chart types that best represent the business questions and make the dashboard easy to understand.

## Work Done

- Used a line chart to show the sales trend over time.
- Used horizontal bar charts to compare regional performance, category profitability, customer segments, shipping performance, and return analysis.
- Used a scatter plot to study the relationship between discount and profit.
- Chose each chart based on the type of information being presented so that the insights are clear and meaningful.

## Conclusion

All visualizations use suitable chart types according to the business requirement. The charts help compare values, identify trends, and understand relationships within the data.


# Executive Sales Dashboard

## Task 5: Interactive Dashboard

An Executive Sales Dashboard was created in Tableau by combining multiple worksheets into a single interactive dashboard. The dashboard includes KPI cards for Total Sales, Total Profit, and Average Delivery Days, along with visualizations for Sales Trend, Regional Performance, Customer Segment, Shipping Performance, and Return Analysis. Interactive filters for Region, Category, and Customer Segment were added so that all charts update dynamically.


## Task 6: Visualization Design Principles

The dashboard follows visualization best practices:
- Appropriate chart selection for each business question.
- Clear visual hierarchy with KPI cards placed at the top.
- Minimal visual clutter.
- Consistent color usage across charts.
- Clear titles and labels.
- Sorted charts for easier comparison.
- Interactive filters for better analysis.
- Accurate scales without misleading visuals.
- Dashboard designed for business decision-making.


## Task 7: Required Screenshots

The following screenshots were captured and included:
- Full Executive Dashboard
- Sales Trend View
- Regional Performance View
- Category Profitability View
- Filter Interaction View

All screenshots are stored in the `screenshots` folder.


## Task 8: Business Insights

Business insights were documented in `outputs/business_insights.md`.

The insights cover:
- Sales trend
- Regional performance
- Category profitability
- Customer segment behavior
- Discount impact
- Shipping performance
- Return pattern
- Business risks and opportunities

Each insight includes:
- Observation
- Data evidence
- Business interpretation
- Recommended action


## Task 9: Dashboard Story

A leadership-focused dashboard story was created in `outputs/dashboard_story.md`.

The story includes:
- Executive summary
- Business strengths
- Underperforming areas
- Risks
- Opportunities
- Recommended business actions
- Dashboard limitations
- Suggested future analysis


## Task 10: Chart Selection Justification

Chart selection justification was documented in `outputs/chart_selection_justification.md`.

For each major chart, the document explains:
- The business question answered
- Why the chart type was selected
- Fields used for color, labels, and filters
- Design principles applied
- Common visualization mistakes avoided
