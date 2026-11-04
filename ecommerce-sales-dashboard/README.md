# E-commerce Sales Dashboard

![Dashboard](dashboard.png)

## Overview
Interactive Power BI dashboard analyzing e-commerce sales across Saudi cities, categories, and payment methods (Jan 2024 - Jun 2025).

> Note: the dataset is synthetic, generated for practice.

## Tools
Power BI, Power Query, DAX, Excel

## Data Model
Star schema: Orders (fact), Customers, Products, and a Calendar table.

## Data Cleaning (Power Query)
- Standardized inconsistent city names
- Replaced missing payment methods with "Unknown"
- Removed 12 duplicate orders
- Set correct data types for all columns

## Key Measures (DAX)
Total Revenue, Total Profit, Orders Count, Return Rate %

## Key Insights
- **Total revenue is about SAR 948K with a 37.9% profit margin** across 3,100 orders (average order value of roughly SAR 306).
- **Sales spike during seasonal periods.** Monthly revenue reaches about SAR 90K in March 2024, November 2024 (White Friday), and March 2025, roughly double the typical SAR 35-50K month.
- **Fashion and Electronics generate about half of revenue** (SAR 259K and SAR 221K), while Sports is the weakest category at about SAR 45K.
- **Riyadh and Jeddah contribute nearly 49% of revenue**, with Dammam a distant third. This suggests an opportunity to grow in other cities.
- **Return rate is 6.6%**, and Mada is the most-used payment method (about 30% of orders).

## Recommendations
- Concentrate inventory and discounts ahead of Ramadan and White Friday.
- Invest in the two leading categories, and review pricing or marketing for Sports.
- Run targeted campaigns in cities outside Riyadh and Jeddah.
