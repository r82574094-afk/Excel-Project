# TheLook eCommerce Analytics: Cart Abandonment and Product Returns

An end-to-end Excel project (Sprint 1) on the TheLook fashion e-commerce dataset.

## Business problem
TheLook loses revenue in two places:
- **Cart abandonment:** shoppers add items to the cart and leave without buying.
- **Product returns:** customers send items back after delivery.

The goal is to find where this happens in the customer journey and what the business can do about it.

## What is in this repo
| File | Description |
| --- | --- |
| `sprint1E.xlsx` | Excel workbook with the data model, DAX measures and the 4-page dashboard |
| Data Dictionary (.docx) | Tables, fields, relationships, cleaning rules and business rules |
| Report (.docx / .pdf) | Written report: method, KPI definitions, findings and recommendations |

## Method
1. **Power Query:** 7 tables loaded as Connection Only into the Data Model; clear null-handling rules.
2. **Data model:** Calendar table, One-to-Many relationships, inventory cost linked to sales to verify profit.
3. **DAX:** revenue, net profit, return rate, retention, churn, funnel rates, stock ratios.
4. **Forecast:** Excel Forecast Sheet (ETS, 95% confidence interval) for demand and months of cover.
5. **Dashboard:** Overview, Funnel, Returns and Inventory pages with slicers, a timeline and a What-If input.

## Key findings
- Gross revenue is $9.22M; about 70% comes from the Search traffic source.
- 57.94% of cart sessions end without a purchase. It fell from 93% (2019) to 37% (2023), but it is still the biggest drop in the journey.
- 11.79% of items are returned, costing $570K in profit. The rate is almost the same in every category, so the fix is store-wide.
- Stock is about 2x the units sold, roughly 26 months of cover at forecast demand.

## Recommendations
1. Fix the cart-to-purchase step (shipping cost early, guest checkout, reminder emails).
2. Reduce returns with better product information (size guides, photos).
3. Pause new purchasing until stock falls.
4. Grow repeat customers.
5. Reduce dependence on one traffic source.

## Tools
Excel, Power Query, Power Pivot, DAX, PivotTables, Forecast Sheet.
