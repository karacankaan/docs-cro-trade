# Predict

**Predict** is cro.trade's prediction markets. You trade shares on the outcome of real-world events — sports, crypto, economy, and politics — and cash out when you're right.

Open the **Predict** tab in the navigation bar.

## How Prediction Markets Work

Each market has outcomes you can buy shares in (most commonly **YES** or **NO**):

* A share **price is its probability** — a YES price of $0.62 means the market thinks there's about a 62% chance
* You pay the share price to buy; if your outcome wins, each share is worth **$1**, and if it loses it's worth **$0**
* You don't have to wait for the result — you can sell your shares back at the current market price any time

So your potential payout is your number of shares × $1, and your profit is that payout minus what you paid.

## Categories

Markets are organized into categories you can tab between:

* **Trending** — the highest-volume markets across everything
* **Crypto** — Bitcoin, Ethereum, and altcoin price markets, with its own hub (below)
* **Football** — soccer, with its own hub (below)
* **Sports** — basketball, American football, hockey, baseball, MMA, golf, F1, and more (30+ leagues). See [Sports & Live Scores](sports.md)
* **Economy** — Fed rates, inflation, GDP, trade, housing, and other macro topics
* **Politics** — elections and political events

You can search markets by name and sort by trending, volume, liquidity, newest, or ending soon.

### Football Hub

The **Football** category is soccer, and it has its own layout with three tabs:

* **Matches** — live games first, then upcoming by kick-off time
* **Questions** — season-long and prop markets, sorted by volume
* **Ended** — games from the last few days

### Crypto Hub

The **Crypto** category groups markets by how long they run, so short-duration "Up or Down" markets don't get buried under season-long ones. Filter by **All**, **5 Min**, **15 Min**, **1 Hour**, **4 Hours**, **Daily**, **Weekly**, **Monthly**, **Yearly**, **Pre-Market**, or **ETF**.

## Placing a Trade

1. Open a market to see its outcomes, current prices, order book, and recent activity
2. Choose your **outcome** (e.g. YES or NO; for some sports markets, Home / Draw / Away)
3. Choose an **order type**:
   * **Market** — buy immediately at the best available price
   * **Limit** — set the price you're willing to pay and wait for a fill
4. Enter an amount in **USD**
5. Review the calculation — shares received, cost, and max payout if you win
6. Confirm (on mobile, swipe to confirm; on desktop, tap submit)

The minimum order is **$1**.

## Managing Your Positions

Your open and closed positions appear in your Predict positions view. Each position shows its current value, unrealized P&L, and max payout.

* **Close** — sell an open position back to the market at the current price (you may get more or less than you paid, depending on how the odds have moved)
* **Redeem** — once a market resolves in your favor, redeem your winning shares for $1 each

## Resolution & Payouts

When the real-world event concludes, the market resolves to its actual outcome. Winning shares become redeemable for $1 each; losing shares are worth $0. Redeeming credits USDC to your Predict balance.

## Funding Predict

Predict markets settle in **USDC**. Open the deposit panel and fund your Predict balance from:

* **Arbitrum USDC** — the most direct route
* **Cronos** (CRO or USDC) — converted to USDC automatically
* **From another chain** — bring native USDC across from **Ethereum, Base, Arbitrum, Optimism, Polygon, Avalanche, or Cronos** (see [Adding USDC from Another Chain](../features/wallet.md#adding-usdc-from-another-chain))
* **From your Perps balance** — moved over in-app

### Withdrawing

Open the withdraw panel, pick where the USDC should land, and enter the destination address. Predict withdrawals can go to:

* **Cronos**
* **Arbitrum**
* **Base**
* **Polygon**
* **Solana**

You can also move funds between Perps and Predict using [internal transfers](../perps/README.md#internal-transfers-perps-↔-predict).

## Price Alerts

You can set a price alert on a market to be notified when it crosses a target probability. See [Notifications](../account/notifications.md).
