 Nifty 500 Gap-Down Recovery Trading Strategy

 📌 Project Overview
This project analyzes a **gap-down recovery trading strategy** on Nifty 500 stocks using Python and Jupyter Notebook.  
It fetches historical price data using `yfinance`, applies the strategy rules, and generates an **Excel report** with key trade metrics.

 Strategy Summary
- **Entry:** Stock gaps down more than 2% from the previous day’s close, then recovers to or above the previous close, plus gains at least 2% more on that same day.
- **Target:** 10% profit
- **Stop Loss:** -5%
- **Max Holding:** 60 days

---

 📂 Files in Repository
- `Trade_Analysis.ipynb` — Main notebook with strategy code and analysis  
- `ind_nifty500list.csv` — List of Nifty 500 stocks (symbols)  
- `output.xlsx` — Generated report with trade details (created after running the notebook)

---
 ⚙️ Requirements
Install the required Python packages:
pip install yfinance pandas openpyxl

---

## ▶️ How to Run
1. Download or clone this repository.
2. Ensure the file `ind_nifty500list.csv` is present in the repository folder.
3. Open `Trade_Analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run all the cells to fetch data, apply the strategy, and generate results.
5. The output Excel file (`output.xlsx`) will be saved in the same directory.

---

## 📊 Output
The generated Excel file contains:
- Win rate
- Number of holding days per trade
- Entry & exit dates/prices
- Profit/Loss (%) for each trade
- Exit reason (Target hit, Stop loss hit, Max holding reached)

---

## 📜 License
This project is for educational purposes only.  
Use it at your own risk for live trading.


