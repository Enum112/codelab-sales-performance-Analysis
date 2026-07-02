 Sales Performance Dashboard 2023–2025 (codelab)
 
## 📌 Project Overview
This project is an interactive **Power BI sales performance dashboard** covering three years (2023–2025) of product sales across 7 product categories. It was built to practice end-to-end data analytics skills — KPI design, time-series trend analysis, segment breakdowns, and executive dashboard storytelling — turning raw sales transactions into a single-page view a business stakeholder can act on.
 
The dashboard is designed to answer:
- How is revenue, order volume, and pricing trending year over year?
- Which products and price segments (Budget / Mid-Range / Premium) are driving the most volume?
- How does unit pricing move across quarters?
**Tool used:** Microsoft Power BI Desktop
 
---
 
## 🗂️ Dataset Summary
The underlying dataset covers sales transactions from **2023 to 2025** across **7 product categories**: Chair, Desk, Laptop, Monitor, Phone, Printer, and Tablet. Each product is further segmented into three pricing tiers: **Budget, Mid-Range, and Premium**.
 
The report includes a **Year** and **Product** slicer, allowing users to filter the entire dashboard by year or by one/more of the 7 product types.
 
> ⚠️ **Note:** 2025 figures appear to reflect partial-year data (well below 2023/2024 totals), so year-over-year comparisons involving 2025 should be treated as a trend indicator rather than a full annual comparison.
 
---
 
## 📊 Key Metrics (from dashboard cards, "All" years)
 
| Metric | Value |
|---|---|
| Total Revenue | **$1.3M** |
| Average Order Value (AOV) | **$1.1K** |
| Number of Products | **7** |
| Total Quantity Sold | **1.2K units** |
 
**Yearly breakdown:**
 
| Year | Units Sold | Revenue |
|---|---|---|
| 2023 | 510 | $0.55M |
| 2024 | 459 | $0.48M |
| 2025 | 231 | $0.23M |
 
**Quarterly Sum of Unit Price trend (2023–2025):** fluctuates between **$35.0K and $48.5K**, with a low point in early 2024 (~$35.0K) followed by a rebound mid-2024 (~$47.6K), then a decline heading into 2025 (~$39.1K–$43.7K).
 
**Dashboard visuals include:**
- KPI cards: Revenue, AOV, No. Product, Total Qty
- Yearly Product (units sold by year — bar chart)
- Sum of UnitPrice by Year and Quarter (line chart)
- Count of Product by Segment: Budget / Mid-Range / Premium (grouped bar chart)
- Yearly Revenue (bar chart)
- Slicers: Year, Product (Chair, Desk, Laptop, Monitor, Phone, Printer, Tablet)
---

<img width="479" height="274" alt="codelab" src="https://github.com/user-attachments/assets/3372ae3b-ba13-4c14-9e08-b8eba1f7c2b8" />

 
## 💡 Key Insights
 
1. **Both units sold and revenue are declining year over year** — units dropped from 510 (2023) to 459 (2024) to 231 (2025), and revenue fell from $0.55M to $0.48M to $0.23M over the same period. This warrants a check on whether 2025 is a full or partial year before treating it as a real downtrend.
2. **Mid-Range is the dominant pricing segment across every product.** Desk leads at 85 units in Mid-Range — the single highest count on the entire chart — and every product sells more in Mid-Range than in Budget or Premium.
3. **Desk shows a steep drop-off from Mid-Range to Premium** (85 → 47 units), the largest swing of any product between tiers, suggesting weaker premium demand or pricing resistance for that category specifically.
4. **Monitor is consistently the weakest performer in the Budget tier** (31 units, the lowest of all products in that segment), which may point to a pricing or positioning gap at the entry level.
5. **Unit price shows no steady upward or downward trend** — it moves in a cycle, dipping sharply in early 2024 before recovering mid-year, then softening again into 2025. This volatility suggests pricing is being actively adjusted (promotions, seasonality) rather than following a stable strategy.
---
 
## ✅ Recommendations
 
1. **Confirm whether the 2025 figures represent a full year or year-to-date.** If YTD, reframe the "decline" narrative and instead track pace-of-sales against the same YTD period in 2023/2024.
2. **Double down on the Mid-Range segment**, since it consistently drives the highest volume across all 7 products — prioritize inventory and marketing spend here.
3. **Investigate Desk's Premium underperformance** relative to its strong Mid-Range demand — consider whether the premium price point, features, or positioning needs adjustment, or whether Mid-Range Desk buyers are simply not being upsold.
4. **Review Monitor's Budget-tier pricing and positioning**, given it's the weakest entry-level performer among all products.
5. **Align pricing and promotional strategy with the quarterly unit-price cycle** observed — for example, understand what drove the Jan 2024 dip and the mid-2024 rebound so pricing actions can be planned proactively rather than reactively.
---
 
## 🛠️ Tools & Skills Demonstrated
- Power BI Desktop (data modeling, visualization, report layout)
- DAX for KPI cards and time-intelligence measures (yearly/quarterly aggregation)
- Segmentation analysis (product × pricing tier)
- Trend analysis and executive dashboard storytelling
