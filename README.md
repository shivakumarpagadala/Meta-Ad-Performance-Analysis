# Meta Ad Performance Analysis – Power BI Dashboard

A complete analytics project designed to evaluate the performance of Meta (Facebook & Instagram) ad campaigns, focusing on impressions, clicks, engagement, purchases, audience behavior, and ROI metrics.
This dashboard provides a clear funnel view — from awareness → engagement → conversions — along with demographic, geographic, and time-based insights.

# Project Overview

This project analyzes how users interact with Meta ads using event-level data, campaign metadata, ad formats, and user demographics.
According to the domain knowledge document (page 1–2), the dataset captures:

Impressions

Clicks

Purchases

CTR, CPC, CPM, ROAS

Audience attributes (age, gender, country, interests)

## Objectives

Track awareness, engagement, and conversions

Measure ad efficiency using CTR, CPC, CPM, ROAS

Identify audience segments with high performance

Compare ad platforms & ad formats

Understand time-based behavior (hourly, daily, weekly)

Provide clear insights to improve ad strategy

## Components of the Dashboard
1️⃣ Funnel Analytics (Top → Middle → Bottom)

- Using impressions, clicks, engagements, and purchases:

- 216K impressions → 25.4K clicks → 1.3K purchases

- CTR = 11.76%, Engagement Rate = 13.56%

- Conversion rate from clicks = 5.21%

## Insight:
### Strong awareness & engagement, but significant drop in purchase efficiency, indicating landing page or targeting issues.

2️⃣ Audience Insights (Demographics & Interests)

- As noted in the project explanation:

- Females (43%) engage more than males (22%)

- Most active users are 18–30 years old

- India & Brazil generate high engagement

- Germany & UK represent high-value audiences


### Targeting should be refined — focus on young female audience and high-value regions separately.

3️⃣ Time & Seasonality Analysis

- Based on hourly & weekly breakdowns:

- Engagement peaks in afternoon & evening

- Specific dates (19–21, 25–27) show performance spikes (likely due to offers/events)

### Schedule ads during peak engagement windows for better ROI.

4️⃣ Ad Type & Platform Performance

- Video ads have the highest CTR and conversion rate

- Stories ads also perform very well

- Images & carousels show lower conversion efficiency

- Shift budget toward video + story ads.

 ## Data Model (Star Schema)

Fact Table

ad_events — impressions, clicks, comments, purchases (event-level interaction)

Dimension Tables

ads — ad type, platform, targeting

campaigns — budget, duration

users — demographics, interests

This schema enables efficient DAX modeling and KPI calculations.

## Tools & Technologies

Power BI

DAX Measures

Data Modeling

Advanced Visuals

Power Query (ETL – cleaning & transformations)

CSV/Excel Data Source

Analytical Skills

Funnel Analysis

Audience Segmentation

ROI Calculation

Trend & Seasonality Analysis

## Key Insights & Recommendations

1. Awareness & Engagement → Strong

CTR and engagement rate are above industry averages.

2. Purchase Conversion → Weak

Leak in funnel → optimize landing pages, offers, retargeting campaigns.

3. Top Audience

Young females (18–30) → highest engagement.

4. Best Performing Ad Formats

Video & Story ads → highest conversion & ROAS.

5. Budget Optimization

Shift budget from low-ROI formats to top-performing segments.

6. Time Optimization

Schedule ads in afternoon & evening for maximum performance.
