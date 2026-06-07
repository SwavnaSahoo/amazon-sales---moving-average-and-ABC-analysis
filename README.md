# Amazon Sales EDA — Moving Average, ABC Analysis & Supply Chain Quadrant

## Overview
End-to-end analysis of 1,465 Amazon products using Python and Excel.
Built for supply chain decision-making — identifying fast movers, quality risks, and inventory priorities.

## What's Inside
- **Moving Average Dashboard** — 7, 30, and 90-day moving averages on product ratings
- **ABC Analysis** — classifies products into A (fast), B (medium), C (slow) movers by review volume
- **Supply Chain Quadrant** — 2x2 matrix plotting categories by demand vs quality:
  - Star → protect stock
  - Niche → grow carefully
  - Risk → investigate supplier
  - Drop → reduce inventory

## Files
| File | Description |
|------|-------------|
| `notebook.ipynb` | Full Python analysis on Kaggle |
| `amazon_abc_dashboard.xlsx` | Excel dashboard with moving averages, ABC tiers and quadrant |

## Dataset
Source: [Amazon Sales Dataset by karkavelrajaj](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)

## Tools Used
- Python (pandas, matplotlib, numpy)
- Excel (AVERAGE, PERCENTRANK, moving average formulas)
- Kaggle Notebooks

## Key Findings
- Electronics and Computers & Accessories are Star categories — highest demand, solid quality
- Musical Instruments flagged as Risk — highest review volume but lowest rating (3.90)
- Office Products are Niche — excellent ratings but low volume, growth opportunity
- ABC analysis shows top 20% of products drive the majority of review volume
