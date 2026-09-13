# Marketing Campaign Analysis

## Business Problem
Which marketing channels and campaigns are most effective and efficient, and where should marketing spend be optimized?

## Objective
This project analyzes marketing campaign performance across different channels and campaigns using Excel and Power BI, focusing on spend, conversions, revenue, and campaign efficiency.

## Tools Used
- Microsoft Excel
- Power BI
- GitHub

## Dataset
~11,000 rows of daily campaign-level marketing data (2023–2025) including:
- Campaign date
- Campaign ID
- Marketing channel
- Impressions
- Clicks
- Leads
- Conversions
- Spend
- Revenue

## Analysis Performed

**Excel**
- Data quality checks
- Duplicate and missing-value checks
- CTR calculation
- Lead Conversion Rate
- Conversion Rate
- Cost per Conversion
- ROAS
- Channel-level analysis
- Campaign-level analysis
- Monthly performance analysis

**Power BI**
The dashboard includes:
- Total Spend, Total Revenue, Total Conversions, ROAS
- Revenue by Channel
- Spend vs Revenue by Channel
- ROAS by Channel
- Conversions by Channel
- Monthly Spend vs Revenue
- Campaign Performance
- Interactive filters for Channel, Campaign, and Date

## Key Business Questions
1. Which marketing channels generate the most revenue?
2. Which channels provide the strongest return relative to spending?
3. Which campaigns perform best?
4. Which channels may require spending optimization?
5. How does campaign performance change over time?

## Key Findings
- **Affiliate is the most efficient channel** — despite mid-range spend ($857.8K), it generated the highest revenue ($5.61M) and the best ROAS (6.54x) of any channel.
- **Paid Search is a close second on efficiency** — ROAS of 6.06x, achieved with the *fewest* impressions of any channel (49.8M), suggesting highly targeted, high-intent traffic.
- **Display drives the most reach but the weakest efficiency among top spenders** — 147M impressions (~34% of all impressions) but only 3.91x ROAS, the second-lowest of the five channels.
- **Video is the weakest performer overall** — lowest revenue ($2.09M), lowest ROAS (2.52x), and lowest conversions (3,933) despite meaningful spend ($828K).
- **Paid Social sits in the middle** — solid revenue ($4.69M) but only 4.76x ROAS, leaving room for optimization.
- **CMP0060 was the top individual campaign**, generating $417.7K in revenue at roughly 6.7x ROAS — the strongest of all 120 campaigns.
- **Clear seasonality**: both spend and revenue peak between August–October each year and dip in February.
- **2024 was the strongest year** overall ($8.76M revenue on $1.97M spend); 2025 figures are lower, consistent with a partial year of data.

**Overall performance:** 437M impressions → 7M clicks → 40K conversions, on $4.52M spend generating $21.56M in revenue (blended ROAS ≈ 4.77x).

## Recommendations
1. **Shift budget from Video toward Affiliate and Paid Search**, given the ~2.5–4x ROAS gap between them.
2. **Re-evaluate Display's role in the funnel** — its low last-click ROAS may understate its value if it's driving upper-funnel awareness that other channels convert later; consider tracking assisted conversions before cutting spend.
3. **Study CMP0060 and other top campaigns** for replicable creative, targeting, or timing patterns.
4. **Plan flight timing around the Aug–Oct seasonal peak** and consider trimming spend in the February trough.
5. **Monitor Paid Social** as the channel with the most room to close the efficiency gap relative to its revenue scale.

## Dashboard
The Power BI dashboard provides an interactive view of marketing campaign performance and allows users to filter results by channel, campaign, and date.

![Dashboard 1](screenshots/dashboard_1.png)
![Dashboard 2](screenshots/dashboard_2.png)

## Project Structure
```
Marketing Campaign Analysis/
├── README.md
├── data/          # original, unmodified source data
├── excel/         # workbook with cleaning, pivot tables, and calculated metrics
├── powerbi/       # Power BI file (.pbix)
└── screenshots/   # exported dashboard images
```
