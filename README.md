# ‎🏥 Hospital Health Data Dashboard Documentation

This Hospital Health Data Dashboard was created in Microsoft Excel to analyze hospital performance across different years, focusing on patients, treatment types, diagnoses, doctors, and revenue.
‎
> 🔍 Objective: ‎The goal was to visualize patient distribution, cost analysis, and key performance indicators (KPIs) such as total patients, revenue, and most common diagnosis.

---

## 🏢 Project Context

**Industry:** Health Analytics  
**Role:** Junior Data Analyst  
**Tools Used:** Microsoft Excel (Pivot Tables, Slicers, Cards, Charts, Conditional Formatting)

---

## 🧾 Dataset Description

- **Total Records:** 5,000
- **Columns:** 9

- **Each row represents:** A unique product
- **Fields included:**
  - Product name
  - Category
  - Actual price & Discounted price
  - Discount %
  - Rating
  - Number of Ratings (Rating Count)
  - Review content (aggregated in some columns)
  - Revenue potential fields (derived)
  ---

## 📊 Key Analytical Tasks & Solutions

| #  | Task Description                                                                 | Excel Tools/Logic Used                        |
|----|-----------------------------------------------------------------------------------|-----------------------------------------------|
| 1  | What is the average discount % by product category?                              | Pivot Table + Average Formula                 |
| 2  | How many products are listed under each category?                                | Pivot Table + Count                           |
| 3  | What is the total number of reviews per category?                                | SUM of `Rating Count` by category             |
| 4  | Which products have the highest average ratings?                                 | Sorting based on calculated `Average Rating`  |
| 5  | What is the actual vs discounted price by category?                              | Grouped Bar Chart + Pivot Summary             |
| 6  | Which products have the highest number of reviews?                               | Top-N Analysis using Sorting + Pivot Table    |
| 7  | How many products have ≥ 50% discount?                                            | Filter logic on Discount column               |
| 8  | What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?              | Grouped histogram with Pivot Count            |
| 9  | Total potential revenue (actual_price × rating_count) per category?              | New Calculated Column + Pivot Table SUM       |
| 10 | Unique product count per price range bucket (<₹200, ₹200–₹500, >₹500)?           | IF formulas + Donut Chart                     |
| 11 | Relationship between rating and discount level?                                  | Scatter Line Chart (2 y-axes)                 |
| 12 | How many products have fewer than 1,000 reviews?                                  | COUNTIF Formula + Bar Chart                   |
| 13 | Categories with highest average discount?                                        | Sorted Pivot Table by Discount%               |
| 14 | Top 5 products by combined review count and rating                               | Ranking logic using SUM(Rating × ReviewCount) |

---
## 📸 Visuals & Dashboard

![RAW DATASET](https://drive.google.com/uc?export=view&id=1MJZZAHJDxb3FSiW7zOEBTBLhG2_GzfSX)

![CEANED DATASET](https://drive.google.com/uc?export=view&id=19ME4caXkqO8BhZ7kK9NF9X1xV3q0TEAb)

![PIVOT TABLE](https://drive.google.com/uc?export=view&id=1nBqNHalmK9cq4AUGhtXKgZBZ-nvniSpO)

![PROJECT DASHBOARD](https://drive.google.com/uc?export=view&id=1QEUtR0bhzeXc1xSpA9FBm4bheIXHmGV3)

### 🧠 Key Highlights from Dashboard:

- **Discount vs Rating**: Discounted products don’t always have higher ratings. There’s a complex relationship.
- **Price Range Bucket**: Most products fall under the affordable to moderately expensive range.
- **Revenue Potential**: Categories like *Home Kitchen* and *Electronics* dominate in potential revenue.
- **Category-wise Review Count**: Electronics and accessories lead in user engagement.
- **Top 5 Products**: Based on high review count and strong ratings (e.g., AmazonsBasics FI, Realme X, etc.)
- **Discount Percentage by Category**: Health and home products offered the most generous discounts.

---

## 🧠 Skills & Competencies Demonstrated

| Skill                      | How I Applied It                                               |
|---------------------------|----------------------------------------------------------------|
| **Data Cleaning**         | Removed nulls, corrected inconsistent formats, trimmed text    |
| **Data Aggregation**      | Used pivot tables and grouping to summarize key insights       |
| **Excel Formulas**        | `IF`, `COUNTIF`, `AVERAGEIFS`, `PROPER`, calculated columns  |
| **Visualization**         | Designed intuitive charts (bar, pie, line, donut, cards)       |
| **Slicers & Cards**       | Enabled dynamic filtering and KPI display                     |
| **Business Reasoning**    | Drew conclusions based on data trends and business logic       |

---

## 💡 Business Insights (Summary)

1. **High Discount ≠ High Rating:** Many discounted items still received poor ratings. Price cuts alone won’t ensure customer satisfaction.
2. **Most Reviewed Category:** Electronics had the most reviews but also a wide range in satisfaction.
3. **Revenue Optimization:** Focus marketing efforts on mid-priced, highly rated products in "Home Kitchen" and "Accessories".
4. **Product Opportunity:** Products with moderate ratings but high volume reviews may benefit from improved quality or targeted feedback campaigns.
5. **Outlier Products:** A few products drive massive engagement. Promoting these further can help with cross-selling.

---

## 🔧 Tools & Environment

- **Microsoft Excel**
  - Pivot Tables
  - Data Visualizations (Bar, Line, Donut)
  - Filters
  - Conditional Formatting
  - Named Ranges & Table References
