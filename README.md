# Fair Value Gaps Indicator

This code represents the Fair Value Gaps indicator which is used to identify discrepancies between buying and selling in the forex market. This indicator is developed by the Forex Robot Easy Team and can be found on forexroboteasy.com. Please note that ForexRobotEasy is not the official developer of this product, but we provide a sample code that can work as described in this indicator.

## Indicator Description

The Fair Value Gaps indicator calculates price gaps based on liquidity voids and displays them on the chart. It identifies situations where liquidity is up for offers and checks for liquidity voids on lower time frame charts. If a range of less than 10 pips is detected, a trading vacuum is created, resulting in an actual price gap. The indicator then identifies discrepancies between buying and selling and displays the Fair Value Gaps on the chart.

## Indicator Initialization

The indicator initialization function, `OnInit()`, is responsible for setting up the indicator buffers, sorting type, index label, and index style.

## Indicator Calculation

The indicator calculation function, `OnCalculate()`, is called for each new tick and performs the calculation of Fair Value Gaps. It iterates through the price data and checks for conditions that indicate liquidity up for offers and liquidity voids. If a price gap is detected, it is recorded in the indicator buffer for display on the chart.

## Usage

To use this indicator, simply add it to your MetaTrader 5 platform and apply it to the desired chart. The Fair Value Gaps will be displayed as lines on the chart, indicating discrepancies between buying and selling.

## Product Description

Fair Value Gaps is a powerful forex indicator developed by the Forex Robot Easy Team. It helps traders identify discrepancies between buying and selling in the forex market, providing valuable insights into market dynamics. By detecting liquidity voids and creating trading vacuums, this indicator can help traders spot potential price gaps and make informed trading decisions.

With Fair Value Gaps, traders can gain a deeper understanding of market liquidity and identify opportunities for profit. The indicator's clear and easy-to-read display on the chart allows for quick analysis and decision-making. Whether you are a beginner or an experienced trader, Fair Value Gaps can enhance your trading strategy and improve your trading results.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/fair-value-gaps-unbiased-review-of-forex-software-efficiency/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.
