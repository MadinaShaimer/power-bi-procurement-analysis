# power-bi-procurement-analysis
Procurement analytics dashboard using Power BI

## Business Objective
The goal of this project is to analyze procurement spending and supplier performance 
to identify cost drivers, delivery risks, and opportunities for optimization

## Dataset
Synthetic procurement dataset including:
- Purchase orders
- Suppliers
- Products and categories
- Delivery and lead time metrics
- Discounts and pricing
Time period: 2024–2025

## Dashboard

### Procurement Overview
![Procurement Overview](images/Procurement_Overview.jpg)

### Supplier Performance
![Supplier Performance](images/Supplier_Performance.jpg)

### Discount Analysis
![Discount Analysis](images/Discount_Analysis.jpg)

## Key Insights

### 1. October Spend Spike
The spike in October procurement spend was driven by a significant increase in purchase volume 
in the raw materials category. This was not caused by price increases, as average unit price 
remained stable.

At the same time, the highest discounts were observed during this period, suggesting that 
the company intentionally increased procurement to take advantage of favorable pricing conditions.

---

### 2. Supplier Risk (Delta Materials Group)
Delta Materials Group accounts for only 4% of total spend but shows a high delay rate (21%) 
and long lead time (30 days), with delays reaching up to 20 days.

This indicates a high operational risk, especially since the supplier operates in the raw materials category.

---

### 3. Procurement Strategy Behavior
The combination of high discounts and increased order volume suggests a bulk purchasing strategy, 
possibly influenced by supplier-related risks and the need to ensure supply continuity.

## Recommendations
- Monitor high-risk suppliers with long lead times and high delay rates
- Avoid increasing dependency on unstable suppliers
- Use bulk purchasing strategically when discounts are favorable
- Maintain safety stock for critical raw materials to mitigate supply chain risks

## Tools Used
- Power BI (data modeling, DAX, dashboard)
- Power Query (data cleaning)
