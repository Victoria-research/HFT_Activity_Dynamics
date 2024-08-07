# HFT_Activity_Dynamics


## Introduction:
High-Frequency Trading (HFT) is algorithmic trading that uses special computers to either execute large orders at the best possible price or to seek small trading opportunities in the market. 

High-Frequency Trading (HFT) industry currently represents 55 percent of the trading volume in the US equity market. It has experienced an average annual growth rate of 2.9 percent between 2017 and 2022. On May 6, the U.S. financial markets underwent a 'Flash Crash', witnessing a sudden and substantial drop in stock prices resulting in a nearly trillion-dollar loss within minutes. Several critics from the U.S. financial system and market note that although HFT was not the sole cause, the automated execution of trades and rapid algorithmic trading significantly contributed to the market instability.

Understanding the market dynamics of HFT activity will provide insights into its influence on the trading landscape for both large-cap and small-cap stocks.

## Methodology
1. Utilize daily ITCH data from 200 NASDAQ-listed stocks, comprising 100 large-cap stocks (Nasdaq100) and 100 small-cap stocks. Analysis will rely on one daily measurement for each month of
 the year spanning from 2018 to 2023
2. Employ a combination of linear regression, correlation tests, and unconditional moments to assess any disparity in HFT activity between Nasdaq100 and SmallCap Stocks
3. Unconditional moments will calculate the average percentages of HFT activity for each year across the cumulative stocks for Nasdaq100 and SmallCap
4. Linear regression will assess variations in how stock volatility and liquidity affect the activity of High-Frequency Trading (HFT) in both Nasdaq100 and SmallCap stocks
5. Stock volatility will be measured utilizing stock returns, whereas stock liquidity will be assessed through share turnover
6. HFT activity will be quantified using metrics such as the HFT cancellation-to-execution ratio, HFT Share of Trades, HFT Volume Share, Hidden Share of Trades and Hidden Share of Volume
7. The regression model; HFT Activity t = β0 + β1 Volatility t−1 + β2 Liquidity t−1 + ϵ1
