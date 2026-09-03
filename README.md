# Product Performance & Consumer Behavior (2018–2021) 
This analysis utilizes a comprehensive Tableau suite to evaluate the health of a UK-based clothing retailer. By processing over 214,000 units sold and £7.08M in revenue, the project identifies key drivers of profitability, regional dominance, and counter-intuitive seasonal trends. Explore the dashboards  [here](https://public.tableau.com/app/profile/fridah.machani/vizzes)

## Business Problem 

An apparel retail client had four years of sales data but no structured way to answer basic business questions. They needed to move from manual tracking to a dynamic system to identify high-margin products, track regional performance, and spot seasonal sales drops. 

## Solution

I conducted multi-dimensional exploratory data analysis across four analytical lenses simultaneously;  product category, individual SKU, geography, and time.

The client got three valuable insights with immediate operational value that enabled the client to optimize inventory rotation and front-load marketing spend for high-margin "hero" products. 
1. Demand dropped by up to 78% in certain product categories (Bras & Tops) between peak and trough months, directly informing how much stock to hold and when.
2. Profit varied by £0.72M across the top five regions with Buckinghamshire leading in profits (generating £0.86M) and Lothian emerging as the most efficiency market (at a 56.3% margin) that may offer better ROI, revealing where marketing spend should be allocated.
3. Frankie Sweatshirts is the client's anchor product that maintained consistent growth and stable margins from 2018 through 2021 despite broader market fluctuations, providing a safe inventory investment that offer a reliable floor for revenue to protect the business against the volatility of trend-based items.

These findings were delivered as three interactive Tableau dashboards their team could explore independently, filter by year, and use in planning meetings without needing a data analyst in the room.

I recommended the client to:
1. **Marketing Budget Reallocation**: Prioritize marketing spend in Lothian and Buckinghamshire, where every pound spent generates a higher return than in higher-volume but lower-margin regions like Derbyshire.
2. **Front-Load Winter Marketing**: Focus Jacket and Hoodie ad spend in September/October to capture the "one-time" seasonal buyer before the November lull.
3. **Inventory Consolidation:** Consider reducing stock in bottom-performing Bras & Tops and reallocating budget to high-margin "Active" lines.
4. **Regional Expansion:** Investigate the success factors in Buckinghamshire to replicate the model in the Greater London market, which has high volume but lower relative margins.

## Sales and Profitability Insights

My analysis uncovered that: 

- Despite being increasingly sensitivite to seasonal shifts, the
business is growing (a 5.7% YoY profit increase in 2021), with an all-time average profit
margin of 52.1%.
- Profit varied by £0.72M across the top five profitable territories, revealing where to allocate marketing spend.
- While Buckinghamshire is far and away the most profitable region, generating £1.59M in sales, Lothian is the most efficient market (56.3% margin) that may offer better ROI on operational costs.


<img width="1796" height="771" alt="sales and profit" src="https://github.com/user-attachments/assets/ae389c0c-5f80-474d-9af0-2ec96ab39233" />



## Seasonal Anomalies & Consumer Psychology

Best vs. Worst Month analysis identified:
- A **logical anomaly:** a 39-44% drop in Jacket and Hoodie sales in November despite peak cold weather, attributable to 'one-time' consumer purchasing behavior for the season. 
- A 78% drop in specific product lines (Bras & Tops) during the Q4 transition, likely due to the combination of a smaller target demographic, allowing for better seasonal inventory planning and clearance strategies.

I used this insight to highlight the importance of promotional timing and inventory management, suggesting that the business may be losing early-winter momentum to Black Friday 'wait-and-see' consumer behavior.

<img width="1784" height="770" alt="quantity sold" src="https://github.com/user-attachments/assets/86300334-9ade-48e3-b468-569b018bd91a" />



## Inventory & Operational Insights

- **Underperformers:** The "Worst Performing Products" list is dominated by the Bras & Tops category (e.g., Electra Bra Top). This suggests an opportunity to either trim this product line or re-evaluate the marketing strategy for the female demographic.

- **Growth Volatility:** Month-over-Month (MoM) Growth Rate revealed high volatility in 2021, indicating that while the business is growing (5.7% YoY profit increase), it is increasingly sensitive to seasonal shifts and supply chain timing.


## Product Performance: Profitability vs. Volume

- **The Profitability Leader:** While Hoodies & Sweatshirts drive the highest volume (£1.96M), the Jackets category maintains the strongest individual product margins.

- **High-Margin "Hero" Products:** The Marco Lightweight Active Hoodie stands out with a 56.3% profit margin, significantly outperforming the store average of 52.1%.

- **Steady Growth:** The Frankie Sweatshirt serves as a benchmark for stability, showing a consistent upward trajectory in profit contribution from 2018 to 2021. In 2021, its profit specifically spiked to £20.6K, nearly doubling its 2018 performance.

<img width="1839" height="751" alt="product performance" src="https://github.com/user-attachments/assets/9d09ce1b-fc45-4c8d-81df-865cab0b2791" />


## Product Lifecycle Insights

I observed that while summer categories (Shorts/Tees) maintained high volume, winter categories like Jackets showed a sharp peak followed by a steep decline in November. This highlights a lower purchase frequency for outerwear; unlike high-rotation summer items, consumers typically invest in a single 'hero' jacket for the season. This insight helps the retailer understand that Jacket marketing must be front-loaded in early Autumn to capture that one-time seasonal spend.

## Strategic Recommendations

1. Front-Load Winter Marketing: Focus Jacket and Hoodie ad spend in September/October to capture the "one-time" seasonal buyer before the November lull.

2. Inventory Consolidation: Consider reducing stock in bottom-performing Bras & Tops and reallocating budget to high-margin "Active" lines.

3. Regional Expansion: Investigate the success factors in Buckinghamshire to replicate the model in the Greater London market, which has high volume but lower relative margins.

## Where to Find the Report

Find the analysis report [here](https://github.com/machaniG/deep-EDA-and-dashboards/blob/main/sales-operation-report.md)

## Where to Find the Dashboards

The dashboards can be accessed [here](https://public.tableau.com/app/profile/fridah.machani/vizzes)
