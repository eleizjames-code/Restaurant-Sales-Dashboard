# Tastescape Restaurant Dashboard

## Overview
This dashboard provides a comprehensive overview of Tastescape Restaurant's performance over a 13-week  period, focusing on revenue, orders, and customer behavior. It highlights key metrics, category and item  performance, time-based patterns, and actionable insights to support data-driven decision-making.

<p align="center">
  <img src="https://github.com/eleizjames-code/Restaurant-Sales-Dashboard/blob/main/Tastescape%20Restaurant%20Sales%20Dashboard%20(PNG).png?raw=true" alt="Tastescape Restaurant Sales Dashboard" width="80%">
</p>
<p align="center"><b>Figure 1:</b> Tastescape Restaurant Sales Dashboard</p>

<p align="center">
  <img src="https://github.com/eleizjames-code/Restaurant-Sales-Dashboard/blob/main/Order%20Insights%20(PNG).png?raw=true" alt="Tastescape Restaurant Sales Dashboard" width="80%">
</p>
<p align="center"><b>Figure 2:</b> Order Insights</p>

<p align="center">
  <img src="https://github.com/eleizjames-code/Restaurant-Sales-Dashboard/blob/main/Revenue%20Insights%20(PNG).png?raw=true" alt="Tastescape Restaurant Sales Dashboard" width="80%">
</p>
<p align="center"><b>Figure 3:</b> Revenue Insights</p>

## Dataset Used
<a href = "https://github.com/eleizjames-code/Tastescape-Restaurant-Dashboard/raw/refs/heads/main/Tastescape%20Restaurant%20Dashboard.xlsx"> Tastescape Restaurant Data </a>

## Key Questions
1. What are the trends in revenue, orders, and customers over the 3-month period?
2. Which food categories and items perform best in terms of revenue, orders, and customer preference?
3. When are the peak ordering times and which days contribute the most revenue?
4. What share of business is contributed by the top 5 items versus other menu offerings?
5. Which months or weeks contribute the most to overall performance?

## Process
1. **Extract**: Imported data from a CSV file using Excel’s **Get Data**.
2. **Transform**: Cleaned and formatted the data in** Power Query**.
3. **Load**: Loaded the data into the **Excel Data Model (Power Pivot)**.
4. Created **measures**and used formulas (e.g., VLOOKUP, INDEX-MATCH, LARGE, MAX etc.).
5. Built **Pivot Tables** and Charts to generate KPIs and trends.
6. Added **slicers** and **option buttons** for filtering and interaction.
7. Designed a clear, interactive **dashboard**for analysis.

## Insights
- **Overall Growth**: There is a consistent positive trend in performance from February to March:
    - Revenue increased by 7.52%
    - Orders by 7.55%
    - Customers by 9.20%
- **Weekly Performance**:
    - Revenue peaked in Week 13 (13.3K) and was lowest in Week 5 (11.0K).
- **Top Categories**:
  - Customers: Prefer Asian (49%), followed by American (40%).
  - Orders: Mostly from Asian (28%), followed by Italian and Mexican (24% each).
  - Revenue: Highest from Italian (31%), followed by Asian (29%).
- **Top Performing Items**:
  - By Revenue: Korean Beef Bowl leads with 11K revenue.
  - By Orders: Hamburger leads with 622 orders.
  - By Customers: Edamame leads with 596 customers.
- **Customer and Order Distribution:**
  - Top 5 Items account for only around 24–27% of total orders and revenue, indicating a diverse customer preference across the menu.
- **Rush Hours:**
  - Highest order volumes are at 12 PM, 1 PM, and 5 PM, accounting for 37.74% of total orders.
- **Day-wise Revenue:**
  - Highest revenue days are Monday (26K) and Tuesday (23.4K).
  - Wednesday (19.9K) is the lowest performing day.

## Conslusion
  Tastescape Restaurant shows a healthy and consistent growth trend with a broad customer base and diverse menu appeal. While Asian cuisine is most favored by customers and in order volume, Italian dishes bring in the highest revenue. Time and day trends highlight lunchtime and early evening as peak order periods, with the beginning of the week bringing in the highest revenue.

## Recommendations
1. Promote High Revenue Items: Focus marketing around top revenue items like Korean Beef Bowl and Spaghetti & Meatballs, especially during off-peak days like Wednesday.
2. Optimize Staffing and Inventory: Ensure sufficient staff and ingredient supply during peak hours (12 PM, 1 PM, 5 PM) and on high-revenue days (Mon/Tue).
3. Diversify Menu Strategy: Since the top 5 items contribute to less than 30% of business, continue offering variety while promoting hidden high-margin items.
4. Targeted Promotions:
   - Offer discounts or bundles during slower days like Wednesday.
   - Introduce “happy hour” promos during off-peak times to flatten the demand curve.
5. Customer Retention: Leverage customer data (5.4K in March, up 9.2%) for loyalty programs or repeat-visit incentives.
