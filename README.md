# Roblox-ProfileService

🛠️ Installation Guide
1. Setup ReplicatedStorage
In your Roblox Studio Explorer, navigate to ReplicatedStorage and create the following structure:

📡 RemoteEvent: Name it ShopRemote

📡 RemoteFunction: Name it ShopFunction

📦 ModuleScript: Name it ShopModule

Action: Paste the STEP 1 code into this module.

Plaintext
📂 ReplicatedStorage
 ├── 📡 ShopRemote
 ├── 📡 ShopFunction
 └── 📦 ShopModule
2. Configure the Server
Navigate to ServerScriptService to handle the backend logic and data saving.

🖥️ Script: Name it ShopServer

Action: Paste the STEP 2 code here.

Note: Ensure this is a regular Script, not a LocalScript.

3. Setup the Client
Navigate to StarterPlayerScripts to handle the UI and player interaction.

👤 LocalScript: Name it ShopClient

Action: Paste the STEP 3 code here.

🚀 Features
🛒 Interactive UI: Automatically generates a "SHOP" button (Bottom-Left).

💰 Currency System: Includes a custom cash badge (Top-Right).

💾 Auto-Save: Data saves automatically every 60 seconds and upon player departure using DataStoreService.

🛡️ Secure: Client-Server validation via RemoteFunctions to prevent exploiters from "free-buying."

⚙️ Customization
To add or modify items in your shop, open the ShopModule in ReplicatedStorage and edit the ITEMS table:

Lua
-- Example Item Entry
[1] = {
    Name = "Speed Coil",
    Price = 500,
    Description = "Go fast!",
    AssetID = 0000000 -- Replace with your mesh/decal ID
},
✅ Testing
Press F5 or click Play.

Verify the 🛒 SHOP button appears.

Verify the 💰 Cash display updates correctly.

Check the Output window for any configuration errors.
