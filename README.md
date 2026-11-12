# World Wide Sales Insight Dashboard

An interactive Power BI dashboard for exploring sales and profit across countries, regions, markets, states, and cities. It also shows how orders are distributed across shipping modes.

## Dashboard overview

The report contains two pages:

### Page 1: Worldwide sales overview

- **Sales by Country** — A map showing sales geographically, with sales represented by marker size.
- **Sales by Region** — A bar chart comparing total sales across regions.
- **Sales by Market** — A bar chart comparing total sales across markets.
- **Sales by City** — A bar chart comparing total sales across cities.
- **Orders by Ship Mode** — A doughnut chart showing the count of orders for each shipping mode.
- **Filters** — Country, Region, and Market-labeled slicers help narrow the report. Selections can affect the other visuals.

### Page 2: Sales and profit details

Tables summarize sales and profit by:

- City
- State
- Region
- Market

This page provides a more detailed view of the geographic breakdown behind the overview charts.

## Metrics and fields

- **Sales:** Sum of the `Sales` field
- **Profit:** Sum of the `Profit` field
- **Orders:** Count of non-empty `Order ID` values
- **Geographic fields:** Country, Region, Market, State, and City
- **Shipping field:** Ship Mode

## How to use

1. Open the `.pbix` file in Microsoft Power BI Desktop.
2. Use the slicers to filter the report by location.
3. Compare sales across the charts on the overview page.
4. Review the tables on the second page for sales and profit details.

## Tools

- Microsoft Power BI
- Interactive charts, map, slicers, and tables

## Note

The slicer labeled **Market** is currently connected to the `Region` field in the report. It may filter by region rather than market until that field binding is corrected in Power BI.

## Author

**Mohammed Ibrahim**
