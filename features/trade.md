# Trade

One page per token: chart, stats, the swap panel, and every trade as it lands.

Get there by tapping a token anywhere in the app, searching for it, or going straight to `cro.trade/<token-address>`.

## Chart

A TradingView candlestick chart on live data. Timeframes run 1s, 5s, 15s, 1m, 5m, 15m, 1h, 4h, 1D, 1W, and the one you pick is remembered. The open candle moves as trades happen.

The **maker filter** isolates one trader's buys and sells on the chart, which is the fastest way to see what a wallet has actually been doing.

## Stats

Price in USD (tiny numbers use compact subscript rather than exponents), the change over your selected timeframe, market cap, pool liquidity, and volume for 5m / 1h / 6h / 24h split buy against sell with trade counts. Age and holder count show where they're known.

## Buying and selling

Pick a direction, pay with **CRO** or **USDC**, enter an amount or hit a quick-amount button. The estimate you see is already net of the routing fee. Then sign.

### One signature, often no gas

Paying with **USDC**, the approval and the swap go through as a single sponsored transaction: one signature, and **no CRO needed at all** — the routing fee covers the gas.

Paying with **CRO**, you pay the network gas yourself. If your wallet can't do the batched route, cro.trade falls back to the older approve-then-swap, which needs CRO for both steps.

### Routing

The router quotes across every Cronos DEX and bonding curve and takes the best path. You don't choose a venue.

### Slippage

Defaults to **0.5%**, with presets at 0.5, 1, 2 and 5%, or a custom figure. Your setting is remembered.

Next to it sits a **MEV risk** badge — Low, Med, High or Extreme — worked out from the pool's liquidity against the size you're trading. cro.trade also calculates how much slippage the pool actually needs and warns you when your setting sits far above it: that surplus is exactly what a sandwich attack has to take.

### Gas

**Saver**, **Standard** or **Instant**, defaulting to Instant. Remembered between trades.

### Fee

**0.9%** per trade, built into the quote. See [Fees](../reference/fees.md) and [Rewards](../rewards/README.md).

## Token info

The info panel goes deeper: total and circulating supply, holder count, the token and deployer addresses, any fee-on-transfer tax, a live risk check with the number of issues found, socials, other tokens the same deployer has launched, and all-time and period highs and lows.

## Trade feed

Every trade on the token as it happens — direction, amount, USD value, trader and time, green for buys and red for sells. Tap a trader's avatar for their [profile](profiles.md), or tap the maker to filter both the feed and the chart marks down to that one wallet.

Amounts are always positive; the buy/sell marker carries the direction.

## Holdings and holders

**Holdings** is your own position in the token with balance, value and P&L. **Holders** ranks the token's largest holders by share of supply.
