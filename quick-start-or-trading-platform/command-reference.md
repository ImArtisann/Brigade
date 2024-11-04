# 🖱️ Command Reference

### Command Reference

The Brigade trading bot provides a variety of commands to streamline trading operations and manage settings efficiently. Below is a detailed list of commands, required and optional parameters, and examples for each.

***

#### 1. **/start**

* **Description**: Initializes Brigade and displays the welcome message. Use any command to view the help menu for that specific command.
* **Usage**: `/start`

***

#### 2. **/buy**

* **Description**: Sends an auto buy order for a specified contract.
* **Required**: `contract` (Token contract address)
* **Optional**: `amount` (SOL amount for the purchase)
* **Usage**: `/buy <contract> <amount>`
* **Example**: `/buy Es9vMFrz... 0.5`

***

#### 3. **/sell**

* **Description**: Sends an auto sell order for a specified contract.
* **Required**: `contract` (Token contract address)
* **Optional**: `amount` (Amount of tokens to sell, in percentage or absolute value)
* **Usage**: `/sell <contract> <amount>`
* **Example**: `/sell Es9vMFrz... 50` (Sells 50% of the token balance

***

#### 4. **/random**

* **Description**: Sends a buy order with a randomly selected SOL amount within a specified range.
* **Required**: `contract` (Token contract address)
* **Optional**: `random range` (SOL amount range, formatted as `min:max`)
* **Usage**: `/random <contract> <min:max>`
* **Example**: `/random Es9vMFrz... 0.1:0.5`

***

#### 5. **/auto**

* **Description**: Opens the settings menu or wallet selector for automatic trades.
* **Options**: `settings` or `wallets`
* **Usage**: `/auto <option>`
* **Example**: `/auto settings`

***

#### 6. **/copy**

* **Description**: Manages copy trading by adding/removing wallets or opening settings.
* **Options**: `settings`, `wallets`, or `wallet`
* **Usage**: `/copy <option>`
* **Example**: `/copy wallet`

***

#### 7. **/snipe**

* **Description**: Manages snipe trading by adding/removing wallets or opening settings.
* **Options**: `settings`, `wallets`, or `wallet`
* **Usage**: `/snipe <option>`
* **Example**: `/snipe wallets`

***

#### 8. **/priority**

* **Description**: Sets the priority fee level for a specified trade mode.
* **Required**: `priority number` (Numeric value for priority)
* **Optional**: `mode` (Trade mode, default is `main`)
* **Usage**: `/priority <priority number> <mode>`
* **Example**: `/priority .001 snipe`

***

#### 9. **/autop**

* **Description**: Enables auto-priority with a specified priority level.
* **Optional**: `priority level string` (e.g., `normal`, `turbo`, `lightening`)
* **Optional**: `mode` (Trade mode, default is `main`)
* **Usage**: `/autop <priority level> <mode>`
* **Example**: `/autop turbo main`

***

#### 10. **/amount**

* **Description**: Sets the SOL amount to be used for a specified trade mode.
* **Required**: `sol amount number`
* **Optional**: `mode` (Trade mode, default is `main`)
* **Usage**: `/amount <sol amount> <mode>`
* **Example**: `/amount 0.5 copy`

***

#### 11. **/buyslip**

* **Description**: Sets the slippage tolerance for buy orders in a specified trade mode.
* **Required**: `buy slip number` (Percentage)
* **Optional**: `mode` (Trade mode, default is `main`)
* **Usage**: `/buyslip <buy slip> <mode>`
* **Example**: `/buyslip 5 snipe`

***

#### 12. **/sellslip**

* **Description**: Sets the slippage tolerance for sell orders in a specified trade mode.
* **Required**: `sell slip number` (Percentage)
* **Optional**: `mode` (Trade mode, default is `main`)
* **Usage**: `/sellslip <sell slip> <mode>`
* **Example**: `/sellslip 3 snipe`

***

#### 13. **/genbuy**

* **Description**: Generates a specified number of new buy wallets for Multi-Wallet Mode.
* **Required**: `number` (Number of buy wallets to generate)
* **Usage**: `/genbuy <number>`
* **Example**: `/genbuy 5`

***

#### 14. **/genfund**

* **Description**: Generates a new fund wallet, replacing the existing one.
* **Usage**: `/genfund`

***

#### 15. **/fund**

* **Description**: Sends SOL from the main wallet to buy wallets.
* **Required**: `sol amount` (Amount of SOL to distribute)
* **Usage**: `/fund <sol amount>`
* **Example**: `/fund 1.0`

***

#### 16. **/extract**

* **Description**: Empties all buy wallets, transferring SOL back to the fund wallet.
* **Usage**: `/extract`

***

#### 17. **/send**

* **Description**: Sends SOL to any specified wallet.
* **Usage**: `/send <wallet address> <amount>`
* **Example**: `/send C1vQy...N2k7w 0.5`

***

#### 18. **/mode**

* **Description**: Toggles between **Quick Mode** (fast actions) and **Open Menu Mode** (detailed actions) for trading.
* **Usage**: `/mode`

***

#### 19. **/help**

* **Description**: Displays the help menu with detailed explanations of all available commands.
* **Usage**: `/help`
