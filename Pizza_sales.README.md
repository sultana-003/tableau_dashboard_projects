# Pizza Sales Analysis Dashboard (Tableau Project)

## Project Overview
##### This project analyzes a 2015 pizza sales dataset to uncover business insights related to revenue, customer ordering behavior, product performance, and ingredient popularity.
##### The goal of this analysis is to help the business understand:
- Which pizzas generate the most revenue
- Which categories perform best
- Which ingredients are most used
- How pricing differs across categories
- When customers order the most (Part of the Day)
- This dashboard was built using Tableau and focuses on business-friendly, actionable insights.

## Dataset Description
The dataset contains detailed transactional information for pizza orders.

### Key Columns:

- order_id – Unique order identifier
- order_date – Date of the order
- order_time – Time of the order
- pizza_name – Full pizza name
- pizza_category – Category (Classic, Supreme, Chicken, Veggie)
- pizza_size – Size (S, M, L)
- quantity – Number of pizzas ordered
- unit_price – Price per pizza
- total_price – Total price per row
- pizza_ingredients – Ingredients used
The dataset represents individual pizza-level transactions, meaning one order can contain multiple pizzas.

## Dashboard Visualizations

### 1️⃣ Top 5 Pizza Names by Total Revenue

##### Chart Type: Horizontal Bar Chart
##### Measure: SUM(Total Price)
##### Dimension: Pizza Name

### Purpose:

##### This chart identifies the top 5 highest revenue-generating pizzas.

### Insight:

- The top pizzas contribute a significant portion of total revenue.
- Premium pizzas (higher unit price) tend to appear in the top rankings.
- Popular pizzas combine strong branding and balanced ingredients.

### Business Value:

- Helps management focus on:
- Promoting best-performing pizzas
- Maintaining stock for high-demand items
- Designing combo offers around top sellers

### 2️⃣ Pizza Category Performance

##### Chart Type: Donut chart
##### Measure: SUM(Total Price)
##### Dimension: Pizza Category

### Purpose:

##### To analyze which category generates the most revenue.

##### Categories:
- Classic
- Supreme
- Chicken
- Veggie

### Insight:

- One or two categories dominate overall sales.
- Classic and Supreme categories typically generate higher revenue.
- Veggie and Chicken show niche but stable demand.

### Business Value:

- Helps in product mix decisions.
- Assists marketing campaigns by category.
- Supports future menu expansion planning.

### 3️⃣ Top Ingredients Analysis

##### Chart Type: Horizontal Bar Chart
##### Measure: Count of Ingredient Occurrence
##### Dimension: Pizza Ingredients (Split and cleaned)

### Purpose:

##### To understand the most frequently used ingredients across pizzas.

### Insight:

- Ingredients like Mozzarella Cheese, Garlic, Tomatoes, and Pepperoni appear most frequently.
- Cheese-based and traditional ingredients dominate the menu.

### Business Value:

- Helps optimize inventory planning.
- Identifies core ingredients that must never go out of stock.
- supports supplier negotiation for high-volume ingredients.

### 4️⃣ Category by Unit Price & Total Revenue

##### Chart Type: Dual Axis Bar Chart
##### Measures:
- AVG(Unit Price)
- SUM(Total Price)
##### Dimension: Pizza Category

###  Purpose:
- To compare pricing strategy vs actual revenue performance.

### Insights:

- Some categories may have higher average prices but lower total revenue.
- Others may have moderate pricing but generate higher sales volume.

### Business Value:

- Identifies whether revenue is driven by price or volume.
- Helps adjust pricing strategies.
- Supports profitability analysis.

### 5️⃣ Sales by Part of the Day

##### Chart Type: Bar Chart
##### Dimension: Part of the Day (Morning, Afternoon, Evening, Night)
##### Measure: SUM(Total Price)

### Purpose:

##### To analyze customer ordering behavior by time.

##### Time Segments:

- Morning (8 AM – 12 PM)
- Afternoon (12 PM – 5 PM)
- Evening (5 PM – 9 PM)
- Night (After 9 PM)

### Insight:

- Afternoon and Evening typically generate the highest sales.
- Morning sales are lower (non-breakfast product).
- Night sales show moderate demand.

## Analysis Summary

##### From the dashboard, we can conclude:

- Revenue is concentrated among a few top-performing pizzas.
- Classic and Supreme categories are strong revenue drivers.
- Cheese and traditional ingredients dominate the menu.
- Sales peak during Afternoon and Evening hours.
- Revenue performance is influenced by both pricing and demand volume.
- Overall, the business shows a strong dependence on premium and classic offerings during peak dining hours.

## Recommendations
### 1️⃣ Promote Top Sellers
- Create bundle deals around top 5 pizzas to maximize revenue.

### 2️⃣ Time-Based Offers
##### Introduce:
- Afternoon combo discounts
- Evening family meal deals
- Late-night promotions

### 3️⃣ Inventory Optimization

##### Maintain higher stock for:
- Mozzarella Cheese
- Garlic
- Tomatoes
- Pepperoni

### 4️⃣ Category-Based Marketing

##### If Supreme category drives high revenue:
- Highlight it in marketing campaigns.
- Introduce new Supreme variants.

### 5️⃣ Pricing Strategy Review

##### If some high-priced categories underperform:
- Re-evaluate pricing.
- Offer seasonal discounts.


## Conclusion

##### This Tableau dashboard provides a comprehensive view of pizza sales performance across product categories, ingredients, pricing, and time of day.

##### The insights can help management:
- Improve operational efficiency
- Increase revenue through targeted promotions
- Optimize inventory
- Enhance customer satisfaction
