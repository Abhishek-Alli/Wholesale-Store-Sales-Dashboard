
# Wholesale Store Sales Dashboard

## Description
This project involves a dynamic sales dashboard for a wholesale store, offering insights into sales performance, customer segmentation, and operational efficiency.
(https://github.com/Abhishek-Alli/Wholesale-Store-Sales-Dashboard/blob/main/wholesale%20dashboard%20analysis%20screenshot.png)

(https://github.com/Abhishek-Alli/Wholesale-Store-Sales-Dashboard/blob/main/forecast%20next%2015%20days%20sales%20with%20power%20bi%20.png)
## Tools and Technologies Used
- Power BI, DAX (Data Analysis Expressions), SQL (if data preprocessing is required)

## Types of Analysis
- - Sales Trend Analysis
- Customer Segmentation
- Profitability Metrics
- Product Performance Insights
- Geographical Sales Distribution

## Steps to Create the Dashboard
1. 1. Import and clean the dataset.
2. Build relationships between tables (if applicable).
3. Create calculated columns and measures using DAX.
4. Design interactive visuals such as charts, tables, and slicers.
5. Publish the dashboard for user interaction.

## DAX Queries Used
```DAX
Total Sales = SUM(Sales[Sales Amount])
Profit Margin = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Sales Amount]))
Top Products = TOPN(10, Products, [Total Sales], DESC)
```

## How to Use
1. Open the `.pbix` file in Power BI Desktop.
2. Review the DAX queries in the model view or measure pane.
3. Interact with the visuals on the dashboard to explore insights.

