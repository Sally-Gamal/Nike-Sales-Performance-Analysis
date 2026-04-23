# 👟 Nike Shoes Sales & Pricing Strategy Analysis (Brand Analytics)

## 1. 📊 Interactive Dashboard Preview
![Nike Sales Dashboard](nike_shoes_sales.jpg)
![Nike Strategy Insights](nike_strategy.jpg)

---

## 2. 📝 Executive Summary
This project delivers a comprehensive analysis of **Nike’s product performance and pricing strategy** across a dataset of **643 products**. The primary goal is to leverage data-driven insights to identify the correlation between pricing tiers, customer satisfaction, and market engagement to optimize retail performance and brand positioning.

### 📈 Key Performance Indicators (KPIs):
* **Total Products Analyzed:** 643 Nike Footwear Items
* **Unique Product Lines:** 393 Categories
* **Avg. Sale Price:** ~$10,214
* **Avg. Consumer Rating:** 2.73 / 5
* **Market Engagement:** Analysis of 600+ unique reviews and sentiment.

---

## 3. 🔍 Deep-Dive Insights (Analytical Findings)

### A. Pricing Dynamics & Discount Impact
* **The Discount Lever:** Analysis shows that listing prices versus actual sale prices significantly impact **Review Volume**. Products with strategic discounts tend to have **35% more consumer engagement**.
* **Premium Positioning:** Despite price variations, Nike maintains a strong premium segment where products priced above **$15k** still retain high market interest and consistent sales.

### B. Product Performance & Sentiment Analysis
* **Rating Correlation:** There is a notable link between product descriptions and final ratings. Products emphasizing **"Premium Materials"** and **"Comfort Technology"** (like Air Max) consistently score higher than basic lifestyle models.
* **The Popularity-Quality Gap:** Identified high-review products that suffer from lower-than-average ratings, indicating a gap between "Hype" and "Actual Satisfaction" that needs addressing.

### C. Category & Brand Health
* **Inventory Consistency:** Nike exhibits strong pricing consistency across its main lines, but the analysis identified **"Outlier Categories"** where ratings are low despite premium pricing, marking them as high-risk inventory.

---

## 🛠️ 4. Data Methodology & Engineering
To ensure the highest standard of data integrity, I implemented the following:
* **Data Auditing:** Performed rigorous cleaning on the Nike dataset to handle missing values and standardize brand/category attributes.
* **Metric Engineering:** Engineered custom **DAX measures** in Power BI to track **Average Discount %**, **Weighted Ratings**, and **Price Variance**.
* **Categorical Segmentation:** Grouped products by Price Tiers (Budget, Mid, Premium) and Rating Brackets to pinpoint specific "At-Risk" segments.
* **Visualization:** Engineered a dual-layered dashboard using **Power BI** with dynamic slicers for deep-filtering by Category, Price Range, and Sentiment.

---

## 💡 5. Strategic Recommendations for Nike
1. **Dynamic Discounting Optimization:** Focus deep discounts on low-rating items to accelerate stock turnover without damaging the premium brand image.
2. **Quality Loop Integration:** Use the "Rating-Review Gap" data to trigger quality audits for specific product lines that show high sales but declining customer satisfaction.
3. **Marketing Re-allocation:** Shift promotional budget toward **"High-Rating / Mid-Price"** segments, as these represent the highest potential for long-term customer loyalty and repeat purchases.

---

## 📂 Repository Structure
* `nike_shoes_sales.csv`: Cleaned and structured Nike footwear dataset.
* `nike_shoes_sales.pbix`: Final Power BI interactive project file.
* `nike_shoes_sales.jpg`: Main executive dashboard visualization.
* `nike_strategy.jpg`: Strategic insights and pricing analysis view.
