# Prop Masters EA

This is the code for the Prop Masters EA, a trading expert advisor developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in the product.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/prop-masters-ea-review-high-win-ratio-forex-software/).

## Overview

The Prop Masters EA is designed to automate trading on the MetaTrader 5 platform. It includes input parameters for risk percentage and stop loss in pips. The EA calculates the lot size based on the risk percentage and opens trades according to specified conditions.

## Input Parameters

- RiskPercentage: Percentage of risk per trade (default: 2)
- StopLossPips: Stop loss in pips (default: 20)

## Initialization and Deinitialization

The EA has an initialization function (`OnInit`) and a deinitialization function (`OnDeinit`) where initialization and deinitialization code can be added, respectively.

## Trading Logic

The main trading logic is implemented in the `OnTick` function. It calls the `CalculateLotSize` function to determine the lot size based on the risk percentage. If the `ShouldOpenTrade` function returns true, the EA opens a trade with the specified lot size using the `OpenTrade` function.

## Additional Functions

- `CalculateLotSize`: Calculates the lot size based on the risk percentage, account balance, stop loss in pips, and tick value.
- `ShouldOpenTrade`: Checks if a trade should be opened based on specified conditions.
- `OpenTrade`: Opens a trade with the specified lot size.
- `NormalizeDouble`: Normalizes a double value to the specified number of decimal places.

Please note that this code is a sample and may need to be customized or modified according to your specific trading strategy or requirements.

For the official developer of this product, please refer to the MQL5 website.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/prop-masters-ea-review-high-win-ratio-forex-software/).
