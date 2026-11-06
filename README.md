# Airbnb Tableau Project

A Tableau-based business intelligence project focused on analyzing Airbnb listing performance, pricing patterns, and revenue trends. This repository contains the Tableau workbook, the source dataset, and a dashboard snapshot that summarize key insights across the Airbnb market.

## Overview

The project explores how listing characteristics such as bedroom count, ZIP code, and property attributes influence pricing and revenue. By combining listing-level data with temporal and review data, the dashboard provides a clear view of market behavior and supports data-driven decision-making for pricing and performance analysis.

The workbook includes 5 core visualizations designed to answer practical questions such as:

1. How many listings are available by bedroom count?
2. How does average price change by number of bedrooms?
3. Which ZIP codes command the highest average prices?
4. What is the relationship between location and price per ZIP code?
5. How has revenue evolved over time?

The dataset contains 3 primary source tables and 1,000+ listing records, allowing for a detailed market-level assessment across multiple dimensions.

## Repository Contents

| File | Description |
| --- | --- |
| `AirBnB Full Project.twb` | Tableau workbook containing the data model, calculated fields, worksheets, and dashboard layout. |
| `Tableau Full Project.xlsx` | Source dataset used by the workbook, including Airbnb listing, review, and calendar information. |
| `Dashboard 1.png` | Static preview of the final dashboard for quick review without opening Tableau. |
| `README.md` | Project documentation and usage notes. |

## Data Sources

The workbook is built from 3 main tables in the Excel dataset, including:

1. `Listings` — listing attributes, host information, property details, location, and pricing fields
2. `Reviews` — review-related data connected to listing IDs
3. `Calendar` — time-series booking and availability information

These tables are joined in Tableau to create a unified analytical dataset for trend and pricing analysis. The workbook uses a total of 5 dashboard views to compare market patterns across bedroom count, ZIP code, and annual revenue performance.

## Dashboard Insights

The dashboard includes 5 core views that provide a high-level understanding of the Airbnb market:

1. Distinct Count of Bedroom Listing
2. Price By Bedroom
3. Price By ZipCode
4. Price Per ZipCode
5. Revenue Per Year

These visualizations help highlight how listing configuration and geography influence pricing, while also revealing patterns in annual revenue performance. The dashboard structure is designed to support a 5-part comparative analysis of listing volume, pricing, geographic variation, and financial performance.

## Project Objectives

This project was designed to:

1. Analyze listing distribution across property size and bedroom count.
2. Evaluate pricing differences by bedroom configuration and location.
3. Identify ZIP-code-based pricing trends.
4. Assess revenue performance over time.
5. Present business insights in a readable Tableau dashboard format.

## How to Use

1. Open `AirBnB Full Project.twb` in Tableau Desktop.
2. If the workbook prompts for a data source refresh, reconnect it to `Tableau Full Project.xlsx`.
3. Review the worksheets and dashboard to explore the underlying analysis.
4. Use `Dashboard 1.png` for a quick visual reference without launching Tableau.

## Notes

- The workbook references the original local Excel file path from the authoring environment, so a refresh may be required if files are moved or opened on another machine.
- This project is a static Tableau analysis repository and does not include a traditional application codebase or deployment pipeline.

## Summary

This project demonstrates practical Tableau analytics for a real-world hospitality dataset, combining descriptive and comparative visualizations to uncover price and revenue patterns in the Airbnb market. It is suitable for portfolio presentation, business reporting, and data storytelling.

## Dashboard
<img width="1000" height="800" alt="Dashboard 1" src="https://github.com/user-attachments/assets/6df014cc-6906-4e0e-9ebe-de81215b7289" />
