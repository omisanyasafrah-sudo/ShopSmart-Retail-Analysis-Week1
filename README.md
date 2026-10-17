# ShopSmart Retail Analysis: Week 1 (Data Analytics Track)

Name: Safrah Adebola Omisanya
Programme: AnalystLab Africa Experience Lab
Mission: 01, Retail Sales Analysis with Microsoft Excel

## Files
the ShopSmart_Analysis.xlsx is available on request
- ShopSmart_Analysis.xlsx: cleaned data tables, KPI sheet, lookups, pivots, charts, dashboard, business answers
- Executive_Dashboard.pdf: dashboard export
- Business_Report.pdf: one-page report

## Workbook guide
- Cleaning_Log: every cleaning check and result
- KPI: the ten required KPIs plus order status counts, return rate and inventory value
- Orders: added Revenue, lookup columns (customer, store, product, category, brand) and helper columns
- Pivot_* sheets: all required pivots
- Dashboard: KPI cards, five charts and six slicers
- Business_Questions: answers to Part 8
- Data_Understanding: tables, keys and relationships (Part 1)

## Key assumptions
- Revenue = Quantity x Unit_Price - Discount, Completed orders only; shipping excluded
- Discount is a flat amount (verified against Line_Total)
- Profit = Completed revenue - (Quantity x Cost_Price)
- Return rate = distinct returned orders / all orders (4.88%)
- Inventory value = Stock_On_Hand x Cost_Price
- Membership Level = Customer_Segment; State = store state
- Currency is not stated in the data

## Headline results
- Completed revenue 2,496,824,383 from 16,529 of 50,000 orders
- Top category: Beauty. Top region: South. Peak month: December
- Return rate 4.88%; 21 inventory records below reorder level

## Limitations
- No supplier link to products, so supplier analysis was not possible
- Returns recorded against Pending and Cancelled orders