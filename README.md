# Superstore Corporate Sales & Profitability EDA

A financial analytics project utilizing Python to evaluate region-level revenue, product margin efficiency, and discount sensitivity inside corporate retail datasets.

## 🎯 Analytical Goals
- **Multi-Level Aggregations:** Nest business categorizations (`Region` -> `Category` -> `Sub-Category`) to trace operational profits.
- **Leakage Identification:** Isolate specific business lines creating negative overall profit margins.
- **Discount Correlation Testing:** Determine numerical thresholds where customer discount strategies begin to trigger financial deficits.
- **Chronological Growth Patterns:** Establish Year-over-Year (YoY) compound revenue changes.

## 🛠️ Stack & Packages
- **Python 3**
- **Jupyter Notebook**
- **Pandas** (Data Transformation & DateTime Math)
- **Matplotlib & Seaborn** (Scatter Profiling, Bar Highlighting, and Profit Heatmaps)

## 📊 Key Highlights
* **Critical Discovery:** Discounts exceeding **40%** systematically destroy profit margins across all categories.
* **Top Revenue Generator:** Technology products (led by "Copiers" as the most efficient sub-category).
* **Worst Performer:** "Tables" represent a high-selling but deeply unprofitable segment across all sales channels.
