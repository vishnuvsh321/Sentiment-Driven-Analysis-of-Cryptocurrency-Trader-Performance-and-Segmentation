# Sentiment-Driven-Analysis-of-Cryptocurrency-Trader-Performance-and-Segmentation
Analyzing how the Fear &amp; Greed Index influences crypto trader behavior, profitability, and segmentation using 211k+ trades, with a predictive model for next-day profitability.

[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)](https://pandas.pydata.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3+-orange.svg)](https://scikit-learn.org/)

## 📊 Project Overview

This project analyzes how market sentiment (Fear & Greed Index) influences cryptocurrency trader behavior and profitability. Using over 211,000 real trades and sentiment data from 2018-2024, we uncover which trader types perform best under different market conditions and build a predictive model for next-day profitability.

## 🎯 Key Findings

| Finding | Insight |
|---------|---------|
| **Most Profitable Sentiment** | "Greed" periods show highest avg PnL ($87.89) |
| **Highest Win Rate** | "Extreme Greed" periods (49% profitable trades) |
| **Most Active Trading** | "Fear" periods drive highest trade volume (133,871 trades) |
| **Largest Trade Sizes** | "Extreme Greed" periods ($5,660 avg trade size) |
| **Best Performing Segment** | High-size traders outperform across all sentiments |
| **Counter-Intuitive Finding** | Inconsistent & infrequent traders outperform consistent/frequent ones in most conditions |
| **Model Accuracy** | Random Forest predicts next-day profitability with **64.29% accuracy** |

## 🧠 Methodology

1. **Data Preprocessing** - Merge sentiment data with trade records by date
2. **Feature Engineering** - Create daily PnL, win rate, trade frequency, avg trade size
3. **Performance Analysis** - Analyze PnL and win rate by sentiment
4. **Behavior Analysis** - Examine trade frequency, size, and buy/sell patterns
5. **Trader Segmentation** - Group traders by size, consistency, frequency, profitability
6. **Predictive Modeling** - Train Random Forest to forecast next-day profitability

## 📁 Dataset

| File | Records | Description |
|------|---------|-------------|
| `fear_greed_index.csv` | 2,644 | Daily Fear & Greed Index scores (2018-2024) |
| `historical_data.csv` | 211,224 | Individual trade records with PnL, size, side, etc. |

## 🚀 Getting Started

### Prerequisites

```bash
pip install -r requirements.txt
