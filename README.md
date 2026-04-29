# RavenStack SaaS Growth & Churn Analysis

**Tools:** Excel · Pivot Tables · Dashboard Design  
**Domain:** SaaS / Subscription Business  
**Dataset:** 5,000 accounts · 500 churn events · 4 supporting data tables  

---

## Overview

Analyzed growth, retention, and churn patterns for RavenStack — a fictional B2B SaaS company — across 5,000 customer accounts. The goal was to identify what's driving churn, where revenue is concentrated, and what levers the business can pull to improve retention and growth.

---

## Dataset Structure

The workbook contains 6 core data tables:

| Sheet | Description |
|---|---|
| Accounts | 500 accounts with industry, country, plan tier, and churn flag |
| Subscriptions | MRR/ARR, billing frequency, upgrade/downgrade flags |
| Churn Events | 500 churn records with reason codes and feedback text |
| Feature Usage | Feature-level usage logs per subscription |
| Support Tickets | Ticket volume, priority, resolution time, satisfaction scores |
| Analysis + Dashboard | Summary metrics, pivot tables, and visual dashboard |

---

## Key Metrics

| Metric | Value |
|---|---|
| Total MRR | $11.3M |
| Total ARR | $136M |
| Total Customers | 5,000 |
| Overall Churn Rate | 9.7% |
| ARPA | $2,268 |

---

## Key Findings

### 1. Revenue is heavily concentrated in Enterprise
Enterprise accounts contribute ~75% of total MRR despite representing only 33% of customers. This creates a concentration risk — enterprise churn has an outsized revenue impact.

### 2. Enterprise has the highest churn rate
Despite driving the most revenue, Enterprise accounts churn at ~10.6% — higher than Basic (10.5%) and Pro (8.9%). Retaining enterprise customers is the highest-leverage retention problem.

### 3. Missing features is the #1 churn driver
Of 424 categorised churn events:
- **Features** — 100 events (24%)
- **Budget** — 92 events (22%)
- **Support** — 82 events (19%)
- **Competitor** — 77 events (18%)
- **Pricing** — 73 events (17%)

Product gaps are driving more churn than pricing or competitive pressure.

### 4. Strong upgrade activity signals product-led growth
529 upgrades recorded across all tiers vs. 218 downgrades — a healthy expansion ratio. Customers are finding value and moving up, which creates a strong upsell funnel if churn can be reduced.

### 5. Organic acquisition is the top channel
Organic channels drive the highest customer volume (114 accounts), outperforming ads (98), other (103), event (96), and partner (89). This suggests strong brand visibility and inbound demand.

### 6. DevTools and FinTech are the strongest verticals
DevTools (113 accounts) and FinTech (112 accounts) are the top customer segments, indicating strong product-market fit in developer-focused and financial technology sectors.

### 7. Billing split is nearly even
Revenue is roughly split 50/50 between annual ($5.6M MRR) and monthly ($5.7M MRR) billing. The slight lean toward monthly plans suggests customers prefer flexibility — an opportunity to improve annual conversion with better incentives.

---

## Recommendations

1. **Invest in product roadmap gaps** — Feature gaps are the leading churn driver. Closing key product gaps could reduce churn by ~24%.
2. **Prioritise enterprise retention** — Given their revenue contribution, even a 2–3% reduction in enterprise churn would have significant ARR impact.
3. **Improve annual conversion** — Near-parity between monthly and annual billing suggests an opportunity to incentivise annual contracts, improving cash flow and reducing churn exposure.
4. **Leverage the upgrade funnel** — Strong upgrade activity signals that product-led growth is working. Investing in onboarding and activation for new accounts could accelerate expansion revenue.

---

## Files

| File | Description |
|---|---|
| `RavenStack_SaaS_Growth_Analysis.xlsx` | Full workbook with raw data, pivot tables, and dashboard |

---

*Analysis conducted by Deepika Narayan · [linkedin.com/in/deepika-narayan](https://linkedin.com/in/deepika-narayan)*
