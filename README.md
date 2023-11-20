# Channel Scanner

Channel Scanner is an expert advisor (EA) developed by Forex Robot Easy Team that scans multiple currency pairs and timeframes to identify potential trading opportunities. It provides clear entry and exit points for trading based on predefined parameters, and allows setting stop-loss and take-profit levels. This ReadMe file provides an overview of the code and its functionality.

## Installation
To use Channel Scanner, follow these steps:
1. Download and install the [Trade.mqh](https://www.mql5.com/en/code/11553) library.
2. Copy the Channel Scanner.mq5 file into the 'Experts' folder of your MetaTrader terminal.
3. Restart the MetaTrader terminal.
4. Open the MetaEditor and compile the Channel Scanner.mq5 file.

## Input Parameters
The EA has the following input parameters:
- ScanPeriod: The period for scanning (default: 20).
- StopLossPips: The stop loss in pips (default: 50).
- TakeProfitPips: The take profit in pips (default: 100).

## Functionality
The EA performs market analysis by scanning multiple currency pairs and timeframes. It iterates through all available symbols and timeframes, and performs analysis based on the predefined parameters. The following steps are executed for each symbol and timeframe combination:

1. Get the high, low, and close prices.
2. Identify potential trading opportunities based on custom logic (example: if the close price is greater than the high price).
3. Set the stop-loss and take-profit levels.

## Custom Functions
The EA provides the following custom functions:

### `BuySignal()`
This function is responsible for generating the buy signal based on custom logic. Modify this function according to your trading strategy.

### `SetStopLoss(double stopLoss)`
This function sets the stop-loss level for the current trade. The `stopLoss` parameter should be provided in the base currency.

### `SetTakeProfit(double takeProfit)`
This function sets the take-profit level for the current trade. The `takeProfit` parameter should be provided in the base currency.

## Note
Forex Robot Easy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, use the MQL5 website.

For detailed reviews and trading results of this product, visit [Forex Robot Easy - Channel Scanner Review](https://forexroboteasy.com/forex-robot-review/channel-scanner-review-real-results-with-only-3-left-at-30/).
