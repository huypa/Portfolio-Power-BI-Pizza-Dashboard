# ☕ Portfolio – Power BI Pizza Dashboard
## 1. Overview
I designed and developed an interactive **Power BI dashboard** to analyze and visualize **pizza sales performance** across categories, products, and ingredients. The dashboard highlights **revenue trends, order intervals, and product insights**, enabling users to explore top-selling items, dynamic performance rankings, and time-based behavior patterns.
## 2. Project Details

- **Tool:** Power BI  
- **Data Source:** [Pizza Transaction Data (Kaggle)](https://www.kaggle.com/code/mdismielhossenabir/pizza-sales-dataset/input)  
- **Goasl Focus:** Revenue, Product Mix, Store & Time Interval Analysis  
- **Technical Focus:** Power Querry / DAX / Database Design

<img width="1852" height="1036" alt="Screenshot 2025-11-07 at 13 40 19" src="https://github.com/user-attachments/assets/3c97d416-6b2a-4c54-8454-fac13ea316a6" />

    The data model follows a **snowflake schema**, where *fact_sales* serves as the central table connected to key dimensions such as *Dim_product*, *Dim_category*, *Dim_date*, and *Dim_size*. Dynamic slicers and parameter tables allow users to switch between metrics like *Total Revenue*, *Total Orders*, *Total Quantity Sold*, *Average Order Value*, and *Average Pizza per Order*.

    <img width="1430" height="968" alt="Screenshot 2025-11-07 at 13 24 17" src="https://github.com/user-attachments/assets/b7cf5f9f-2ec7-4371-a730-5e4fb3251fd0" />


## 3. Key Features & Insights
*3.1 Revenue & Trend Analysis*
- Line and bar charts visualizing revenue trends by month and category with hover-enabled tooltips showing detailed sales metrics and percent change.

*3.2 Dynamic Metric Selection*
- Powered by DAX parameter logic, enabling instant switching between KPIs (Revenue, Orders, Quantity, AOV, Avg Pizza per Order).

*3.3 Product & Ingredient Rankings*
- Dynamic Top/Bottom N ranking visuals using RANKX and SELECTEDVALUE() for metric-based filtering.
- Ingredient-level charts showing correlation between total revenue and quantity sold with average reference lines.

*3.4 Order Interval Distribution*
- Percentile-based (P25, P50, P75, P90) order interval analysis using DAX window functions to track order timing and customer frequency.

*3.5 Category & Size Analysis*
- Weighted average pizza price and category-level performance indicators to identify best-selling combinations.

## 4. Color & Design System

- **Palette:** Bright, modern tones — tomato red, mozzarella white, and basil green inspired by pizza ingredients.
- **Highlights:** Used contrast and accent colors to separate key KPIs and trends.
- **Layout:** Balanced use of bar, line, and scatter charts with clean spacing and rounded visual cards.

## 5. Interactivity & Usability

- **Dynamic Filters:** Filter by *Month*, *Category*, *Metric*, or *Product*.
- **Top/Bottom Switch:** User-controlled toggle for ranking visualizations.
- **Hover Cards:** Show detailed breakdowns like average order value, order count, and category contribution.
- **Drill-down:** Explore data from category level to individual product or ingredient performance.

## 6. Results

Delivered an **insight-driven dashboard** that enhanced:
- Enhanced **visibility into product and category-level performance**
- Improved understanding of **sales distribution and order timing**
- Enabled **data-driven optimization** for product mix and customer engagement 

This dashboard provides an **intuitive, visually engaging view** of pizza sales trends and performance insights through smart, dynamic DAX and design-driven storytelling.




