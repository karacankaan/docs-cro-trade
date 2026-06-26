# Perps Overview

**Perps** (perpetual futures) let you trade with leverage — going long (betting the price rises) or short (betting it falls) — without an expiry date. Perps on cro.trade settle in **USDC**.

Open the **Perps** tab in the navigation bar to get started.

## Available Markets

Perps cover four market categories:

* **Crypto** — Bitcoin, Ethereum, and many other coins
* **Stocks** — major US companies
* **Commodities** — gold, oil, and more
* **Forex / Indices** — currency pairs and index products

Each market card shows the current price and 24h change, daily **volume**, the current **funding rate**, **open interest**, and the maximum leverage available.

## Opening a Position

1. Open the **Perps** tab and tap a market (e.g. BTC)
2. Choose **Long** (price up) or **Short** (price down)
3. Pick an **order type**:
   * **Market** — fills immediately at the best available price
   * **Limit** — fills only at your chosen price or better
   * **Stop** — triggers a market order when the price hits your level (useful to cut losses)
4. Set your **leverage** with the slider (up to **50x**, depending on the market)
5. Choose your **margin mode** — Cross or Isolated (see below)
6. Enter your **size** in USD (or use the size slider as a % of your buying power)
7. Optionally enable **Reduce Only** and **Take Profit / Stop Loss**
8. Tap **Long** / **Short** to submit, then confirm

A toast notification shows the order status and your entry price. Filled positions appear in your **Positions** list.

## Order Types & Options

| Option | What it does |
| --- | --- |
| **Market** | Instant fill at the best price (with a slippage setting) |
| **Limit** | Waits for your price; you control entry |
| **Stop** | Becomes a market order when a trigger price is hit |
| **Reduce Only** | Only reduces/closes an existing position — never opens a new one |
| **Take Profit (TP)** | Auto-exits at a profit target |
| **Stop Loss (SL)** | Auto-exits to limit losses |

TP/SL can close a partial amount (25/50/75/100%) and can be set by target price or by gain in % or $.

### Slippage (market orders)

Market orders use a slippage setting with presets (e.g. 0.1%, 0.3%, 0.5%, 1%) or a custom value. Your choice is remembered.

## Margin: Cross vs Isolated

* **Cross margin** — your whole balance backs all positions, lowering liquidation risk for any single one
* **Isolated margin** — a fixed amount of margin is dedicated to one position; only that margin is at risk

Some markets only support one mode. You can switch modes in the order form where allowed.

## Funding Rates

Perpetuals use periodic **funding payments** between longs and shorts (roughly every 8 hours):

* **Positive** funding: longs pay shorts
* **Negative** funding: shorts pay longs

You only pay or receive funding while holding a position. The current rate is shown on every market.

## Liquidation

If your losses eat through your margin, your position is liquidated (automatically closed). The estimated **liquidation price** is shown as you size a trade and on every open position. Lower leverage moves the liquidation price further away.

## Managing Positions

Open the **Positions** view to see each position's side, size, entry and mark price, unrealized PnL, funding, margin, leverage, liquidation price, and ROE. Tap a position to:

* **Close** — fully or partially, at market or limit
* **Adjust leverage**
* **Add or reduce margin** (cross)
* **Set or edit TP/SL**

You can also review **Open Orders** and **Order History**.

## Funding Your Perps Account

Perps trade in USDC held in your Perps account. To add funds, open the wallet panel and choose **Deposit**:

* **From Cronos (CRO or USDC)** — converted to USDC automatically
* **From Arbitrum USDC** — a direct deposit

Funds typically arrive within a few minutes. To take funds out, use **Withdraw** and choose your destination.

### Internal Transfers (Perps ↔ Predict)

You can move USDC between your Perps and [Predict](../predict/README.md) balances in-app. Open the wallet panel, choose **Transfer**, pick the direction, and confirm.

## Charts

Perps charts support standard timeframes (1m, 5m, 15m, 1h, 4h, 1d, 1w, 1mo) with live price updates and an order book you can tap to set a price.

## Fees

Perps use a flat **0.06%** maker/taker fee, plus periodic funding payments between longs and shorts. See [Fees](../reference/fees.md) for the full breakdown.

> **Risk note:** Leverage amplifies both gains and losses, and positions can be fully liquidated. Trade with care and only risk what you can afford to lose.
