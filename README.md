# 📦 E-Commerce Delivery Performance Analysis

## Overview
An end-to-end analysis of delivery operations for a global e-commerce company, covering **172,765 orders** from **January 2015 to January 2018** across multiple regions. The project identifies root causes of chronic late deliveries and quantifies their financial impact.

## Key Findings

| Metric | Value |

| Total Orders Analyzed | 172,765 |
| Late Delivery Rate | **54.71%** |
| On-Time Delivery Rate | 45.29% |
| Total Profit (profitable orders) | $7.5M |
| Profit on Delayed Orders | $2.1M |

- **Shipping mode is the #1 lever:** First Class 100% late, Second Class 79.8%, Standard Class 39.8%, Same Day 0%
- **The problem is systemic:** delay rates sit at 55–59% across all regions and customer segments
- **Payment bottlenecks:** PAYMENT_REVIEW and PENDING_PAYMENT orders show elevated delays
- **Seasonal and intra-day peaks:** Aug/Sep/Dec and late-evening orders are the worst

## Approach
1. Data cleaning and preparation
2. KPI baseline and profitability analysis
3. Bottleneck detection across six dimensions
4. Root cause deep-dive (Central Africa)
5. Time-based delay patterns
6. Strategic recommendations

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn
