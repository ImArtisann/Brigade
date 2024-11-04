---
description: Buy / Sell Menu Button
---

# 💸 Trading Menu

The **Trading Menu** in Brigade allows users to quickly execute buy and sell transactions for a selected token. It provides customization options for buy/sell amounts, transaction priority, slippage tolerance, and wallet selection when in Multi-Wallet Mode.

#### Overview of the Trading Menu

1. **Token Information**
   * **Wallet Address**: Displays the active wallet address in use.
   * **Balance**: Shows the current SOL balance in **Multi Wallet** mode (if applicable).
   * **Token Data**: Displays the token symbol (e.g., `$SKY`) and **Market Cap** in USD (e.g., `MCAP: $7,525.68 USD`).
   * **Platform**: Shows the platform (e.g., `Pump.fun`) and any relevant token information or market status.
2. **Trading Options**
   * **Buy Menu**: Switches to **Buy Options** for executing buy orders.
   * **Sell Menu**: Switches to **Sell Options** for executing sell orders.

#### Buy Options (Buy Menu)

When in the **Buy Menu**, users have access to several configurable options for executing buy orders:

* **Quick Buy Options**: Provides three preset SOL amounts for quick buys, based on the nearest values set in the **Main** tab of the **Settings Menu**. For example, if the user sets `1 SOL`, `3 SOL`, and `5 SOL` in Settings, these values will appear here as options for quick selection.
  * **Auto-Update**: If the user changes a quick buy amount here, it will automatically update to the closest available values from their settings.
* **Custom Buy Amount**: Tap on the **Custom** icon (🖊) to enter a specific amount of SOL for a custom buy order.
* **Random Buy**: Tap the **Random** icon (🖊) to specify a random SOL range for buys. The bot will pick a random value within this range for each transaction, creating a more human-like trading pattern.
* **Slippage (Slip)**: Shows the current slippage tolerance for buy transactions (e.g., `Slip: 17`). Users can adjust this to ensure trades execute only within the specified tolerance range.
* **Priority Settings**: Set the transaction priority (Normal, Turbo, Lightspeed) for faster or slower execution based on network conditions and fee preferences.
* **Send Buys**: Executes the buy order with the selected parameters.
* **Select Wallets** (Only in Multi-Wallet Mode): Allows users to select specific buy wallets for the transaction. This button will only appear when in **Multi-Wallet Mode**. Users can choose individual wallets or use the **Select All** option for bulk selection.

#### Sell Options (Sell Menu)

When in the **Sell Menu**, users can access the following options for executing sell orders:

* **Quick Sell Options**: Provides three preset sell percentages based on the nearest values configured in the **Main** tab of the **Settings Menu** (e.g., `50%`, `75%`, `100%`).
  * **Auto-Update**: If the user changes a quick sell percentage here, it will automatically update the options to the nearest values set in the **Settings Menu**.
* **Custom Sell Percentage**: Tap the **Custom** icon (🖊) to enter a specific percentage of tokens to sell.
* **Slippage (Slip)**: Displays the current slippage tolerance for sell transactions (e.g., `Slip: 30`). Users can adjust this to ensure trades execute only within the specified tolerance range.
* **Priority Settings**: Set the transaction priority (Normal, Turbo, Lightspeed) to control the execution speed and fee based on network conditions.
* **Send Sells**: Executes the sell order with the selected parameters.
* **Quick Dump** (Only in Multi-Wallet Mode): This option consolidates all tokens from the selected buy wallets into a single wallet and initiates a sell order. **Quick Dump** is useful for rapidly exiting positions across multiple wallets to minimize slippage. This button will only appear in **Multi-Wallet Mode**.
