# TA-API
This API gets buy/sell signals from TradingView indicators and automatically excuses orders on FTX, ByBit, and Binance exchanges.

A Flask app (Python) receiving alerts from TradingView and/or python engines and automatically sends a POST order to an integrated exchange API such as FTX, ByBit, and Binance. 

It can also deliver the alert and the chart to discord where you can decide whether or not to take that trade through a Discord bot.


