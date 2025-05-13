# Trader Behavior Insights – Market Sentiment vs Performance

This project investigates the relationship between Bitcoin market sentiment and trader performance. By analysing historical trade data alongside the Fear & Greed Index, the goal is to uncover behavioral patterns that can support smarter and more adaptive trading strategies.

---

## Project Overview

### 1. Bitcoin Market Sentiment Dataset
- Contains daily sentiment labels: **Fear** or **Greed**
- Captures the overall emotional state of the market on each date

### 2. Hyperliquid Trader Data
- Includes detailed trade records such as:
  - `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.
- Offers a granular view of trader activity and performance over time

---

## Objectives

- Explore how trader behavior changes under different sentiment conditions
- Analyze patterns in profit/loss, leverage usage, trade volume, and side (long/short)
- Derive insights that inform sentiment-aware trading strategies

---

## Analysis Workflow

### 1. Data Cleaning & Preprocessing
- Parsed timestamps and matched dates across datasets
- Removed or imputed missing values
- Merged sentiment data with trade data for joint analysis

### 2. Exploratory Data Analysis
- Visualized distribution of sentiment over time
- Compared average closed PnL on Fear vs. Greed days
- Analyzed leverage usage and trade size across different sentiment phases

### 3. Key Findings
- Some accounts consistently outperformed regardless of sentiment
- Greed days typically saw more aggressive leverage and larger trade sizes
- Fear phases correlated with lower volatility and more conservative strategies

---

## Future Improvements

- Integrate machine learning to predict trade outcomes based on sentiment
- Test rule-based trading strategies under different market conditions
- Add interactive dashboards for live sentiment and performance monitoring
- Include hourly-level sentiment granularity for intraday pattern analysis
