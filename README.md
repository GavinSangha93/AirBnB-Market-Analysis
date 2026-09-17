# Airbnb Market Analysis

A Tableau dashboard that explores Airbnb listing prices, property size, geographic patterns, inventory, and calendar-based pricing trends.

## Business Question

How do location and bedroom count relate to advertised listing prices, and how can hosts or analysts use the available data to compare market segments?

## What I Built

- Connected listing and calendar data in Tableau.
- Compared average advertised prices across zip codes.
- Mapped geographic price patterns.
- Analyzed average price by bedroom count.
- Compared the number of listings across bedroom categories.
- Visualized calendar-based pricing totals over time.
- Combined the views into a single dashboard.

## Dashboard Preview

![Airbnb market analysis dashboard](https://imgur.com/ZdAYLBq.png)

## Key Findings

- Advertised prices vary across zip codes.
- Listings with more bedrooms generally have higher average prices.
- Listing inventory is concentrated in certain bedroom categories.
- Calendar-based pricing totals vary over time.

These results are descriptive. Listing price is not the same as booked revenue, profit, occupancy, or investment return.

## Dashboard Walkthrough

### Average Price by Zip Code

![Bar chart showing average Airbnb price by zip code](https://imgur.com/HQucnzD.png)

This comparison highlights geographic differences in advertised nightly prices.

### Geographic Price Map

![Map showing Airbnb price patterns by zip code](https://imgur.com/QnFTYAQ.png)

The map provides spatial context for the same pricing differences.

### Calendar Pricing Trend

![Time-series chart showing calendar-based pricing totals](https://imgur.com/xlUxeKL.png)

This view tracks the sum of available calendar price records over time. It should be treated as a pricing-data trend—not confirmed revenue—because the source does not establish that each available night was booked.

### Average Price by Bedroom Count

![Chart showing average Airbnb price by bedroom count](https://imgur.com/hJotNdn.png)

The chart compares advertised price levels across property sizes.

### Listing Inventory by Bedroom Count

![Chart showing distinct listing count by bedroom count](https://imgur.com/DaXiWux.png)

Inventory counts help show which property-size segments are more or less represented in the dataset.

## Business Use

The dashboard can support preliminary market comparison and pricing research. A host or analyst could use it to identify segments for deeper investigation before evaluating a specific property.

## Limitations and Next Steps

- Advertised price does not equal realized revenue or profitability.
- The analysis does not account for occupancy, cleaning fees, platform fees, taxes, financing, or operating costs.
- Geographic averages may hide substantial differences among neighborhoods and individual listings.
- A stronger investment analysis would add occupancy, review activity, property costs, seasonality, and comparable-listing filters.
- Historical results should be refreshed before making current market decisions.

## Tools and Skills

**Tableau · Microsoft Excel · Data Integration · Exploratory Analysis · Geographic Analysis · Dashboard Design · Data Visualization**

## Project File

- **AirBnB Full Project.twbx** — packaged Tableau workbook containing the dashboard and supporting worksheets.
