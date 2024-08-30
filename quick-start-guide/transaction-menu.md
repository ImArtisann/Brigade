---
description: Buy / Sell Menu Button
---

# 💸 Transaction Menu

## **Fund Wallet Mode:**

* **Contract Address Input**: Enter the token’s contract address to access trading options.
* **Buy Options**:
  * **Preset SOL Amounts**: Choose from preset options (e.g., 0.5 SOL, 1 SOL).
  * **Custom Amount**: Set a specific amount of SOL for purchasing.
  * **Random Amount**: The bot can automatically select a random buy amount within a specified range (e.g., 0.1 to 0.5 SOL).
* **Sell Options**:
  * **Preset Sell Percentages**: Choose from preset percentages of your token balance (e.g., 2%, 5%, 10%, 25%, 50%, 75%, 100%).
  * **Custom Token Amount**: Enter a specific number of tokens to sell.
* **Submit Buys/Sells**: Directly execute trades from the fund wallet without selecting multiple wallets.

## **Buy Wallet Mode:**

* **Contract Address Input**: Similar to Fund Wallet Mode, but the user must select the wallets to use for the trade.
* **Buy Options**:
  * **Preset SOL Amounts**: As with Fund Wallet Mode, select from preset amounts.
  * **Custom Amount**: Specify the amount of SOL for the transaction.
  * **Random Amount**: The bot will randomly select a buy amount within a user-defined range.
  * **Select Wallets**: Users must select which of the generated buy wallets will be used for the transaction. A green checkmark indicates a selected wallet.
  * **Quick Select**: Use the `Select All` button to quickly select all wallets. The button changes to `Remove All` if all wallets are selected.
* **Sell Options**:
  * **Preset Sell Percentages**: As with Fund Wallet Mode, choose from preset sell percentages.
  * **Custom Token Amount**: Enter the number of tokens to sell.
  * **Quick Dump**: This special option allows users to consolidate all SPL tokens from all buy wallets that have a SPL balance into a single wallet and then execute a sell order. This feature is useful for quickly exiting trades while minimizing slippage.
* **Submit Buys/Sells**: Executes the trade across all selected wallets simultaneously. Brigade’s custom methods ensure the transaction speed remains consistent across multi wallets vs submitting a transaction on one wallet.
* **Transaction Status Updates**: After submitting a trade, the bot will update with transaction IDs and statuses (e.g., confirmed, failed, or no balance). Users can refresh to update their wallet balances and unrealized PNL to be shown in the transaction menu.
