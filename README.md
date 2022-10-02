# CISE-Telegram-Crypto-Screener

Code implementation for running automated crypto screener on hourly charts.
Live channel can be found here: https://t.me/CPR_EMA200_STC

![image](https://user-images.githubusercontent.com/106367095/192753705-1eac5447-e62a-42dc-837b-30dee87ba3f4.png)


# What is CISE Screener?

The CISE bot is a technical indicator that scans all the cryptocurrency futures Coin-M asset pairs hourly to find the pairs matching the technical conditions provided by the cise algorithm. 

> [CISE Both Analysis Algorithm](https://jovian.ai/ranton95/test)

The complete algorithm used on the deployed CISE bot can be found in this report. The separate study and analysis for each indicators that combines together to form the CISE screener are of the following:


**1. Central Pivot Range (CPR):** Central Pivot Range (CPR) indicator is used to identify key points of price levels and trade accordingly. Traders can take up trading positions based on the different levels on the chart. It is quite popular among traders as it is quite versatile and simple to understand. 

> [CPR Scanner for Binance & OKEX Exchange](https://jovian.ai/ranton95/cpr-okex)

**2. Initial Balance (IB):** Initial Balance (IB) is the price data, which are formed during the first hour of a trading session. Activity of traders forms the so-called Initial Balance at this time. The market profile shows traders horizontal volumes, that is how many contracts or stocks were sold or bought at each price level. 

Initial Balance can give a trader many hints in respect of how the trading session would develop. It sets the tone of the trading session. It often happens that activity and volumes of trades during the first hour have the bigger significance than during the following hours. 

> [Initial Balance Analysis](https://jovian.ai/ranton95/ib-multiple-exchange)

> [Initial Balance Dashboard](https://deepnote.com/@royce-anton-jose-dashboard/Initial-Balance-IB-Binance-Asset-Screener-176469cf-0ddd-4538-a034-712b2593061a)


**3. The Schaff Trend Cycle (STC)** is a charting indicator that is commonly used to identify market trends and provide buy and sell signals to traders. Developed in 1999 by noted currency trader Doug Schaff, STC is a type of oscillator and is based on the assumption that, regardless of time frame, currency trends accelerate and decelerate in cyclical patterns.

> [STC Indicator Visualization](https://jovian.ai/ranton95/stc-indicator)


**4. Exponential Moving Average (EMA-200):**

An exponential moving average (EMA) is a type of moving average (MA) that places a greater weight and significance on the most recent data points. The exponential moving average is also referred to as the exponentially weighted moving average. An exponentially weighted moving average reacts more significantly to recent price changes than a simple moving average simple moving average (SMA), which applies an equal weight to all observations in the period. In general, the 50- and 200-day EMAs are used as indicators for long-term trends. When a stock price crosses its 200-day moving average, it is a technical signal that a reversal has occurred. CISE bot uses the 200 period EMA for screening.

> [Analysis on EMA-200 for BTC](https://jovian.ai/ranton95/200-ema-screener)
