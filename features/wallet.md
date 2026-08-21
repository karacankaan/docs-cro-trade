# Wallet & Portfolio

Your **Profile** tab gives you a complete view of your portfolio across everything you trade on cro.trade — spot tokens, perps, and predictions — plus your full history and analytics.

## Portfolio Overview

At the top you'll see:

* **Total portfolio value** — your combined value across spot holdings, perps, and predictions
* **CRO balance** — your native CRO, with receive/send actions
* A **portfolio chart** with selectable ranges (**1D**, **1W**, **1M**) so you can see how your value has changed over time

## Holdings

A list of the tokens you hold on Cronos, each showing:

* Token name and symbol
* Amount held
* Current USD value and share of your portfolio
* Price change and profit & loss (P&L)

Tap any holding to open its [trade page](trade.md).

## Trade History

A unified log of your activity across spot, perps, and predictions. View it two ways:

* **List view** — each trade with the market, direction (buy/sell), amount, price, value, and time, with filters and a profit/loss badge on closed positions
* **Calendar heatmap** — a month-at-a-glance view of your realized P&L, with green for profitable days and red for losses; tap a day to filter the list to that period

History covers your Cronos spot trades, perps, and predictions in one place.

## Sending Money

**Send** moves money to a *person*, not to an address you have to paste. It asks three things, in order:

1. **Who** — pick from the traders you follow or people you've paid before, or type a **username**, a **`.cro` name**, or an address
2. **Where from** — **Cronos cash**, **Perps cash**, or **CRO**, each shown with its balance
3. **How much** — enter the amount, then swipe to confirm

Money arrives in the same balance it left: your Cronos cash lands in their Cronos cash, Perps in their Perps, CRO in their CRO. There's no cross-venue send — if you want your money in the other pot, move it there once on the transfer screen rather than on every send.

> **Predict is not a send source or destination.** Money in Predict is posted collateral rather than a spendable balance, so it leaves through withdraw instead.

## Funding Perps & Predict

Perps and predictions use **USDC**. Deposit, withdraw, and move funds between Perps and Predict from their wallet panels — see [Perps](../perps/README.md#funding-your-perps-account) and [Predict](../predict/README.md#funding-predict).

## Adding USDC from Another Chain

If your USDC is on a different chain, you don't have to bridge it yourself first. Choose **Add USDC from another chain** and cro.trade moves it across for you.

**Source chains:** Ethereum, Base, Arbitrum, Optimism, Polygon, Avalanche, and Cronos.

**Destination:** your **Cronos** wallet, your **Perps** balance, or your **Predict** balance.

How it works:

1. Pick the chain your USDC is on and the destination you want it in
2. Enter an amount — between **2** and **25,000 USDC** per transfer
3. Choose **Fast** (arrives in seconds, for a small transfer fee) or **Standard** (slower, cheaper)
4. Approve and confirm on the source chain

The USDC is burned on the source chain and native USDC is issued on the destination — it isn't a wrapped or synthetic token. **You don't need gas on the destination chain**: cro.trade covers that side. You do need enough of the source chain's native token to pay for the burn.

The panel shows each step as it happens — approving, burning, waiting for attestation, then minting — so you can see where a transfer is.

## Account & Wallets

Manage your username, linked sign-in methods, and your wallets (you can hold up to 20) from Settings — see [Account & Wallets](../account/wallets.md).
