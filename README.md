# E-Commerce Revenue & Churn Analysis
**Customer Segmentation & Retention Intelligence — UCI Online Retail Dataset**

---

## The Business Question
Which customers are quietly leaving and what is it costing?

## Key Findings
- **58.1% of customers** have not purchased in 64+ days, representing
  **£3,783,910 — 25.7% of all lifetime revenue**
- **25.4% of customers (Champions)** generate **68.1% of all revenue**
- **21.1% of products** drive **80% of total revenue** — the 80/20 rule
  proven in this specific dataset

## What's in This Repo

| File | Description |
|---|---|
| `rfm_churn_analysis.ipynb` | Full analysis notebook — cleaning, RFM scoring, segmentation, charts |
| `insight_brief.html` | Executive insight brief — findings and recommendations |
| `index.html` | Portfolio showcase page |
| `chart1_segment_distribution.png` | RFM segment customer breakdown |
| `chart2_revenue_at_risk.png` | Financial cost of churn by status |
| `chart3_repeat_purchase.png` | Purchase frequency loyalty curve |
| `chart4_pareto.png` | Product revenue concentration (Pareto) |
| `chart5_recency_distribution.png` | Customer lifecycle by segment |

## Methodology
- **RFM Segmentation** — Recency, Frequency, Monetary scoring on a 1–5 quintile scale
- **Churn Definition** — Data-derived threshold of 64 days (2× median inter-purchase interval)
- **Pareto Analysis** — Product revenue concentration
- **Tools** — Python, pandas, matplotlib, seaborn

## Dataset
UCI Online Retail Dataset Version 2 — available on
[Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)

---
*Analyst: Otokini Soberekon · Revenue & Sales Analytics · SaaS & E-Commerce*
