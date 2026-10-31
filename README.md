# plp-da-a1-gikomba-stall-analysis

**Student Name:** Denise Ndirangu
**Cohort:** Data Analytics with Python - 1 Million Devs Cohort

---

## Business Problem Summary

Wanjiku operates a fresh-produce stall at Gikomba Market, maintaining handwritten daily sales records and rough stock notes. Without structured business intelligence, she faced uncertainty regarding whether her business was growing week-over-week, which days drove maximum revenue, and how to allocate working capital between fast-moving produce and high-margin inventory. This analysis examines her two-week sales trends, weekday versus weekend dynamics, and inventory thresholds to provide actionable, data-backed operational recommendations.

---

## How to Run

Click the badge below to run the notebook interactively in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deendiran/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb)

Alternatively, run locally:
```bash
jupyter notebook stall_analysis.ipynb
```

---

## Top Three Findings

1. **Steady Week-on-Week Revenue Growth:** Total stall revenue reached **KES 46,450.00** across 14 days, growing by **10.66%** from Week 1 (KES 22,050.00) to Week 2 (KES 24,400.00).
2. **Significant Surge in Weekend Sales:** Weekend sales averaged **KES 4,900.00** per day, which is **82.50% higher** than the weekday average of **KES 2,685.00** (peaking on Saturday of Week 2 at KES 5,600.00).
3. **Critical Stockout Risk in Profitable Items:** Two items have dropped to or below their reorder points: **Tomatoes** (18 kg remaining vs. 25 kg reorder level) and **Sukuma** (9 kg remaining vs. 15 kg reorder level), the latter of which has an impressive **40.00% gross profit margin**.