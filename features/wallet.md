# Wallet & Portfolio

The **Profile** tab is everything you hold and everything you've done, across spot, perps and predictions.

## Overview

Your total value across all three markets sits at the top, with your CRO balance and its send and receive actions beside it, over a chart you can set to **1D**, **1W** or **1M**.

## Holdings

The Cronos tokens you hold, each with the amount, its USD value, what share of your portfolio it is, the price change and your P&L. Tap one to open its [trade page](trade.md).

## History

One log for spot, perps and predictions together, in either of two views.

**List** gives you each trade with its market, direction, amount, price, value and time, filterable, with a profit or loss badge on anything closed.

**Calendar** is a month of realised P&L at a glance — green days up, red days down. Tap a day to narrow the list to it.

## Sending money

**Send** moves money to a *person*, not to an address you have to paste. It asks three things in order:

1. **Who.** People you follow, people you've paid before, or a **username**, a **`.cro` name** or an address typed in.
2. **Where from.** **Cronos cash**, **Perps cash** or **CRO**, each with its balance.
3. **How much.** Enter the amount and swipe to confirm.

Money lands in the same balance it left — your Cronos cash into their Cronos cash, Perps into their Perps, CRO into their CRO. There's no cross-venue send. If you want it in the other pot, move it there once on the transfer screen instead of on every send.

**Predict is neither a source nor a destination.** Money in Predict is posted collateral rather than a spendable balance, so it comes out through withdraw.

## Funding perps and predict

Both settle in **USDC**. Deposit, withdraw and move money between them from their own wallet panels — see [Perps](../perps/README.md#funding-your-account) and [Predict](../predict/README.md#funding).

## Adding USDC from another chain

If your USDC is somewhere else, you don't have to bridge it yourself. **Add USDC from another chain** does it in one flow.

It comes from **Ethereum, Base, Arbitrum, Optimism, Polygon, Avalanche or Cronos**, and lands in your **Cronos** wallet, your **Perps** balance or your **Predict** balance.

Pick the source and destination, enter an amount between **2 and 25,000 USDC**, choose **Fast** (seconds, small fee) or **Standard** (slower, cheaper), then approve on the source chain.

The USDC is burned there and native USDC is issued on the destination — nothing wrapped or synthetic arrives. **You need no gas on the destination side**; cro.trade covers it. You do need enough of the source chain's native token to pay for the burn.

The panel names each step as it happens — approving, burning, waiting for attestation, minting — so a transfer in flight is never a blank screen.

## Account and wallets

Username, linked sign-in methods and your wallets — up to 20 — live in [Account & Wallets](../account/wallets.md).
