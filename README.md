# VWAP Volume And Price - ReadMe

This code is a custom indicator for MetaTrader 5 (MQL5) called 'VWAP Volume And Price'. It calculates the Volume Weighted Average Price (VWAP) for a given period and displays it as a line on the chart.

## Inputs

- **Timeframe**: The timeframe for which the VWAP will be calculated (default: H1).
- **Period**: The number of candles used to calculate the VWAP (default: 20).

## Installation

To use this indicator, follow these steps:

1. Download the 'VWAP Volume And Price.ex5' file.
2. Open your MetaTrader 5 platform.
3. Go to 'File' > 'Open Data Folder'. This will open the folder where your MetaTrader 5 data is stored.
4. Open the 'MQL5' folder.
5. Open the 'Indicators' folder.
6. Copy the 'VWAP Volume And Price.ex5' file into this folder.
7. Restart MetaTrader 5.
8. The indicator will now appear in the 'Navigator' window under the 'Custom Indicators' section.

## How It Works

The VWAP is calculated by summing the product of the typical price (average of the high, low, and close prices) and the volume for each candle in the specified period. This sum is then divided by the total volume for the period.

The calculation is performed in the `OnCalculate` function, which is called by MetaTrader 5 for each new candle. The VWAP values are stored in the `VWAPBuffer` array, which is used to plot the line on the chart.

## Product Description

The 'VWAP Volume And Price' indicator is a powerful tool for traders who use volume analysis in their trading strategy. It provides a visual representation of the average price weighted by volume, which can help identify significant price levels and potential reversal points.

Key Features:
- Calculates the Volume Weighted Average Price (VWAP) for a specified period.
- Works on any timeframe.
- Customizable period length.
- Displays the VWAP as a line on the chart.

To optimize your forex trading strategy with volume-weighted average price, consider using the 'VWAP Volume And Price' indicator. It can be used in conjunction with other technical indicators and price action analysis to make more informed trading decisions.

Please note that Forex Robot Easy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, visit [Forex Robot Easy - VWAP Volume And Price Review](https://forexroboteasy.com/forex-robot-review/vwap-volume-price-review-optimize-forex-with-volume-weighted-average/).
