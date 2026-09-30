# Sales Performance Analysis

An exploratory data analysis of 4 years of U.S. retail sales (2015-2018) to uncover revenue trends, seasonality, top-performing products and underperforming regions.

## Key Results

| Metric | Result |
|---|---|
| Total sales | **$2.26M** across 4,922 orders and 793 customers |
| Growth | 2018 sales were **50.6% higher than 2015** (+30.6% in 2017, +20.3% in 2018) |
| Seasonality | **Nov + Dec = 29.7%** of all sales |
| Top regions | **West 31.4%**, East 29.6%, Central 21.8%, **South 17.2% (weakest)** |
| Top category | **Technology 36.6%**, Furniture 32.2%, Office Supplies 31.2% |
| Top sub-categories | **Phones ($328K), Chairs ($323K), Storage ($219K)** = 38.5% of sales |
| Top state | **California = 19.7%** of total sales |
| Avg order value | **$459** |
| Avg shipping time | **4.0 days** |

## Business Insights

1. **Q4 is the revenue engine.** Two months generate nearly 30% of annual sales, so inventory and promotions should be planned ahead of September-December.
2. **The South underperforms.** At 17.2% of sales it trails the West by more than 14 points, which makes it the clearest region to investigate (pricing, coverage, customer mix).
3. **Sales are concentrated.** Three sub-categories drive 38.5% of revenue, and California alone contributes about a fifth.
4. **Growth is recent.** Sales dipped 4.2% in 2016, then grew strongly for two consecutive years.

## Data Cleaning

- 9,800 rows and 18 columns loaded
- 11 missing values found in `Postal Code`
- 1 duplicate record removed (ignoring `Row ID`)
- Order and ship dates converted to datetime (`dd/mm/yyyy`)

## Tech Stack

Python (pandas, matplotlib)

## Limitations

The dataset contains sales values only (no profit, cost or quantity), so this analysis measures **revenue performance, not profitability**.

## Author

**Zubin Kotecha** - Data Analyst
[LinkedIn](https://www.linkedin.com/in/zubin-kotecha-7b8685387) | [GitHub](https://github.com/zubinkotecha22-ship-it)
