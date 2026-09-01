# Restaurant-Analysis-Dashboards
An interactive Power BI dashboard analyzing restaurant sales, orders, and customer data — built with a star-schema data model, custom DAX measures, and a 5-page report featuring dynamic slicers and cross-filtering.  

# Restaurant Sales & Operations Dashboard (Power BI)

An end-to-end Power BI project that transforms raw restaurant order data into an interactive, multi-page analytics dashboard — covering data cleaning, dimensional modeling, DAX measures, and visual reporting.

## Overview

This project takes a raw restaurant dataset through the full BI pipeline: import and inspection, cleaning and transformation in Power Query, a proper star-schema data model, calculated columns and DAX measures, and a five-page interactive report with slicers and cross-filtering.

## Project Workflow

- [x] Import dataset
- [x] Inspect columns
- [x] Clean and transform in Power Query
- [x] Create `RestaurantID`
- [x] Finalize Restaurants table
- [x] Create Orders table
- [x] Create Customers table
- [x] Create Date table
- [x] Build relationships
- [x] Create calculated columns
- [x] Create base measures
- [x] Create advanced measures
- [x] Build Page 1
- [x] Build Page 2
- [x] Build Page 3
- [x] Build Page 4
- [x] Build Page 5
- [x] Add slicers
- [x] Add interactions
- [x] Final formatting

*(Adjust checkboxes to reflect your actual progress before publishing.)*

<img width="959" height="493" alt="Screenshot 2026-09-01 143321" src="https://github.com/user-attachments/assets/736b08a9-eadd-45ef-b900-15af7fdcd17c" />


## Data Model

The report follows a star-schema design for efficient filtering and aggregation:

| Table | Description |
|---|---|
| **Restaurants** | Restaurant-level attributes, keyed by `RestaurantID` |
| **Orders** | Fact table of individual restaurant orders |
| **Customers** | Customer-level attributes |
| **Date** | Standard date dimension table for time intelligence |

Relationships were built between the fact table (Orders) and each dimension table to support clean one-to-many filtering.

## Report Pages

| Page | Focus |
|---|---|
| Page 1 | *(e.g., Executive Overview / KPIs)* |
| Page 2 | *(e.g., Sales Trends)* |
| Page 3 | *(e.g., Restaurant Performance)* |
| Page 4 | *(e.g., Customer Insights)* |
| Page 5 | *(e.g., Operational Deep Dive)* |

*(Replace with the actual titles/purpose of each page in your .pbix file.)*

## Features

- Interactive slicers for filtering by restaurant, date range, and customer segment
- Cross-filtering and drill-through interactions across pages
- Calculated columns and DAX measures for base and advanced KPIs
- Clean, consistent formatting across the report

## Tools & Technologies

- **Power BI Desktop** — data modeling, DAX, and report building
- **Power Query (M)** — data cleaning and transformation

## Getting Started

1. Clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Refresh the data source(s) if prompted.
4. Explore the report pages using the slicers on each page.

## Repository Structure

```
├── data/              # Raw and/or sample dataset
├── PowerBI/           # .pbix report file
├── screenshots/        # Report page previews
└── README.md
```

## Future Enhancements

- Automate data refresh via a scheduled gateway
- Add row-level security for multi-restaurant access
- Extend the model with a Menu Items / Products table

## Author

Aditya

---
*Feel free to open an issue or submit a pull request with suggestions or improvements.*
