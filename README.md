## Project Overview

MSD Sales Dashboard is an interactive Power BI sales analytics dashboard developed using a synthetic sales dataset.

The project demonstrates practical skills in data analysis, data modeling, DAX, interactive visualization, and business-focused reporting.

## Business Objective

The dashboard was designed to analyze sales and profitability performance across different time periods, regions, product categories, sub-categories, customer segments, and shipping modes.

The key objectives are to:

- Monitor overall sales, profit, quantity, and discount performance
- Analyze monthly sales trends
- Compare sales performance across regions
- Understand quantity distribution by product category
- Identify sub-categories contributing to sales
- Analyze profit across customer segments and categories
- Understand shipment cost by shipping mode

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Data Modeling
- Data Visualization
- Synthetic Sales Dataset

## Dashboard Preview

![MSD Sales Dashboard](https://github.com/Divakar30/MSD-Sales-Dashboard-Power-BI/blob/main/Screenshots%20/%20MSD_Sales_Dashboard.png)

## Key Metrics

- Total Sales
- Total Quantity
- Total Profit
- Average Discount %

## Dashboard Features

### Sales Analysis
- Monthly sales trend
- Regional sales comparison
- Sales by product sub-category

### Profitability Analysis
- Profit by customer segment
- Profit by product category

### Product Analysis
- Quantity distribution by category
- Sales performance across sub-categories

### Logistics Analysis
- Shipment cost by shipping mode

### Interactive Features

- Region slicer
- Category slicer
- Interactive cross-filtering
- Interactive dashboard visuals
- Consistent KPI and visual formatting

## Power BI Features Implemented

- Power Query for data transformation and preparation
- Data modeling and relationships
- DAX measures
- Interactive slicers
- Cross-filtering between visuals
- KPI cards
- Conditional formatting
- Interactive dashboard visualizations
- Time-based sales analysis
- Regional and category analysis

## Important DAX Measures

  Total Sales =
  SUM('MSD sales dataset'[Sales])

  Total Profit =
  SUM('MSD sales dataset'[Profit])

  Total Quantity =
  SUM('MSD sales dataset'[Quantity])

  Avg Discount % =
  AVERAGE('MSD sales dataset'[Discount %])

  AOV =
  DIVIDE(
      [Total Sales],
      DISTINCTCOUNT('MSD sales dataset'[Order_id]),
      0
  )

## Key Business Insights

The dashboard enables analysis of:

- Monthly changes in sales performance
- Regional differences in sales contribution
- Product categories and sub-categories contributing to overall quantity and sales
- Profit contribution across different customer segments
- Profitability differences across product categories
- Shipment cost distribution across shipping modes

## Project Highlights

- Designed an end-to-end interactive Power BI dashboard
- Created reusable DAX measures for key business metrics
- Used Power Query and Power BI data modeling concepts
- Applied consistent dashboard design and visual formatting
- Built multiple business-focused visualizations
- Used synthetic data for portfolio and learning purposes

## Dataset Fields Used

The dashboard uses a sales dataset containing fields related to:

- Order details
- Customer details
- Product details
- Category and sub-category
- Sales and profit
- Quantity and discount
- Region and location
- Customer segment
- Shipping mode
- Order date and ship date

## Project Conclusion

This project demonstrates the ability to transform sales data into an interactive business intelligence dashboard using Power BI.

It combines data preparation, data modeling, DAX calculations, visualization, and business analysis to provide a clear view of sales, profitability, product, regional, and logistics performance.

## Data Logic

The dashboard uses aggregated sales, profit, quantity, and discount measures based on the underlying sales records.

Different visuals analyze the data at different business dimensions such as month, region, category, sub-category, segment, and shipping mode.

The AOV measure calculates average order value using total sales divided by the distinct number of orders.

## Data Privacy

This project uses a synthetic dataset created for portfolio and demonstration purposes.

It does not contain real customer or organization data. The dashboard is intended only to demonstrate Power BI, DAX, data modeling, visualization, and analytical skills.
