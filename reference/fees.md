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

Bringing USDC in from another chain costs you no gas at all: cro.trade sponsors the transaction on both the source and the destination side. From **Arbitrum** and **Base** the transfer itself carries a small network fee, around **0.014%** and **0.013%**; from **Polygon** and **Solana** there is none. Topping up your **Perps** balance adds a flat **~$0.20-0.30** on top, the same amount whatever the size of the transfer. Whatever applies is shown on screen before you confirm. See [Adding USDC from another chain](../features/wallet.md#adding-usdc-from-another-chain).

Moving USDC between your Perps and Predict balances is quick and cheap — see [Transfers between Perps and Predict](../perps/README.md#transfers-between-perps-and-predict).
