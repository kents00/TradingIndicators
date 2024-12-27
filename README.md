# TradingIndicators

## Introduction
This project contains a collection of custom trading indicators designed to help traders make informed decisions in the financial markets. Each indicator is implemented in Pine Script and can be used on the TradingView platform.

## Indicators
### Range Filter Buy and Sell [Strategy]
![BTCUSD_2024-12-27_13-45-25](https://github.com/user-attachments/assets/41d7e014-2705-4372-ace1-557168f70e0d)
The `Range Filter Buy and Sell [Strategy]` indicator is designed to identify potential buy and sell signals based on a range filter logic. It combines support and resistance levels, moving averages, and candlestick pattern recognition to generate trading signals. The main features include:
- **Support and Resistance Levels**: Identifies key support and resistance levels based on pivot highs and lows.
- **Moving Averages**: Uses 20-period and 50-period simple moving averages to confirm trends.
- **Candlestick Pattern Recognition**: Detects bullish and bearish engulfing patterns to identify potential reversals.
- **Range Filter Logic**: Applies a range filter to smooth out price movements and identify trend directions.
- **Trade Conditions**: Generates long and short entry signals based on the combination of the above factors.
- **Stop Loss and Take Profit**: Allows for the configuration of stop loss and take profit levels to manage risk.

## How to Import and Run in TradingView
1. Open TradingView and log in to your account.
2. Click on the "Pine Editor" tab at the bottom of the screen.
3. Copy the entire content of the `Indicators/rangefilter.pine` file.
4. Paste the copied content into the Pine Editor.
5. Click the "Add to Chart" button to apply the indicator to your chart.
6. To customize the indicator settings, click on the gear icon next to the indicator name in the chart legend.
