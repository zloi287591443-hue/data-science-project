# data-science-project
# Apple Stock Price Analysis (2018–2020)

## Research Question
What are the price trends and volatility characteristics of Apple Inc. (AAPL) stock from July 2018 to June 2020?

## Dataset Source and Usage Permission
- Source: Yahoo Finance, Apple Inc. (AAPL) historical daily data.
- Time range: 2018-07-02 to 2020-06-30.
- Variables: Date, Open, High, Low, Close, Adj Close, Volume.
- Usage permission: Used for educational purposes only. The raw data file is included for reproducibility. `Adj Close` accounts for dividends and stock splits.

## Methods and Tools
- Python 3
- pandas: Data cleaning, time series processing, grouped statistics
- matplotlib: Time series plots, boxplots, histograms
- numpy: Return and volatility calculations

## Key Findings
1. **Overall Trend**: The Adjusted Close price increased from ~183 USD to ~365 USD, yielding a total return of **100.22%** over the two-year period.
2. **Market Shock**: In March 2020, the stock experienced a sharp decline, hitting a local low of **223.76 USD** on 2020-03-23, likely due to the COVID-19 pandemic.
3. **Volatility**: The annualized volatility is **36.18%**. The maximum single-day gain was **11.98%** (2020-03-13), and the maximum single-day loss was **-12.80%** (2020-03-16).
4. Moving averages (50-day and 200-day) indicate a death cross in early 2020, followed by a golden cross and strong recovery.

## One Limitation
The dataset only covers a 2-year period (2018–2020) and focuses solely on price and volume. It does not incorporate macroeconomic indicators, earnings reports, or news sentiment, so it describes trends but cannot explain the underlying causes of the price movements.

## How to Run the Analysis
1. Install dependencies: `pip install -r requirements.txt`
2. Ensure `data.csv` and `apple_stock_analysis.ipynb` are in the same directory.
3. Open the notebook: `jupyter notebook apple_stock_analysis.ipynb`
4. Run all cells sequentially.
[requirements.txt](https://github.com/user-attachments/files/33707789/requirements.txt)
[data.csv](https://github.com/user-attachments/files/33707788/data.csv)
[apple_stock_analysis.ipynb](https://github.com/user-attachments/files/33707787/apple_stock_analysis.ipynb)
<img width="1731" height="678" alt="ab4de2e4-6e7a-4b21-bfe9-f66b9eb5fc07" src="https://github.com/user-attachments/assets/181c7963-a459-429c-acb2-a3bc25cc26a7" />
<img width="1775" height="723" alt="6bf14356-b71f-461d-b60b-f4b3173e3307" src="https://github.com/user-attachments/assets/0306ccb6-1b85-4213-a122-d052e1e3af45" />
<img width="1668" height="735" alt="5e919c50-abe9-4b38-9066-006c7a62ad95" src="https://github.com/user-attachments/assets/37680366-b278-4b1f-a4ba-9dcc215dc9bd" />

