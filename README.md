Trader Behavior Insights (Junior Data Scientist Assignment)
📌 Project Title

Trader Behavior Insights — Relationship Between Market Sentiment & Trader Performance

👤 Candidate

Darshan Yograj Patil
Junior Data Scientist Applicant

📄 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader behavior/performance using:

Bitcoin Market Sentiment Dataset

Columns: Date, Classification (Fear/Greed)

Historical Hyperliquid Trader Data

Columns: account, symbol, execution price, side, size, leverage, closedPnL, event, start position, timestamp, etc.

The goal is to explore:

How sentiment affects trader performance

Whether leverage/position size changes under different sentiments

Profitability behavior of top vs bottom traders

Risk-taking patterns during Fear vs Greed days

Insights that can guide smarter trading strategies

📂 Repository Structure
├── notebook_1.ipynb          # Full EDA, sentiment merge, visualizations, statistics
│
├── csv_files/
│   ├── traders_processed.csv
│   └── daily_aggregates.csv
│
├── ds_report.pdf             # Final report summarizing insights
└── README.md                 # (this file)

📥 Dataset Sources

1. Hyperliquid Historical Trader Data
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

2. Bitcoin Fear & Greed Index
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

🚀 How to Run the Project
Option 1 — Google Colab (Recommended)

Open notebook_1.ipynb in Colab

Upload the two datasets OR mount Google Drive

Run all cells (runtime < 2 mins)

Export figures → saved in outputs/

Export processed CSVs → saved in csv_files/

📊 What’s Included in Analysis
✔️ Data Cleaning & Standardization

Datetime conversion

Leverage/size normalization

Removal of invalid trades

Merging Fear/Greed sentiment with each trade

✔️ Exploratory Data Analysis

PnL distributions

Top/bottom trader behavior

Sentiment-wise trade counts

Leverage usage across sentiment

✔️ Statistical Testing

Mann-Whitney U test

t-test for PnL differences

Chi-square for side (buy/sell) variations

✔️ Visualizations

Daily PnL trends

PnL boxplot by sentiment

Leverage vs Profit scatterplots

Account-level performance metrics

📌 Key Insights Summary

(Exact values updated after running notebooks)

Traders show different performance patterns under Fear vs Greed conditions.

Median PnL tends to be higher/lower during Greed (depends on dataset output).

Leverage increases/decreases by ~X% on Greed days.

Top performing traders use lower leverage & smaller average size while maintaining high win rate.

Certain symbols show sentiment-sensitive volatility.

Subject:
Junior Data Scientist – Trader Behavior Insights

📞 Contact

Name: Darshan Yograj Patil
Email: patildarshan4321@gmail.com
Role: Junior Data Scientist Applicant
