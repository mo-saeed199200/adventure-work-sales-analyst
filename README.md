# 🚲 AdventureWorks Sales & Customer Analysis

A multi-page Power BI dashboard analyzing sales, profit, customer behavior, and product performance for **AdventureWorks Bike Shop**, covering the period **Jan 2020 – early 2022**.

---

## 🎯 Business Problem

AdventureWorks needed a unified view of sales performance, regional distribution, customer behavior, and product profitability to support inventory planning, regional strategy, and customer targeting decisions.

---

## 📁 Dataset

- **Source:** AdventureWorks (Microsoft sample dataset)
- **Period:** January 2020 – early 2022
- **Tables:** Sales Data, Returns Data, Customer Lookup, Product Lookup, Product Categories/Subcategories, Territory Lookup, Calendar Lookup

---

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, dashboard design
- **Power Query** — data cleaning and transformation
- Parameter-driven visuals (price/quantity adjustment simulation, dynamic metric selection)

---

## 📊 Dashboard Pages

1. **Dashboard Overview** — KPIs, monthly revenue trend, order category breakdown, top product table
2. **Product Overview** — gauges vs. targets, revenue/profit per year, adjustable price & quantity simulation
3. **Customer** — customer count, revenue per customer, gender/continent breakdown, customer-level table
4. **Map** — interactive world map with weekly orders, revenue, cost, profit, and return rate by country
5. **Tree** — decomposition tree drilling from Total Customer → Category → Subcategory → Product

---

## 📌 Key Insights

### 🌍 Overall Performance
- Total revenue: **$24.9M**, total profit: **$10.5M**
- Return rate: **2.17%**, total orders: **25.2K**
- Monthly revenue reached **$1,826,987**, beating the goal of $1.77M by **+3.31%**
- Monthly orders: **2.15K**, slightly below the 2.17K goal **(-0.88%)**
- Monthly returns: **167**, above the goal of 169 by **+1.18%** (fewer returns than expected)
- Revenue shows strong growth from Jan 2020, accelerating sharply from late 2021 onward

### 🛍️ Product Performance
- **Accessories** lead order volume (17.0K orders), followed by **Bikes** (13.9K) and **Clothing** (7.0K)
- **Fender Set – Mountain** is the top product by revenue ($87,040.80, 1,975 orders, 1.36% return rate)
- **Sport-100 Helmets** (Red, Blue, Black) show the highest return rates among top products (2.68%–3.33%), worth investigating for quality issues
- **Tires and Tubes** is the most ordered subcategory; **Shorts** has the highest return rate among categories

### 👥 Customer Insights
- **17.42K total customers**, averaging **$1.43K revenue per customer**
- Revenue is nearly evenly split by gender: Male 49.14% ($12.24M), Female 50.23% ($12.52M)
- By continent: **North America** leads with $9.71M (38.97%), followed by **Pacific** $7.79M (31%) and **Europe** $7.42M (29.77%)

### 🗺️ Regional Breakdown (by country)
| Country | Total Orders | Revenue | Profit | Return Rate |
|---|---|---|---|---|
| United States | 6,060 | $7.42M | $3.08M | 2.25% |
| United Kingdom | 8,700 | $7.94M | $3.36M | 2.12% |
| Canada | 3,024 | $1.77M | $757.8K | 2.18% |
| France | 2,771 | $2.90M | $1.21M | 2.10% |
| Germany | 2,294 | $2.52M | $1.05M | 2.05% |

- The **United Kingdom generates the highest revenue and profit** of any single country, despite the United States having a larger visual footprint on the map (more total customers)
- Return rates are consistently tight across all regions (2.05%–2.25%), showing stable product/fulfillment quality globally

### 🌳 Product Hierarchy (Decomposition Tree)
- **Bikes** account for 8,793 of 17,416 total customer interactions, with **Mountain Bikes** as the leading subcategory (3,950)
- Top individual product: **Mountain-200 Black, 42** (593 units)

---

## 💡 Recommendations

1. **Investigate Sport-100 Helmet return rates** (2.68%–3.33%) — significantly higher than other top products, suggesting a sizing, quality, or description mismatch issue.
2. **Prioritize UK and US markets** for marketing and inventory — they generate the highest combined revenue and profit among all five tracked countries.
3. **Leverage the Mountain Bikes subcategory** as a flagship line — it's the top-selling bike subcategory and likely a strong anchor for cross-selling accessories.
4. **Monitor the order goal gap (-0.88%)** — while revenue and profit are exceeding targets, order volume is slightly behind goal, which may signal rising average order value rather than rising demand.

---

*Built by Mohammed | Power BI Portfolio Project*
