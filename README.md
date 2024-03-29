# TMA and CG Indicator by McSudov - ReadMe

## Description
This code represents the TMA and CG Indicator, developed by McSudov. The indicator is designed to provide precise forex signals based on the TMA (Triangular Moving Average) and CG (Center of Gravity) calculations. 

The TMA is calculated using a specified period and deviation value, with the option to choose the applied price for the calculation. The CG is also calculated using the same period and deviation values. 

The indicator generates signals when the price crosses the TMA channel. When the price exits above the TMA channel, an arrow is displayed above the candle, indicating a potential buy signal. Conversely, when the price exits below the TMA channel, an arrow is displayed below the candle, indicating a potential sell signal.

## Indicator Parameters
- **period**: The period for TMA calculation.
- **deviation**: The deviation value for TMA channel.
- **applied_price**: The applied price for TMA calculation.

## Indicator Buffers
- **tmaBuffer[]**: Stores the TMA values.
- **cgBuffer[]**: Stores the CG values.

## Initialization
The indicator buffers are mapped and labeled accordingly. The line styles and colors are set for the TMA and CG lines. The indicator buffers are initialized with empty values.

## Calculation
The TMA and CG values are calculated for each bar in the specified period. The TMA and CG calculations are performed using the iCustom function. 

The signals are generated by comparing the current and previous bar's closing prices with the TMA values. If the price exits above the TMA channel, the CG values are adjusted to display arrows above the candles. If the price exits below the TMA channel, the CG values are adjusted to display arrows below the candles.

## Usage
To use this indicator, follow these steps:
1. Copy the code into your MQL5 editor.
2. Compile the code.
3. Apply the indicator to your chart.
4. Adjust the desired parameters (period, deviation, applied price).
5. Interpret the signals generated by the indicator.

## Disclaimer
Forex Robot Easy is not the official developer of this product. We only provide a sample code that can work as described in this product. For detailed reviews and trading results of this product, please visit [https://forexroboteasy.com/forex-robot-review/tma-cg-indicator-review-precise-forex-signals-by-mcsudov/](https://forexroboteasy.com/forex-robot-review/tma-cg-indicator-review-precise-forex-signals-by-mcsudov/). To find the official developer of this product, please refer to MQL5.
