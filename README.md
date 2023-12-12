# Moving Average Cross Price Alert MT5

This code is a custom indicator for MetaTrader 5 (MT5) that generates alerts when a moving average crossover occurs. The indicator calculates the moving averages based on the specified input parameters and checks for crossover conditions. When a crossover occurs, an alert is generated and sent.

## Developer

This code was developed by the Forex Robot Easy Team. For more information about the developer and their other products, visit their website: [forexroboteasy.com](https://forexroboteasy.com)

## Libraries Used

The code includes several necessary libraries for the indicator to function correctly. These libraries provide functions and classes for trading, chart objects, indicators, and alerts. The libraries used are:

- Trade.mqh
- ChartObjects.mqh
- MA.mqh
- Alert.mqh

## Input Parameters

The code defines several input parameters that can be customized by the user. These parameters control the period of the moving averages, the type of moving average, and the minimum number of consecutive bars for a crossover. The input parameters are:

- ShortMA_Period: Period of the shorter-term moving average (default: 10)
- LongMA_Period: Period of the longer-term moving average (default: 20)
- MA_Method: Type of moving average (default: Simple Moving Average)
- MinConsecutiveBars: Minimum number of consecutive bars for a crossover (default: 3)

## Global Variables

The code defines several global variables that are used throughout the indicator. These variables include:

- trade: Trade object for executing trades
- alert: Alert object for generating alerts
- prev_cross: Previous crossover value
- consecutive_bars: Number of consecutive bars for a crossover
- ShortMA: Short-term moving average object
- LongMA: Long-term moving average object
- text: Chart object for displaying moving averages on the chart
- alert_message: Alert message for crossover events
- error: Flag for error handling
- error_message: Error message for error handling

## Functions

The code defines several functions that are used for calculating and displaying moving averages, checking for moving average crossovers, and handling events. These functions include:

- CalculateMovingAverages(): Calculates and displays the moving averages on the chart.
- CheckMovingAverageCrossover(): Checks for moving average crossovers and generates alerts.
- OnTick(): Event handler for the OnTick event.
- OnInit(): Event handler for the OnInit event.
- OnDeinit(): Event handler for the OnDeinit event.
- OnError(): Event handler for the OnError event.
- OnStart(): Main program entry point.

## Usage

To use this indicator, simply add it to a chart in MetaTrader 5 and customize the input parameters as desired. The indicator will calculate and display the moving averages on the chart, and generate alerts when a crossover occurs.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/moving-average-cross-price-alert-mt5-review-and-download-the-candle-stick-patterns-finder-for-professional-forex-traders/).
