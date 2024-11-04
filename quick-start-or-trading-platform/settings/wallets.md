---
icon: wallet
---

# Wallets

The **Wallets Menu** in Brigade allows users to manage their main and buy wallets. Here, users can generate new wallets, send SOL to their buy wallets, retrieve SOL back to the main wallet, and view private keys. This section provides detailed instructions on how to use each option in the Wallets Menu.

#### Wallets Menu Features

1. **FAQ: Generating Wallets and Sending SOL**
   * **Generating Wallets**:
     * Users can generate a new **Main Wallet** or create additional **Buy Wallets** for multi-wallet mode.
     * **Important Note**: When generating a new main or buy wallet, ensure that the current wallet is **empty**, as old wallets will not be recoverable after regeneration.
   * **Sending SOL**:
     * To send SOL to buy wallets, make sure the **Main Wallet** has sufficient SOL balance.
     * There are two methods for distributing SOL to buy wallets:
       1. **Fixed Amount per Wallet**: Enter a specific amount of SOL that will be sent to each buy wallet. Ensure the main wallet has enough SOL to cover the amount for each wallet.
       2. **Total Amount to Distribute Evenly**: Enter a total amount of SOL, which the bot will divide equally among all buy wallets. This option is helpful if you want an even distribution across wallets without specifying a fixed amount per wallet.
     * **Sending SOL Outside Brigade**: To send SOL to an external wallet, make sure the main wallet has the required amount. This option allows users to transfer SOL to any Solana wallet address.
2. **Display Private Keys**
   * **Description**: This option allows users to view the private keys for their main and buy wallets.
   * **Important Note**: Private keys should be handled securely. This option is provided for users who wish to back up or import their wallets outside of the bot. Tap the **Display Privates 🔑** button to view your private keys.

#### Wallet Management Options

1. **Generate Buy Wallets**:
   * **Function**: Creates a specified number of buy wallets (up to 5 for free users).
   * **Usage**: Tap the **Generate Buy Wallets 🪙** button, and select the number of wallets you wish to generate. This will replace any existing buy wallets, so ensure that old wallets are empty.
2. **Regenerate Main Wallet**:
   * **Function**: Replaces the current main wallet with a new one.
   * **Usage**: Tap the **Regenerate Main Wallet 🔄** button to generate a new main wallet. Be sure to transfer any funds out of the old wallet before proceeding, as the old wallet will no longer be accessible.
3. **Send SOL Out**:
   * **Function**: Allows users to send SOL from the main wallet to any external wallet.
   * **Usage**: Tap the **Send SOL Out 👋** button, then enter the recipient address and the amount of SOL you want to send.
4. **SOL Amount to Buys**:
   * **Function**: Sets a fixed amount of SOL to be sent to each buy wallet.
   * **Usage**: Tap the **SOL Amount to Buys 📄** button and enter the amount per wallet (e.g., `0.14`). The bot will then transfer this specified amount to each buy wallet.
5. **Send SOL**:
   * **Function**: Distributes SOL from the main wallet to all buy wallets based on the fixed amount or evenly divided total.
   * **Usage**: Tap the **Send SOL 🚀** button to initiate the transfer based on the amount you set in **SOL Amount to Buys** or the total amount divided equally among wallets.
6. **Empty Back to Main**:
   * **Function**: Transfers all SOL from buy wallets back to the main wallet.
   * **Usage**: Tap the **Empty Back to Main 🚀** button to consolidate funds from all buy wallets into the main wallet. This option is useful after completing trades or if you want to centralize your funds.
7. **Back**:
   * **Function**: Returns to the previous menu.
   * **Usage**: Tap the **Back 🔙** button to exit the Wallets Menu and return to the Settings Menu or Main Menu.
