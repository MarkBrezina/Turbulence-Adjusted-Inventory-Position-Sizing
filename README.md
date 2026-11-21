# Inventory and position sizing based on Market states for a simple "buy the dip strategy"


The simple idea here is that airplanes function in a somewhat similar manner with respect to turbulence.
Where speed is adjusted for turbulence and the plane does a tradeoff between speed and stability.
A similar tradeoff should be viable for any trading strategy. Such that you aren't left holding undesirable inventory.


Assumptions
### 1. Picking out a range of assets, for minute-to-minute data, from 2021 to 2026 if possible

10 Cryptocurrencies
BTC, ETH, XRP, SOL, TRX, ADA, LTC, ADA, DOGE, HYPE

5 Currencies
EURUSD, GBPJPY, AUDGBP, EURJPY, CADEUR,

5 Commodities
XAUUSD, XAGUSD, XCUUSD, XPDUSD, XPTUSD

25 Equities
MSFT, AAPL, ...

### 2. Using a simple strategy like:
Post limit orders at last low - 1%.  Position sizing based on market state
Post limit orders at last close + volatility adjusted price. With position sizing based on market state.


### 3. Learn appropriate market state volatility

### 4. Learn appropriate position sizing and volatility adjustments to the strategy based on volatility.





