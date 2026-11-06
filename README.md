# Real Estate Market Analysis

## Business Objective
To perform a comprehensive quantitative and exploratory analysis of a real estate market dataset—encompassing properties, customer demographics, sales activity, and performance breakdowns—to uncover key sales drivers, buyer behaviors, and property performance trends that can inform strategic decision-making and marketing optimization.

---

## 📊 Project Scope
* **Dataset Size:** 267 property units across 5 major buildings and 162 unique customers (155 individual buyers and 7 corporate entities).
* **Sales Activity:** Analysis of 195 sold units versus 72 unsold units.
* **Property Metrics:** Evaluation of property pricing (Average: $281,171.90, Range: $117,564.07 to $538,271.74) and area dimensions (Average: 936.22 sq. ft., Range: 410.71 to 1,942.50 sq. ft.).
* **Financial & Satisfaction Tracking:** Analysis of mortgage financing structures (23.22% overall mortgage rate across 62 deals) and buyer satisfaction ratings (3.46 / 5.00 overall; 3.60 / 5.00 for completed sales).

---

## 🛠️ Tools & Technologies
* **Python / Jupyter Notebooks:** Data cleaning, manipulation, and exploratory data analysis (EDA).
* **Pandas & NumPy:** Quantitative metric aggregation, statistical summaries, and correlation calculations.
* **Matplotlib & Seaborn:** Data visualization for demographic breakdowns, price quartiles, and geographic distributions.
* **Markdown / GitHub:** Documentation and project reporting.

---

## 🔍 Key Insights

### Customer & Demographic Profile
* **Buyer Types & Channels:** Individual buyers dominate the market (155 individuals vs. 7 corporate entities). Digital channels serve as the primary acquisition engine, with the website generating 73.46% of buyers (119 users), followed by agencies (36.42%) and client referrals (10.49%).
* **Geographic Concentration:** Domestic buyers from the USA represent **90.77%** of all sold properties (177 buyers). International sales are led by Canada (3.59%) and Russia (2.05%). Within the US, California alone accounts for **66.30%** of cumulative sales (120 sales with an average price of $278,680.74 and a 34% mortgage rate), followed by Nevada, Arizona, Oregon, and Colorado.
* **Age & Buying Power:** The core buying demographic spans **48 to 70 years old** (over 60% of volume), peaking in the 54–59 age bracket (30 sales, 16.85%). However, a Pearson correlation coefficient of **-0.17** indicates a weak negative correlation between age and property purchase price, showing age is not a strong predictor of expenditure.

### Building & Property Performance
* **Price Quartiles & Velocity:** Lower-tier properties sell out significantly faster than luxury units. Budget properties ($\le$ $217,553.06) achieve an 82.09% sell-through rate, whereas Luxury properties (> $326,964.86) sit at a 58.21% sell-through rate.
* **Satisfaction Consistency:** Overall deal satisfaction remains stable across price tiers, ranging from 3.48 to 3.69 out of 5.00, though regional satisfaction varies (e.g., higher ratings in Canada and Germany compared to lower ratings in Denmark and Russia).

---

## Business Value
* **Targeted Marketing Allocation:** With digital website channels and California buyers driving the vast majority of volume and leads, marketing budgets can be optimized to focus heavily on digital acquisition campaigns tailored to high-converting domestic regions.
* **Inventory & Pricing Strategy:** The lower velocity of luxury units compared to budget and mid-tier properties highlights the need for flexible pricing strategies, targeted promotions, or specialized financing options for higher-priced properties to improve overall sell-through rates.
