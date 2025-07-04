# Superstore Quaterly Sales Forecasting using Tableau

**Tableau Dashboard Link:** https://public.tableau.com/views/QuaterlySalesForecast_17422125898670/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

This README provides a comprehensive overview of the Superstore Sales Dashboard, including its purpose, the data sources used, the creation process in Tableau, and instructions on how to navigate and interact with its features.

## Dashboard Overview

The Superstore Sales Dashboard is an interactive tool designed to analyze and monitor the sales and profitability of a retail superstore. It provides a high-level view of key performance indicators (KPIs) and allows for a detailed exploration of sales trends, regional performance, and product category contributions.

The primary objectives of this dashboard are to:
* Track core metrics: **Sales**, **Profit**, **Quantity Sold**, and **Profit Ratio**.
* Analyze sales and profit trends over time and forecast future performance.
* Identify top-performing and underperforming regions, states, and cities.
* Understand sales distribution across different customer segments, product categories, and shipping modes.

---

## Data Sources

The dashboard is built using three distinct CSV files that together provide a complete picture of the store's operations.

* **`Orders.csv`**: This is the primary dataset containing all transactional information. It includes details such as:
    * Order and Customer Information (`Order ID`, `Customer Name`, `Segment`)
    * Geographical Data (`Country`, `City`, `State`, `Region`)
    * Product Details (`Product Name`, `Category`, `Sub-Category`)
    * Core Financial Metrics (`Sales`, `Profit`, `Quantity`, `Discount`)

* **`Returns.csv`**: This file contains a list of all orders that were returned by customers. It is used in conjunction with the `Orders` data to identify returned transactions.

* **`People.csv`**: This dataset maps regional managers to their respective sales regions, allowing for an analysis of performance by the responsible manager.

---

##  navigating the Dashboard

The dashboard is designed to be interactive, allowing you to filter and explore the data dynamically.

* **Main KPIs**: At the top, you'll find four key metrics that provide an immediate summary of business performance: **Sales**, **Profit**, **Quantity**, and **Profit Ratio**.

* **Time-Series and Forecast**: The "Sales and Profit by Month" chart shows historical trends. The lighter, shaded area represents the sales forecast for the upcoming months.

* **Interactive Filters**: On the right-hand side, you can use the filters to customize the data displayed across the entire dashboard:
    * **Order Date**: Use the slider to select a specific date range you wish to analyze.
    * **Region, State, City**: Select one or more geographical areas to drill down into local performance. The rest of the dashboard will automatically update to reflect your selections.

* **Tooltips for Detail**: Hover your mouse cursor over any data point on the charts (e.g., a state on the map, a bar in a chart) to reveal a tooltip with more detailed information and exact figures.
