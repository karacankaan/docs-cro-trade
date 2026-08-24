# Fees

## Spot, on Cronos

**0.9%** per trade, built into the quote you see. On top of that you pay network gas and whatever the underlying pools charge, both of which the router already accounts for when it picks a route.

USDC trades are gasless.

## Perpetuals

**0.06%**, maker and taker alike.

Funding is separate and isn't a platform fee: it's paid between longs and shorts every few hours and can go either way for you. [Perps](../perps/README.md) explains it.

## Prediction markets

**1% taker, 0.5% maker.** Your cost is the share price plus the fee, and you can sell back at the market price at any time.

Redeeming winning shares is free — they're worth $1 each. Minimum order is **$1**. See [Predict](../predict/README.md).

## Moving money

Funding and withdrawing USDC costs the relevant network fees.

Moving USDC in from a chain you already hold it on costs you no gas: cro.trade sponsors both sides. What the transfer itself costs:

| From | To Cronos | To Perps | To Predict |
| --- | --- | --- | --- |
| **Cronos** | | free | free |
| **Arbitrum** | 0.014% | free | 0.014% |
| **Base** | 0.013% | 0.013% | 0.013% |
| **Polygon** | free | free | free |
| **Solana** | free | free | free |
| **HyperEVM** | free | free | free |

A percentage is the network's own charge for settling in seconds rather than twenty minutes, taken out of the amount as it moves. It depends on where the money starts, which is why Arbitrum and Base carry one and the rest don't; Arbitrum into Perps takes a different route that costs nothing at all. Whatever applies is shown before you confirm.

Your first ever Perps deposit also opens the account, which costs **$1** once. See [Adding USDC from another chain](../features/wallet.md#adding-usdc-from-another-chain).

Moving USDC between your Perps and Predict balances is quick and cheap — see [Transfers between Perps and Predict](../perps/README.md#transfers-between-perps-and-predict).
