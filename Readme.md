# Sales Data Analysis (Case Study)

This project presents an end-to-end exploratory data analysis (EDA) of real-world e-commerce sales data from 12 months of 2019, originally provided by [Keith Galli](https://github.com/KeithGalli/Pandas-Data-Science-Tasks). I just need to ensure that I'm good in **Pandas** 

---

## Dataset

- **Source:** Online retail sales data (CSV files, one per month)
- **Columns:** `Order ID`, `Product`, `Quantity Ordered`, `Price Each`, `Order Date`, `Purchase Address`
- **Size:** ~1.7M rows (after merging)

---

## Goals & Questions Answered

1. **What was the best month for sales?**
2. **Which city had the highest sales?**
3. **What time should we display advertisements to maximize purchases?**
4. **What products are most frequently bought together?**
5. **What product sold the most and why?**

---

## Techniques Used

- `pd.concat()` to merge datasets
- Cleaning with `.dropna()`, `.duplicated()`, `.str.startswith()`
- Feature engineering: `Month`, `Sales`, `City`, `Hour`, `Grouped`
- `groupby()` for aggregation
- Lambda functions, `.apply()` for custom extraction
- Visualizations: `matplotlib`, `seaborn`
- Product bundling analysis via `itertools.combinations()` and `collections.Counter`

---

## Key Insights

- **December** was the highest revenue-generating month (~$4.6M in sales).
- **San Francisco** had the highest sales across cities.
- Optimal **advertising hours**: **11 AM** and **7 PM**, when purchases spike.
- **iPhone & Lightning Charging Cable** were most commonly sold together.
- **USB-C Charging Cable** sold the most due to its low price and wide utility.

---

## Business Recommendations

- Boost marketing budget around **December holidays**.
- Run **targeted ad campaigns** in major cities like **San Francisco** and **LA**.
- Place ads between **10:30 AM–12 PM** and **6–8 PM**.
- Offer **bundled product discounts** for high-frequency pairings.
- Promote **affordable, high-volume accessories** to maximize unit sales.

---

## Output

- Final cleaned dataset: `final_all_data.csv`
- Project file: `Sales_Analysis.ipynb`

---

## About Me

**Sanjay Ram** — Aspiring Data Scientist 
**Tech Stack:** Python, Pandas, Matplotlib, Seaborn  

