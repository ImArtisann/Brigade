---
description: >-
  Brigade offers a comprehensive set of commands to streamline and automate
  various trading activities. This section provides detailed descriptions and
  usage examples for each command.
---

# 🖱️ Command Reference

### **1. `/slip <amount>`**

**Description:**\
Sets the slippage tolerance for transactions. Slippage refers to the percentage difference between the expected price of a trade and the price at which the trade is actually executed.

**Usage:**\
`/slip 0.5`\
Sets the slippage tolerance to 0.5%.

### **2. `/priority <amount>`**

**Description:**\
Sets a custom priority fee for transactions, which can help increase the likelihood of your transaction being confirmed during network congestion.

**Usage:**\
`/priority 0.00001`\
Sets the transaction priority fee to 0.00001 SOL.

### **3. `/ap <medium|high|vhigh>`**

**Description:**\
Turns on auto priority for transactions, allowing the bot to automatically select a priority fee based on network conditions.

**Usage:**\
`/ap medium`\
Activates auto priority with a medium fee setting.

### **4. `/gb <number>`**

**Description:**\
Generates new buy wallets. This command is particularly useful for users operating in Buy Wallet Mode.

**Usage:**\
`/gb 5`\
Generates 5 new buy wallets. A confirmation prompt will appear, reminding users that old wallets cannot be recovered.

### **5. `/gf`**

**Description:**\
Generates a new fund wallet. This command is used to replace the current fund wallet with a new one.

**Usage:**\
`/gf`\
Generates a new fund wallet after confirming that the old wallet’s balance is empty.

### **6. `/sendsol <wallet> [<amount>]`**

**Description:**\
Transfers SOL from the fund wallet to another wallet. If no amount is specified, all SOL in the fund wallet is transferred.

**Usage:**\
`/sendsol C1vQy...N2k7w`\
Transfers all SOL from the fund wallet to the specified wallet.

`/sendsol C1vQy...N2k7w 0.5`\
Transfers 0.5 SOL from the fund wallet to the specified wallet.

### **7. `/ab <contract> [<amount>]`**

**Description:**\
Submits an auto buy using the default settings configured in the Auto Buy/Sell Settings Menu. If an amount is specified, it overrides the default amount.

**Usage:**\
`/ab Es9vMFrz...`\
Submits an auto buy using the contract address with the default SOL amount.

`/ab Es9vMFrz... 0.5`\
Submits an auto buy with 0.5 SOL for the specified contract address.

### **8. `/as <contract> [<sell percentage>]`**

**Description:**\
Submits an auto sell using the default settings configured in the Auto Buy/Sell Settings Menu. If a sell percentage is specified, it overrides the default percentage.

**Usage:**\
`/as Es9vMFrz...`\
Submits an auto sell using the contract address with the default sell percentage.

`/as Es9vMFrz... 50`\
Submits an auto sell for 50% of the token balance for the specified contract address.

### **9. `/ar <contract> [<random amount>]`**

**Description:**\
Submits an auto random buy based on the random amount range set in the Auto Buy/Sell Settings Menu. If a specific random amount is specified, it overrides the default range.

**Usage:**\
`/ar Es9vMFrz...`\
Submits an auto random buy using the default random amount range for the specified contract.

`/ar Es9vMFrz... 0.1:0.3`\
Submits an auto random buy with an amount randomly chosen between 0.1 and 0.3 SOL for the specified contract.

### **10. `/sf`**

**Description:**\
Quickly transfers all SOL from your buy wallets back to the fund wallet. This command is useful when users want to consolidate funds after trading.

**Usage:**\
`/sf`\
Transfers all SOL from buy wallets to the fund wallet.

### **11. `/sb <amount>`**

**Description:**\
Sends SOL from the fund wallet to all buy wallets, distributing the specified amount evenly.

**Usage:**\
`/sb 0.5`\
Distributes 0.5 SOL evenly among all buy wallets.

### **12. `/ac <wallet>`**

**Description:**\
Adds a wallet address to your copy trade list. This command is a quick alternative to adding wallets via the Copy Trade Menu.

**Usage:**\
`/ac C1vQy...N2k7w`\
Adds the specified wallet to the copy trade list.

### **13. `/rc <wallet>`**

**Description:**\
Removes a wallet address from your copy trade list.

**Usage:**\
`/rc C1vQy...N2k7w`\
Removes the specified wallet from the copy trade list.

### **14. `/sniper <wallet>`**

**Description:**\
Adds a wallet address to your sniper trade list, which is used to snipe new tokens created by the specified wallet.

**Usage:**\
`/sniper C1vQy...N2k7w`\
Adds the specified wallet to the sniper trade list.

### **15. `/rsniper <wallet>`**

**Description:**\
Removes a wallet address from your sniper trade list.

**Usage:**\
`/rsniper C1vQy...N2k7w`\
Removes the specified wallet from the sniper trade list.
