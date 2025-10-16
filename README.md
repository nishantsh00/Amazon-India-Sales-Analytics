# Amazon-India-Sales-Analytics
Amazon India: A Decade of Sales Analytics
## Overview
This repository contains a comprehensive Power BI dashboard project analyzing a decade of Amazon India sales, customers, product portfolio, revenue, and operational performance using SQL-prepared datasets and interactive business visualizations.

## Features
Executive Dashboard: Total revenue, growth rate, active customers, average order value, top categories, and YoY trend indicators.
Real-time Performance: Current month performance vs targets, run-rate, customer acquisition, and performance alerts.
Strategic Overview: Brand-wise market share, competitive positioning, geographic expansion, and key health metrics.
Financial Analytics: Revenue by category, profit margin (if available), cost structure, and financial forecasts.
Growth Analytics: Customer growth, market penetration, product launches and expansion, and initiative tracking.
Category & Revenue: Trends by month/quarter/year, category-wise breakdowns, seasonal and festival sales, price optimization.
Customer Analytics: Segmentation and cohorting, customer journey analysis, Prime vs non-Prime, retention, behavioral and demographic visualizations.
Product & Brand Insights: Product ranking, brand analysis, rating and reviews, returns, and lifecycle tracking.
Operations & Logistics: Delivery performance, payment analysis, returns/cancellations, customer service, and (optionally) supply chain/vendor dashboards.
Advanced/BI Command Center: Foundations for predictive analytics, scenario planning, cross-sell/upsell, and BI command integration.

# Data Model
## Tables:
- customers
- products
- transactions
- time_dimension

Structure: Fact table (transactions) joined to dimension tables (products, customers, time_dimension).

Data Preparation: Cleaned and deduplicated using Python/Pandas and SQL.

## Getting Started
Download or clone this repository.
Open Amazon_India_Analytics.pbix in Power BI Desktop.
Explore each interactive dashboard page using slicers for year, category, geography, customer tier, and more.

## Key Visuals & Usage
Cards: Display headline KPIs for revenue and customers.
Column/Bar/Line Charts: Visualize trends, breakdowns, and growth.
MaP Visuals: Analyze city/state performance.
Pie/Donut Charts: Show distribution of brands, payment methods, Prime status.
Scatter/Bubble Plots: Show correlations for price, discount, performance.
Tables: Drill-down into segmentation and operational details.
Slicers: Interactive filtering by date, category, region, customer type, and more.

## Files
Amazon_India_Analytics.pbix – Power BI dashboard file.
AMAZON_PROJECT.ipynb – Python notebook for ETL and preprocessing.
README.md – This documentation.

## Credits/Contact
Created by Nishant Sharma
