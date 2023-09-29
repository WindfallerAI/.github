## Hi there 👋

WindfallerAI is an automated algorithmic trading system using Consensus-Based Artificial Intelligence and Classical Calculus for Financial Market Analysis and Data Mapping Techniques.

Windfaller handles a World State, considering candles in multiple periodicities (intervals ranging from 1m, 3m...1d, 1Y,...) for numerous markets.     
It performs multiple analysis and strategies on those specific intervals, qualify the market's interval into simple -100;100 temperature, simulates some "classical" traders' behavioral models (permabull, swing, scalper etc.), and additional sentiment/news analysis.  
Assets have the same treatment, except they are considered in their multi-dimensional components (markets and their intervals).    

A Consensus-Based Quorum is then performed upon each candle's extended information. 
As such, a set of different "Oracle" takes as inputs all that information (containing trends, candle patterns, resistance/support level etc.) and presents them to the different models.    
A final consensus is made on markets. 

This consensus is then relayed to the different "Trader" systems that each has under management a single Identity and its financial set (exchanges, assets, positions etc.). 


In short, It manages your assets while you are sleeping.  

Contact me: obusco+windfallerai@gmail.com ; fund us, and let's deal with all the regulatory licensing steps and open it up for 20$ a month :D



Features: 
- [X] RWA Ready
- [X] Can management on Stocks, Forex, Crypto
- [X] Can monitor Commodities
- [~] Production-ready (currently in testing on my personal funds). 

- CandleMaker: A plug-and-play system, plug to exchange (centralized, on-chain, etc...) and transform data into a standardized set of Candle (OHLCV), Ticker, and order book. 
- Dow: Our modules take candles as input and perform hundreds of indicator computations (RSI, BB, MACD) and strategies on top of that (Breakout-and-test, pattern, fractals, etc...).
- Agent: This qualifies the sentiments from those data. 
- Post-Analysis: Adding meta-information across the market states (news, events, inter-market interaction,...), we "colorize" market intervals, markets, and assets into a standard -100;100 range.  
- Simulator: Simulate some trader's typology, trying to "reason" as some bots, permabull, permabear, retails. And output an "advice" (BUY/SELL/ACCUMULATE...).
- Oracle: Those pieces of information goes as input to a quorum of multiple oracle (AI system) that are trained to correct themselves on the advice vs. result.
- Order Decision Making: All this information is emitted across the system, as such as the system propagates some "advice" that is then to be taken by an individual module that can perform that by taking into account the specificity of the assets under management (at Identity level).
- Trade management: System that continuously monitors the market and provides new advice from the system (TP/SL/ Exit management). 
