---
layout: article
title: Indicator library
abstract: Everything you want to learn about the indicators
categories: misc
tags: indicator library
eyeCatcher: https://user-images.githubusercontent.com/16822689/176058647-cf23baaf-c979-4e13-947e-1305b90151d1.png
---

The library to list all the important public indicators uploaded to the platform (please expect weekly update).

## Daily Predictions

### SPY30Y
Here are the default indicators to project SPY's future using the history. Please use it after the market close. It is a close price to next day's close price's projection.

| Indicator name | Description  | Update Frequency |
| :---------------------------- | :--------------: | :----: |
| SMA50D_SPY   |   50D simple moving average (normalized)     |  Daily, after market close  |
| VIX_SPYLong  |   VIX index value  |  Daily, after market close  |
| HYG          |   iShares iBoxx $ High Yield Corporate Bond ETF    |  Daily, after market close  |
| NATR         |  A market volatility indicator: [link](https://www.investopedia.com/terms/a/atr.asp)  | Daily, after market close  |
| Volume       |   Volume compared to its 30D SMA   | Daily, after market close  |

### SPY30Y-Open
Here are the default indicators to project SPY's future using the history. Please use it after the market open. It is an open price to next day's open price's projection.

| Feature                       | Description  | Status |
| :---------------------------- | :--------------: | :----: |
| Volume_online  | Volume compared to its 30D SMA             | Daily, after market open      |
| NATR_online    | A market volatility indicator: [link](https://www.investopedia.com/terms/a/atr.asp)             | Daily, after market open     |
| CloseOpenSpread_online_SPY         | Open price compared to the last day's close price normalized by last day's close price              | Daily, after market open      |
| SMA50_online_SPY      | 50D simple moving average (normalized)          | Daily, after market open    |
| VIX_online_SPY                   | VIX index value             | Daily, after market open    |
| HYG_online_SPY   |  iShares iBoxx $ High Yield Corporate Bond ETF      | Daily, after market open   |

### Nasdaq
Here are the default indicators to project Nasdaq's future using the history. Please use it after the market open. It is a close price to next day's close price's projection. Please expect one day delay. It is used to project the long history of the indicator.

| Feature                       | Description  | Update Frequency |
| :---------------------------- | :--------------: | :----: |
| EFFR_20DSMA_NASDAQ         | A pulse when fed increase the interest rate, and there would be a decay after the pulse. Original data acquired from the fed: [Link](https://fred.stlouisfed.org/series/EFFR)          | Daily, one day delay      |
| SMA50D_Nasdaq    | Nasdaq index compared to its 50 days simple moving average  (normalized by the previous day's price)             | Daily, one day delay     |
| DFF_NASDAQ          |  Federal Funds Effective Rate: [Link](https://fred.stlouisfed.org/series/DFF)    | Daily, one day delay      |
| TB_3M_10Y_NASDAQ      | Spread between 10-Year Treasury Constant Maturity Minus 3-Month Treasury Constant Maturity: [Link](https://fred.stlouisfed.org/series/T10Y3M)       | Daily, one day delay      |
| SCPI_NASDAQ                   | Sticky Price Consumer Price Index (1 month offset): [Link](https://fred.stlouisfed.org/series/STICKCPIM157SFRBATL)   | Daily, one day delay      |
| FCPI_NASDAQ   | Flexible Price Consumer Price Index (1 month offset): [Link](https://fred.stlouisfed.org/series/FLEXCPIM679SFRBATL)     | Daily, one day delay      |
| M0_YoY | Monetary Base; Total: [Link](https://fred.stlouisfed.org/series/BOGMBASE)    |   Daily, one day delay    |

## More indicators
Coming soon, the fastest way is google the short description we wrote in the S-creator.

## Roadmap
1. Support hourly update of crypto currency.
2. Comprehensively analysis indicator's performance.
3. More powerful stop loss indicators.

## Check indicators in S-ensembler
[Link](https://armadillo-5lx7id43eq-uc.a.run.app/)