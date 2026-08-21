# Perps

Perpetual futures: leveraged long or short, no expiry, settled in **USDC**. The **Perps** tab opens them.

> Leverage cuts both ways and a position can be liquidated in full. Only risk what you can afford to lose. Eligibility and availability depend on where you are — see [Privacy & Terms](../privacy-and-terms.md).

## Markets

Five categories, each a tab in the market picker, plus a **Watchlist** tab for the ones you star: **Crypto**, **Stocks**, **Commodities**, **Indices** and **Forex**.

Every market card carries the price and 24h change, daily volume, the current funding rate, open interest, and the maximum leverage that market allows.

## Opening a position

Pick a market, then **Long** or **Short**, then an order type:

| Type | Behaviour |
| --- | --- |
| **Market** | Fills now at the best available price, within your slippage setting |
| **Limit** | Waits for your price or better |
| **Stop** | Becomes a market order once a trigger price is hit |

Set leverage on the slider. Every market sets its own ceiling and the slider stops there: **40x** on BTC, lower on most other crypto, up to **50x** on a couple of forex pairs. Then choose **Cross** or **Isolated** margin and enter a size in USD, or drag the slider as a percentage of buying power.

Two options before you submit. **Reduce Only** marks the order so it can only shrink or close an existing position rather than open a new one. **Take Profit / Stop Loss** attaches an automatic exit; it can close any portion of the position, set either by target price or by gain in % or $.

Submit and confirm. A toast reports the status and your entry price, and the position appears in your **Positions** list.

### Slippage on market orders

Presets at 0.1, 0.3, 0.5 and 1%, or a custom figure. Remembered between orders.

## Cross and isolated margin

Under **cross** margin your whole balance backs every position, which pushes any single liquidation further away but ties them together. Under **isolated**, a fixed amount of margin is committed to one position and only that amount is at risk.

Some markets support only one of the two. Where both are allowed, you switch in the order form.

## Funding

Perpetuals hold their price to the underlying with periodic funding payments between longs and shorts, roughly every eight hours. Positive funding means longs pay shorts; negative means the reverse. You only pay or receive it while a position is open, and the current rate is on every market.

## Liquidation

If losses eat through your margin, the position is closed for you. The estimated liquidation price is shown while you're sizing the trade and on the open position afterwards. Lower leverage moves it further away.

## Managing positions

The **Positions** view carries side, size, entry and mark price, unrealised PnL, funding, margin, leverage, liquidation price and ROE. Tap one to close it — fully or partially, at market or limit — adjust leverage, add or reduce margin on cross, or set and edit TP/SL. **Open Orders** and **Order History** sit alongside it.

## Charts

1m, 5m, 15m, 1h, 4h, 1d, 1w and 1mo, live, with an order book you can tap to fill in a price.

## Funding your account

Perps trade against a USDC balance. **Deposit** takes it from:

- **Cronos**, in CRO or USDC, converted for you
- **Arbitrum USDC**, directly
- **Another chain** — Ethereum, Base, Arbitrum, Optimism, Polygon, Avalanche or Cronos, described in [Adding USDC from another chain](../features/wallet.md#adding-usdc-from-another-chain)

Money usually lands within a few minutes.

**Withdraw** goes to **Cronos**, **Arbitrum** or **Solana** — pick the network, give it an address.

### Transfers between Perps and Predict

**Transfer** in the wallet panel moves USDC between your Perps and [Predict](../predict/README.md) balances. Pick a direction and confirm.

## Fees

A flat **0.06%** maker and taker, plus the funding payments above, which are exchanged between traders rather than charged by the platform. [Fees](../reference/fees.md) has the whole picture.
