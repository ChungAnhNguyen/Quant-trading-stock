# Introduction to Quantitative Trading & NVIDIA trading strategy implementation based on MACD
- Author: Nguyen Chung Anh
- Date: 2025-01-11

This notebook contains the basic concepts and Python implementation of QT.
- Basic Concepts of QT
- Market data acquisition and cleaning
- Calculation and visualization of technical indicators
- Implementation of simple trading strategies
- Basic backtesting methods



## Stock Bollinger Band Analysis

## Chart basic information
- **Subject Asset**: Tesla (TSLA)
- **Timeframe**: May 2022 - May 2025 (with forecast data)
- **Key Metrics**.
  - Closed Price
  - Upper-track (Upper-track = Mid-track + 2 x Standard Deviation)
  - Mid-track (Mid-track = 20-day SMA)
  - Lower Bollinger Band (Lower-track = Mid-track - 2 x Standard Deviation)

---

## Key Timeframe Analysis

----

## Multi-Dimensional Validation Indicator Suggestions
| Signal Types | Bollinger Band Patterns | Validation Indicators | Reliability Improvement Methods |
|----------------|------------------|-----------------------|-----------------------|
| Overbought Signal | Price touched the upper rail | RSI >70 + Volume Divergence | Wait for price to return to the middle rail before taking action |
| Oversold Signal | Price hits lower rail | RSI <30 + Panic Selling | Split Positions + Tight Stop Losses |
| Trend Continuation | Channel Continues to Expand | MACD Columns Enlarged | Moving Stops to Follow the Trend |
| Trend reversal | Channel contracting fast | Volatility Index (VIX) spiking | Reverse after breakout confirmed |


## Summary

In this notebook, I have learned:
1. how to acquire and process stock data
2. how to calculate and visualize technical indicators
3. how to implement a simple moving average crossover strategy
4. how to evaluate the performance of a strategy
