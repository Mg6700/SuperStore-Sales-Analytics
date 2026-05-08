# Super Store Sales Analysis

**Tools:** Power BI, DAX  
**Domain:** Retail Analytics | Sales Performance | Forecasting  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes Super Store retail sales data across the USA for 2019–2020, covering $1.6M in total sales across 22K orders. The dashboard segments performance by product category, customer segment, shipping mode, payment method, and geography — with year-on-year monthly trend comparisons for both sales and profit.

---

## Key Metrics

| Metric | Value |
|---|---|
| Total Sales | $1.6M |
| Total Profit | $175K |
| Total Orders | 22K |
| Average Ship Days | 4 |

---

## Dashboard Features

- **Region filter** — Central / South / East / West
- **State-Wise Sales** — Bing Maps heatmap of US sales concentration
- **Sales by Category** — Office Supplies / Technology / Furniture
- **Sales by Segment** — Consumer / Corporate / Home Office donut
- **Sales by Ship Mode** — Standard / Second / First Class / Same Day
- **Sales by Payment Mode** — COD / Online / Cards donut
- **Sales by Sub-Category** — Phones / Chairs / Binders top items
- **Monthly Profit by YoY** — 2019 vs 2020 monthly profit comparison
- **Monthly Sales by YoY** — 2019 vs 2020 monthly sales comparison

---

## Sales by Category

| Category | Sales |
|---|---|
| Office Supplies | $0.64M |
| Technology | $0.47M |
| Furniture | $0.45M |

---

## Sales by Segment

| Segment | Share |
|---|---|
| Consumer | 48% |
| Corporate | 33% |
| Home Office | 19% |

---

## Sales by Ship Mode

| Mode | Sales |
|---|---|
| Standard Class | $0.91M |
| Second Class | $0.31M |
| First Class | $0.24M |
| Same Day | $0.10M |

---

## Sales by Payment Mode

| Mode | Share |
|---|---|
| COD | 43% |
| Online | 35% |
| Cards | 22% |

---

## Top Sub-Categories

| Sub-Category | Sales |
|---|---|
| Phones | $0.20M |
| Chairs | $0.18M |
| Binders | $0.17M |

---

## Key Findings

**1. Office Supplies leads revenue (0.64M) but Technology likely leads profit margin**
Office Supplies dominates volume, but Technology products (Phones at $0.20M sub-category) typically carry higher margins — a classic retail volume vs margin trade-off.

**2. Consumer segment drives 48% of sales — nearly half of all revenue**
Individual consumers outpace both Corporate (33%) and Home Office (19%) combined — unusual for a store typically targeting business buyers, suggesting strong individual product demand.

**3. COD dominates payment at 43% — digital payments lag**
Cash on Delivery being the most popular payment method suggests customer trust issues with digital payments or a customer demographic that prefers physical payment confirmation.

**4. Standard Class shipping handles 57% of all orders (0.91M of 1.6M)**
Customers overwhelmingly prefer the slowest, cheapest shipping option — indicating price sensitivity and low urgency for most purchases, with 4-day average shipping being acceptable.

**5. 2020 significantly outperformed 2019 in both sales and profit**
The YoY monthly comparison charts show 2020 lines (darker) consistently above 2019 — particularly in Q4, suggesting pandemic-driven online shopping lifted the business substantially.

**6. December is the peak month for both sales and profit across both years**
Both YoY trend lines peak in November-December — confirming strong holiday season concentration. March also shows a secondary profit spike in 2019.

---

## Technical Highlights

- Dual YoY trend lines for both Sales and Profit with monthly granularity
- Bing Maps integration for state-level geographic sales visualization
- Regional filter (Central/South/East/West) updating all visuals
- Five simultaneous segmentation charts on single dashboard
- DAX measures for YoY comparison, profit margin, and avg ship days

---

## Data Source

Super Store Sales Dataset — Kaggle.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
