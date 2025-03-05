# AI Stocks vs. Market – Is the AI Boom Real or Just Hype?

## 📌 Overview
In this project, I analyzed leading AI stocks (**NVDA, GOOG, MSFT, META, AMD**) and compared them to the **S&P 500** to determine if they truly outperform the market or if they are just riding the AI hype.

## 🔎 Key Steps & Analysis

### ✅ Data Collection & Normalization
- Pulled stock data from **Yahoo Finance**.
- Normalized prices to compare **cumulative returns over time**.

### ✅ Beta Calculation (Market Sensitivity)
- Measured how AI stocks move relative to the **S&P 500**.
- **High Beta** → More volatile than the market.
- **Low Beta** → Less sensitive to market swings.

### ✅ CAPM & Alpha Calculation (Expected vs. Actual Return)
- Used the **Capital Asset Pricing Model (CAPM)** to determine expected returns.
- **Alpha = Actual Return - Expected Return**
- **Positive Alpha** → Stock outperformed market expectations.
- **Negative Alpha** → Stock underperformed compared to market expectations.

### ✅ Sharpe Ratio (Risk-Adjusted Performance)
- Calculated the **Sharpe Ratio** to see if AI stocks justify their risk.
- **NVDA & MSFT** had the best risk-adjusted returns, outperforming the **S&P 500**.
- **META** underperformed the market in risk-adjusted terms.

### ✅ Visualization & Insights
- Plotted **cumulative returns** to compare AI stocks vs. **S&P 500**.
- Created a **Sharpe Ratio bar chart** to highlight the best AI investments.

## 📊 Key Takeaways
- The **AI boom is real**, but **not all AI stocks are equal**.
- **NVDA & MSFT** offer the best **risk-adjusted returns**, making them strong investments.
- **META**'s AI growth **hasn’t translated** into better risk-adjusted performance yet.
- **AI stocks outperform in some cases, but investors must be selective**.

## 📊 Data Source
This project uses historical stock data from Yahoo Finance. Since the dataset is large, it is **not included** in this repository.

To download fresh data, run the `data_fetch.py` script, which will pull the latest stock prices for analysis.

## 📂 Project Structure
```
📂 AI-Stocks-CAPM-Analysis/
│── 📜 README.md              
│── 📜 requirements.txt        # Required Libraries
│── 📂 notebooks/              # Jupyter Notebook file
│    ├── AI_Stocks_Analysis.ipynb
│── 📂 visuals/                 # Images for README.md
│── 📜 LICENSE       
```

## ⚙️ Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/AI-Stocks-CAPM-Analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/AI_Stocks_Analysis.ipynb
   ```
4. Have the necessary dataset and Run the cells and analyze the data!


## 🏆 Future Improvements
- Adding **Monte Carlo simulations** to test different market scenarios.
- Incorporating **sector-wide AI investment trends**.
- Enhancing **data sources** with real-time API integration.

What’s next for AI stocks? Are they still the **best bet**, or should investors be cautious? Let’s discuss! 

