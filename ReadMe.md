# RFM Customer Segmentation Analysis 🛍️

## Overview
End-to-end customer segmentation analysis using the RFM model (Recency, Frequency, Monetary)
applied to 12 months of real e-commerce transactional data (541K+ transactions, 4,338 customers).
The goal was to identify actionable customer segments to optimize marketing spend and retention strategy.

**Tools:** Python · Pandas · Matplotlib · Seaborn · Excel

---

## What is RFM?
RFM is a proven marketing framework that scores each customer across three dimensions:
- **Recency** — How recently did they purchase?
- **Frequency** — How often do they purchase?
- **Monetary** — How much have they spent in total?

Each customer receives a score from 1–5 per dimension, enabling precise segmentation.

---

## Key Findings

### 👑 Champions Drive Almost Everything

| Segment | Customers | Revenue | Avg Ticket |
|---------|-----------|---------|------------|
| Champions | 962 | 65.2% | $6,039 |
| Loyal Customers | 758 | 15.7% | $1,843 |
| At Risk | 454 | 8.3% | $1,635 |
| Need Attention | 1,041 | 7.0% | $603 |
| New Customers | 319 | 1.6% | $458 |
| Lost | 556 | 1.4% | $227 |
| Promising | 248 | 0.7% | $253 |

962 customers (22% of the base) generate 65% of all revenue. Losing even a fraction of Champions would critically damage the business.

### 🚨 At Risk: The Urgent Priority
454 high-value customers (avg ticket $1,635) haven't purchased in ~142 days.
These were once strong buyers — a targeted win-back campaign could recover significant revenue before they move to the Lost segment permanently.

### ⚠️ Need Attention: The Hidden Opportunity
The largest segment (1,041 customers) but only 7% of revenue.
They bought before but engagement is fading (118 days avg recency, only 1.7 orders avg).
Low-cost reactivation campaigns (email, discount) could unlock meaningful upside.

### 📉 Lost Segment: Triage Decision
556 customers averaging 280 days inactive with low spend history.
Cost of reactivation likely exceeds return — recommend deprioritizing vs At Risk.

---

## Business Recommendations

1. **Protect Champions** — loyalty program, exclusive perks, early access to new products
2. **Win back At Risk immediately** — personalized email campaign within 30 days
3. **Reactivate Need Attention** — low-cost email sequence with soft incentive
4. **Nurture New Customers** — onboarding sequence to convert them into Loyal Customers
5. **Deprioritize Lost** — minimal spend, broad reactivation only if budget allows

---

## Project Structure

    rfm_customer_segmentation/
    │
    ├── rfm_analysis.ipynb       # Full analysis notebook
    ├── rfm_results.xlsx         # RFM scores and segment summary
    ├── rfm_dashboard.png        # Customer segmentation visualizations
    └── README.md

Data used: https://www.kaggle.com/datasets/carrie1/ecommerce-data 
In case you can't see the ioynb file, 📓 [View Full Notebook](https://francogarrido100.github.io/RFM-Customer-Segmentation/rfm_analysis.html)
---

## Author
Franco Garrido · [GitHub](https://github.com/francogarrido100) · [Upwork](https://www.upwork.com/freelancers/~01464eeecfaee2a8a5)
