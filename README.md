Trading Sentiment Analysis – Trader Behavior Insights

1) Project Overview
   
This project analyzes trader behavior by combining Bitcoin market sentiment data (Fear & Greed Index) with historical trader-level trading data.
The goal is to understand how trader performance and behavior change across different market sentiment conditions.

2) Datasets Used

Bitcoin Market Sentiment Dataset
Columns: Date, Classification (Fear / Greed / Extreme Fear / Extreme Greed)
Historical Trader Data (Hyperliquid)
Columns include: account, symbol, execution price, size, side, time, closedPnL, leverage, etc.

3) Tools & Technologies

Python
Pandas
NumPy
Matplotlib
Jupyter Notebook

4) Key Analysis Performed

Data cleaning and preprocessing
Merging sentiment data with trader data by date
Analysis of:
Average PnL by sentiment
Number of trades per sentiment
Best performing trade side (BUY / SELL)
Top performing coins during each sentiment phase
Visualization of results using bar charts

5) Output

Summary tables showing trader performance across sentiment categories
Visualizations for top-performing coins by sentiment
Final merged dataset saved as:
Merged_Trader_Sentiment_Analysis.csv

6) How to Run

Clone the repository
Open trading_analysis.ipynb
Install required libraries if not already installed
Run all cells to reproduce the analysis and outputs

7) Conclusion

The analysis highlights how trader behavior and profitability vary significantly under different market sentiment conditions, providing useful insights into sentiment-driven trading patterns.
