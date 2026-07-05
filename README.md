# 📊 Trader Behavior Analysis Based on Bitcoin Market Sentiment

## Overview

This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **historical trader performance** using data from Hyperliquid. The objective is to uncover patterns in trading behavior, profitability, and market sentiment to derive actionable insights for smarter trading strategies.

This project was completed as part of a **Data Science Hiring Assignment**.

---

## Objective

The primary goal of this project is to investigate how market sentiment influences trader performance by:

- Analyzing profitability across different market sentiments.
- Comparing Buy and Sell trading behavior.
- Identifying the most actively traded and profitable cryptocurrencies.
- Exploring trading volume and profitability trends.
- Discovering correlations among trading metrics.

---

## Dataset

The analysis uses two datasets:

### 1. Bitcoin Fear & Greed Index
Contains daily market sentiment information.

**Features**
- Date
- Fear & Greed Value
- Market Sentiment Classification

### 2. Historical Hyperliquid Trader Data
Contains historical trading records.

**Features**
- Account
- Coin
- Execution Price
- Size (Tokens & USD)
- Side (Buy/Sell)
- Timestamp
- Start Position
- Closed PnL
- Fee
- Transaction Information

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Date Conversion
4. Dataset Merging
5. Exploratory Data Analysis (EDA)
6. Visualization
7. Business Insights
8. Conclusion

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Exploratory Data Analysis

The following analyses were performed:

- Market Sentiment Distribution
- Average Closed PnL by Market Sentiment
- Total Closed PnL by Market Sentiment
- Win Rate by Market Sentiment
- Buy vs Sell Trade Analysis
- Buy vs Sell Profitability
- Top 10 Most Traded Coins
- Top 10 Coins by Average Profit
- Trading Volume Analysis
- Closed PnL Distribution
- Hour-wise Trading Performance
- Correlation Heatmap

---

## Key Insights

- Trading profitability varies across different market sentiment conditions.
- Extreme Greed periods tend to exhibit stronger average profitability compared to Fear and Neutral periods.
- The most actively traded cryptocurrencies are not always the most profitable.
- Larger trade sizes are associated with higher transaction fees.
- Market sentiment alone has a weak linear relationship with profitability, indicating that multiple factors influence trading performance.

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Trader-Behavior-Analysis.git
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Open the notebook using:

- Google Colab
- Jupyter Notebook

4. Place the datasets in the working directory.

5. Run all notebook cells.

---

## Future Improvements

- Machine Learning model for profitability prediction.
- Interactive dashboard using Plotly or Streamlit.
- Time-series forecasting of market sentiment.
- Advanced trader segmentation and clustering.

---

## Author

**Ayaz Ahmad**

---

## License

This project is intended for educational purposes..
