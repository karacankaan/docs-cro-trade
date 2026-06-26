# Fees

A summary of the fees you'll encounter across cro.trade. Fees differ by market type.

## Spot Trading (Cronos)

* **Trading fee: 0.9%** per trade, built into your quote
* You also pay the underlying network gas and any DEX/pool fees, which the [smart router](../features/trade.md) factors into your price

A portion of spot fees funds the buybacks behind [CRONUS fee sharing](../rewards/README.md), so trading activity flows back to CRONUS holders.

## Perpetuals

* **Trading fee: 0.06%** for both maker and taker orders
* **Funding** payments exchanged between longs and shorts periodically (not a platform fee — it can be positive or negative for you)
* A **liquidation penalty** if a position is force-closed

See [Perps Overview](../perps/README.md).

## Prediction Markets

* **Trading fees: 1% taker / 0.5% maker**
* No fee to **redeem** winning shares — they're worth $1 each
* Your cost is the share price plus the trading fee; you can sell back at the current market price any time

See [Predict](../predict/README.md). The minimum order is **$1**.

## Deposits & Withdrawals

* Funding and withdrawing USDC may incur the relevant **network fees**
* **Internal transfers** between your Perps and Predict balances are quick and low-cost — see [Internal Transfers](../perps/README.md#internal-transfers-perps-↔-predict)

## CRONUS Fee Sharing

cro.trade distributes protocol trading fees to CRONUS holders. No tokens are minted — all distributions come from trading fees via on-chain buybacks. See [Rewards & Fee Sharing](../rewards/README.md).
