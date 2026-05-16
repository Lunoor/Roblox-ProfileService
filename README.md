# Roblox-ProfileService

## 1. Setup ReplicatedStorage
Navigate to ReplicatedStorage and create these three objects. This acts as the "bridge" between your players and the server.

📡 RemoteEvent → Name it ShopRemote

📡 RemoteFunction → Name it ShopFunction

📦 ModuleScript → Name it ShopModule

Action: Paste your STEP 1 code here.

## 2. Add the Shop Configuration
The ShopModule is the heart of your system. This is where you will manage prices and item names.

File Location: ReplicatedStorage > ShopModule

Note: Whenever you want to add new items, you only need to edit the ITEMS table inside this script.

## 3. Configure the Server Logic
This script handles the money, saves the data to the cloud, and checks if a player has enough cash to buy an item.

File Location: ServerScriptService > ShopServer (Create a Script)

💾 Data Saving: Saves every 60 seconds.

🛡️ Security: Prevents players from giving themselves items without paying.

## 4. Setup the Client UI
This script creates the buttons on the player's screen and talks to the server when they click "Buy."

File Location: StarterPlayer > StarterPlayerScripts > ShopClient (Create a LocalScript)

🛒 Shop Button: Automatically appears at the bottom-left.

💰 Cash Badge: Displays your current balance at the top-right.

## ✅ Final Checklist
Press Play: Check the bottom-left of your screen for the Shop button.

Verify Data: When you leave and rejoin, your cash should stay the same.

Expansion: To add more items, just go back to Step 2 and update the table.

Check the Output window for any configuration errors.

## ## 🏷️ Trademarks & Brand Protection
The following are registered marks of the **Lunor Development Group**:
*   **Lunor™** (Brand Name)
*   **Lunor Hub™** (UI Framework)
*   **LPL™** (Lunor Product License)

Unauthorized use of these names, or the creation of "copycat" frameworks using the **Lunor** prefix, is a violation of our brand guidelines. All visual assets, logos, and branding elements are proprietary.
