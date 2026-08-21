# Trade

The Trade page is where you buy and sell Cronos tokens. It combines a live chart, token stats, a swap interface, and a real-time trade feed in a single view.

## Opening a Trade Page

Open a token's trade page by:

* Tapping a token card on Explore, your Watchlist, or your portfolio
* Searching for a token by name or address
* Navigating directly to `cro.trade/<token-address>`

## Chart

A live candlestick chart powered by TradingView and real-time data.

* **Many timeframes** — 1s, 5s, 15s, 1m, 5m, 15m, 1h, 4h, **1D**, and **1W**
* **Live candles** — the current candle updates in real-time as trades happen
* **Maker filter** — isolate an individual trader's buys/sells on the chart
* Your selected timeframe is remembered for next time

## Token Stats

Around the chart you'll see key metrics:

* **Price** — current USD price (tiny prices use compact subscript notation)
* **Price change** — for the selected timeframe
* **Market Cap**
* **Liquidity** — available liquidity in pools
* **Volume** — for 5m / 1h / 6h / 24h, with the buy vs sell split and trade counts
* **Age** and **holder count** when available

## Buy & Sell

The swap panel lets you trade directly:

1. **Select direction** — toggle between Buy and Sell
2. **Choose payment token** — pay with **CRO**, **USDC**, or **USDT**
3. **Enter amount** — type it, or use the quick-amount buttons
4. **Review** — see the estimated output (already net of the routing fee)
5. **Confirm** — sign once in your wallet

### One Signature, Often No Gas

When you pay with **USDC or USDT**, the approval and the swap go through together as a single sponsored transaction: you sign once, and you need **no CRO at all** — the routing fee covers the gas.

Paying with **CRO** you pay the network gas yourself, as normal. And if your wallet doesn't support the batched route, cro.trade falls back to the older approve-then-swap, which needs CRO for both steps.

### Smart Routing

cro.trade checks prices across multiple Cronos DEXes and bonding curves and routes your trade through the best path automatically.

### Slippage

Slippage defaults to **0.5%**. Presets are **0.5%, 1%, 2%, and 5%**, or you can enter a custom tolerance — your choice is remembered for future trades.

Beside the slippage control is a **MEV risk** badge — Low, Med, High, or Extreme — based on the pool's liquidity for the size you're trading. cro.trade also works out how much slippage the pool actually needs, and warns you when your setting is far above it, since the surplus is what a sandwich attack has to take.

### Gas

Choose how much you pay for on-chain speed: **Saver**, **Standard**, or **Instant**. It defaults to Instant, and your choice is remembered.

### Fees

A **0.9% routing fee** is applied per trade — see [Fees](../reference/fees.md) and [Rewards](../rewards/README.md).

## Token Info

Open the token info panel for a deeper look:

* **Overview** — price, market cap, liquidity, age
* **Supply & holders** — total/circulating supply and holder count
* **On-chain details** — token address (copyable), creator/dev address, and any fee-on-transfer tax
* **Security** — a real-time risk check showing the number of detected risks
* **Socials & links** — X, Telegram, Discord, and website
* **Creator's other tokens** — other tokens launched by the same deployer
* **Price performance** — all-time high/low and period high/low

## Trade Feed

A real-time feed of all trades on the current token. Each entry shows:

* **Buy/Sell** indicator (green for buys, red for sells)
* **Amount** and **USD value**
* **Trader** — tap their avatar to view their profile
* **Time**

Tap a maker to filter the feed (and chart marks) to just their trades.

## Holdings & Holders

* **Holdings** — tokens you currently hold, with balance, value, and P&L
* **Holders** — the token's top holders and their share of supply

## Amounts & Direction

Trade amounts are always shown as positive values; the buy/sell indicator tells you the direction. The token's logo and links are derived from its on-chain address.
