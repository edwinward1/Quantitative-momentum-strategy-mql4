# Quantitative-momentum-strategy-mql4
This is a quantitative momentum-based expert advisor that uses the MQL4 language, so is intended to be run on the MetaTrader4 platform. It uses key quantitative metrics obtained from real-time price data to automatically identify and execute statistical arbitrage opportunities for the major currency pairs. It has been tested extensively on over 10 years of raw price data and in real-time.

This EA was created and is intended for use on the major currency pairs only, and should not be used to place trades on minor or exotic currencies with low liquidity.

It makes use of a conservative but robust position sizing and risk-management framework to minimise volatility exposure, and in turn drawdown.

For any further questions please contact me at: edwinward1@icloud.com

NOTE: I highly recommend this expert advisor to be used in conjunction with the EuroCurrency Volatility Index ($EVZ) found here: https://www.barchart.com/stocks/quotes/$EVZ 
The expert advisor should not run unless there is sufficient market volatility to allow for prices to trend effectively. The recommended minimum $EVZ level is 6.0.
