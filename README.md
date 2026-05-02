# Uber Trip Analysis - Power BI Dashboard

This repository contains a comprehensive Power BI dashboard project built to analyze Uber trip data and provide actionable insights into booking trends, customer behavior, revenue generation, and operational efficiency.

---

## Project Overview

The Uber Trip Analysis dashboard is designed to help stakeholders and business users make data-driven decisions by visualizing key metrics such as:

- Total Bookings
- Total Booking Value
- Average Booking Value
- Total and Average Trip Distance
- Average Trip Time

It includes dynamic navigation across three main dashboards:
- Overview Analysis
- Time Series Analysis
- Details View

---

## Business Objectives

- Identify booking trends and revenue patterns.
- Analyze trip efficiency in terms of distance and duration.
- Understand user behavior across vehicle types, payment methods, and trip times.
- Optimize pricing models, driver availability, and location-based services.

---

## Key Features

### Dashboard 1: Overview Analysis
- KPI Cards (Bookings, Revenue, Distance, Duration)
- Dynamic Measure Selector (Total Bookings, Booking Value, Trip Distance)
- Analysis by:
  - Payment Type (Card, Cash, Wallet, etc.)
  - Trip Type (Day/Night)
  - Vehicle Type (Matrix visual)
- Top 5 Pickup and Drop-off Locations
- Most Preferred Vehicle per Location
- Conditional Formatting for quick insights

### Dashboard 2: Time Analysis
- Pickup time analysis in 10-minute intervals (Area Chart)
- Day-wise trip trends (Line Chart)
- Hourly Heatmap by Day (Matrix View)
- Dynamic Measure Control for all visuals

### Dashboard 3: Details Tab
- Drill-through functionality to view detailed trip records
- Grid table with key fields like trip ID, distance, duration, payment method, etc.
- Bookmark to toggle between full data view and filtered data

---

## Enhancements Implemented

- Dynamic Titles based on selected measures
- Tooltips with additional trip-level details
- Clear Filters Button using Reset Slicer Action
- Download Raw Data button (Power Automate ready)
- Pop-up Bookmarks for metric definitions and data source description

---

## Data Source

- Uber trip data (June 2024)
- Contains fields for trip ID, pickup/drop-off locations, distance, duration, vehicle type, payment type, timestamp, and revenue

---

## Technologies Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M Language)
- Power BI Bookmarks and Buttons
- Power Automate (for optional export functionality)

---

## How to Use

1. Clone this repository
2. Open the .pbix file in Power BI Desktop
3. Refresh the data source (if applicable)
4. Explore interactive visuals, slicers, and drill-through features

---

## License

This project is intended for educational and portfolio purposes.

---

## About the Developer

**Dasari Ramashailesh**
Analytics Engineer
Email: ramashaileshd@gmail.com
LinkedIn: https://www.linkedin.com/in/ramashaileshd

Dasari is an Analytics Engineer with over 6 years of experience building analytics datasets, SQL pipelines, and data warehouse solutions supporting operational and financial analysis. He specializes in SQL, data modeling, ETL/ELT pipelines, and Power BI dashboard development. He focuses on improving reporting performance through query optimization and data validation to deliver reliable datasets for enterprise analytics and data-driven decision making.