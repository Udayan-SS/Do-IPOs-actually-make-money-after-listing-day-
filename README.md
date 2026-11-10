# Do IPOs Actually Make Money After Listing Day?

## Project Overview
This project analyses 194 Indian Mainboard IPOs listed between 30 October 2022 and 30 October 2025 to understand whether IPOs generate positive returns after listing.

The analysis compares IPO returns from the issue price and listing-day closing price across listing day, 6-month and 12-month periods.

## Business Objectives
- Evaluate IPO listing-day performance.
- Analyse 6-month and 12-month post-listing returns.
- Compare positive and negative IPO performance.
- Explore subscription patterns and sector-wise performance.
- Identify trends that can support better IPO investment decisions.

## Tools & Technologies
- Python – Data collection, cleaning and analysis
- Pandas, NumPy – Data manipulation
- yfinance – Historical stock price data
- Power BI – Interactive dashboard
- Jupyter Notebook – Analysis workflow

## Project Structure
```text
IPO_Analysis_DA14/
│
├── Dashboard/
│   └── IPO_Analysis_Dashboard.pbix
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── 01_IPO_Data_Collection.ipynb
│
├── report/
│   └── IPO_Insight_Memo.pdf
│
└── .gitignore
```

## Methodology
1. Collected Indian Mainboard IPO listing information.
2. Filtered IPOs based on listing dates.
3. Collected historical stock price data.
4. Cleaned and prepared IPO, subscription and sector datasets.
5. Calculated listing-day, 6-month and 12-month returns.
6. Developed an interactive Power BI dashboard.

## Return Calculation
**Return from Issue Price**

(Returning Price - Issue Price) / Issue Price × 100

**Post-Listing Return**

(Future Closing Price - Listing-Day Closing Price) / Listing-Day Closing Price × 100

For 6-month and 12-month returns, the first available trading-day closing price on or after the respective anniversary date was used.

## Dashboard Pages
1. IPO Market Overview
2. Post-Listing Performance
3. Subscription & Sector Analysis

## Key Findings
- Average return from issue price was 17.53% on listing day.
- Average return from issue price was 23.36% after 6 months.
- Average return from issue price was 35.61% after 12 months.
- However, only 58.42% of IPOs with available 12-month observations generated positive returns from their issue price.

These findings highlight the difference between average returns and the proportion of IPOs that actually generated positive returns.

## Limitations
- Historical stock price data was unavailable for a small number of IPOs.
- Some IPOs had incomplete subscription information.
- Missing return observations were not treated as zero.
- The analysis does not account for brokerage charges, taxes or investor-specific transaction costs.
- Historical performance does not guarantee future returns.

## Disclaimer
This project is for educational and analytical purposes only. It does not constitute investment advice or a recommendation to invest in any IPO.
