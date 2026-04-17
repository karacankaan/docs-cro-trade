# Trade

The Trade page is where you buy and sell tokens. It combines a live chart, trade feed, token stats, and a swap interface into a single view.

## Opening a Trade Page

Navigate to a token's trade page by:

* Tapping a token card on the Explore page
* Tapping a token in your Watchlist or Wallet
* Searching for a token by name or address
* Navigating directly to `cro.trade/<token-address>`

## Chart

The trade page features a live candlestick chart powered by real-time data.

* **Multiple timeframes**: 1s, 5s, 15s, 1m, 5m, 15m, 1h, 4h, 1D, 1W
* **Drawing tools**: Trendlines, horizontal lines, and other drawing tools
* **Live candles**: The current candle updates in real-time as trades happen

## Token Stats

Below the chart, you'll see key token metrics:

* **Price** — current USD price
* **Market Cap** — total token value
* **Liquidity** — available liquidity in pools
* **24h Volume** — trading volume over the last day
* **Social links** — X, Telegram, Discord, and website links when available

## Buy & Sell

The swap panel lets you trade tokens directly:

1. **Select direction** — toggle between Buy and Sell
2. **Enter amount** — type the amount you want to trade, or use quick-select buttons (25%, 50%, 75%, 100%)
3. **Review** — see the estimated output, price impact, and route
4. **Confirm** — approve and execute the trade through your wallet

### Smart Routing

cro.trade finds the best price across multiple Cronos DEXes and routes your trade through the optimal path. Split routes across multiple DEXes are supported when it results in a better price.

### Fees

A **0.9% fee** is applied per trade. This fee is shared with CRONUS holders — by holding CRONUS, you benefit from the trading activity on the platform.

## Trade Feed

A real-time feed of all trades happening on the current token. Each entry shows:

* **Buy/Sell** indicator (green for buys, red for sells)
* **Amount** traded
* **USD value**
* **Trader address** — tap to view their profile
* **Time** — when the trade happened

The feed updates live as trades occur on-chain.

## Trade Detail

Tap any trade in the feed to see more details, including the exact amounts, token pair, and transaction link to the block explorer.
