## Windfaller AI - Your own family office

WindfallerAI is an automated algorithmic trading system using Consensus-Based Artificial Intelligence and Classical Calculus for Financial Market Analysis and Data Mapping Techniques.

Windfaller handles a World State, considering candles in multiple periodicities (intervals ranging from 1m, 3m...1d, 1Y,...) for numerous markets.     
It performs multiple analysis and strategies on those specific intervals, qualify the market's interval into simple -100;100 temperature, simulates some "classical" traders' behavioral models (permabull, swing, scalper etc.), and additional sentiment/news analysis.  
Assets have the same treatment, except they are considered in their multi-dimensional components (markets and their intervals).    

A Consensus-Based Quorum is then performed upon each candle's extended information. 
As such, a set of different "Oracle" takes as inputs all that information (containing trends, candle patterns, resistance/support level etc.) and presents them to the different models.    
A final consensus is made on markets. 

This consensus is then relayed to the different "Trader" systems that each has under management a single Identity and its financial set (exchanges, assets, positions etc.). 

In short, It manages your assets while you are sleeping.  

Contact me: 
- Closed beta: We will use Bybit so you can always keep control on your funds. Contact us, if you want to have access. - obusco+windfallerai@gmail.com
- Funding Round: Let's work together to get all the legal done so we open it up for more than just crypto ! - obusco+windfallerai@gmail.com

Currently implemented features (~ meaning currently only available in alpha version) : 

- [X] Pricing system (monitors trades from various exchanges: Crypto, Stocks, Commodities, Forex,... and form candles)
- [X] Extend candles with various strategy analysis
   - [X] Volume Strategies (Breakout, Accumulation, OBV/Trend, Money Flow, crossing, pivots and classic VWMA)
   - [X] BB Strategies (Breakout, Squeeze, DblTop/Bottom)
   - [X] RSI & MACD (Divergence, WRSI,...)
   - [X] Connors Strategies
   - [X] Pivots Strategies
   - [X] Direct Price (h/l, open/close, support & resistance, all-time high/low, hull price,...)
 - [~] Extend candles with pattern analysis
   - [X] Conventional candle pattern matching.
   - [~] Swing Cycle
- Connectors
   - [X] RWA Ready (housing, art,...), easy plug to any "price outputting system."
- [~] Fund & Risk Management
   - [X] Coherent identity system taking multiple exchanges into consideration (including price arbitrage)
   - [X] Trade management (SL and TP and standard risk management and exit strategy)
   - [~] Support allowing trade management to also handle trade created by the user instead of the bot (Fire & Forget feature)   
- [~] Production-ready (currently live with my funds). 

Current: 
- Simulator: Simulate some trader's typology, trying to "reason" as some bots, permabull, permabear, retails. And output an "advice" (BUY/SELL/ACCUMULATE...).
- Post-Analysis: Adding meta-information across the market states (news, events, inter-market interaction,...), we "colorize" market intervals, markets, and assets into a standard -100;100 range.  
- Oracle: Those pieces of information go as input to a quorum of multiple oracle (AI system) that are trained to correct themselves on the advice vs. result.

Next: 
- Better Order Decision Making: information is emitted across the system, as such as the system propagates some "advice" that is then to be taken by an individual module that can perform that by taking into account the specificity of the assets under management (at Identity level).
- Social Agent : Qualifying social aspect into our extended set.
- Fractals analysis
- Improved Orderbook usage in the system and arbitrage opportunity management.
