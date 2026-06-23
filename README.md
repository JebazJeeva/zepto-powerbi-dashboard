# 🛒 Zepto Grocery Sales — Power BI Dashboard

## 📌 Project Overview

An interactive **Power BI dashboard** analyzing Zepto's grocery sales data across outlet types, locations, item categories, and fat content — built to give business stakeholders a single-view performance snapshot with dynamic filtering.

---

## 🎯 Business Objective

Help Zepto's business team monitor and compare:
- Which **outlet types and locations** drive the most revenue?
- Which **item categories** contribute most to total sales?
- How have **outlet establishments** performed over time (2012–2022)?
- What is the split between **low fat vs regular** product sales?

---

## 🗂️ Dataset

| Detail | Info |
|---|---|
| Source | Zepto / BlinkIT Grocery Data |
| Records | 9,000+ transactions |
| Columns | 12 fields |

**Key Fields:** Item Type, Item Fat Content, Item Visibility, Item Weight, Outlet Type, Outlet Size, Outlet Location Type, Outlet Establishment Year, Sales, Rating

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard design, DAX measures, slicers
- **Microsoft Excel** — Source data

---

## 📊 Dashboard Highlights

![Zepto Grocery Sales Dashboard](Zepto_Dashboard.png)

### KPI Cards
| Metric | Value |
|---|---|
| Total Sales | **$1M** |
| Avg Sales per Item | **$141** |
| No. of Items | **9K** |
| Avg Rating | **4** |

### Key Visuals
- **Fat Content Donut** — Regular ($776K) vs Low Fat ($425K) split
- **Item Type Bar Chart** — Fruits & Vegetables and Snack Foods lead at $0.18M each
- **Outlet Establishment Line Chart** — Sales peaked in 2018 at $205K; trend from 2012–2022
- **Outlet Size Donut** — Medium outlets dominate at $508K
- **Outlet Location Bar** — Tier 3 leads at $472K, followed by Tier 2 ($393K) and Tier 1 ($336K)
- **Outlet Type Table** — Supermarket Type1 drives 79% of total sales ($788K, 5,577 items)
- **Fat by Outlet Stacked Bar** — Regular fat products outsell Low Fat across all tiers

### Interactive Filters
- Outlet Location Type (Tier 1 / 2 / 3)
- Outlet Size (Small / Medium / High)
- Item Type (16 categories)

---

## 💡 Key Insights

| # | Insight |
|---|---|
| 1 | **Supermarket Type1** accounts for **79% of total sales** — primary revenue channel |
| 2 | **Tier 3 locations** generate the highest sales despite being lower-tier cities — untapped market potential |
| 3 | **Regular fat products** outsell Low Fat 2:1 — health positioning may need rethinking |
| 4 | **Fruits & Vegetables and Snack Foods** are the top categories — stock prioritization opportunity |
| 5 | Sales **peaked in 2018** and have stabilized around $130K — growth has plateaued post-2018 |

---

## 📁 Repository Structure

```
zepto-powerbi-dashboard/
│
├── zepto_Grocery_Data.xlsx     # Raw grocery sales dataset (9K rows)
├── Zepto_BI_Project.pbix       # Power BI dashboard file
├── Zepto_Dashboard.png         # Dashboard screenshot
└── README.md                   # Project documentation (this file)
```

---

## ▶️ How to Explore

1. Download `Zepto_BI_Project.pbix`
2. Open in **Power BI Desktop** (free download at powerbi.microsoft.com)
3. Use the **Filter Panel** on the left to slice by Location Type, Outlet Size, and Item Type
4. Switch between **Total Sales / Avg Sales / No of Items / Avg Ratings** using the tab buttons

> Don't have Power BI? View the full dashboard in `Zepto_Dashboard.png`

---

## 🧠 Skills Demonstrated

- Power BI dashboard design — KPI cards, donut charts, bar charts, line charts, tables
- DAX measures for aggregated metrics (Total Sales, Avg Sales, Avg Ratings)
- Interactive slicer-based filtering for business exploration
- Data storytelling — translating raw grocery data into outlet strategy insights

---

## 👤 Author

**Jebaz Jeeva M**  
PGDM — Business Analytics & Marketing | Rajalakshmi School of Business  
[LinkedIn](https://www.linkedin.com/in/jebazjeeva/) | [GitHub](https://github.com/JebazJeeva)
