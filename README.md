# Roblox-ProfileService

ReplicatedStorage — create 2 things
📡 RemoteEvent → name it ShopRemote
📡 RemoteFunction → name it ShopFunction
Right-click ReplicatedStorage → Insert Object → search "Remote"
2
ReplicatedStorage — add the module
📦 ReplicatedStorage
  ├─ ShopRemote
  ├─ ShopFunction
  └─ ShopModule  ← paste STEP1 file here (ModuleScript)
Insert Object → ModuleScript, rename it ShopModule, paste the STEP1 code in
3
ServerScriptService — add the server script
🖥️ ServerScriptService
  └─ ShopServer  ← paste STEP2 file here (Script)
Insert Object → Script (not LocalScript!), rename ShopServer, paste STEP2 code in
4
StarterPlayerScripts — add the client script
👤 StarterPlayer
  └─ StarterPlayerScripts
      └─ ShopClient  ← paste STEP3 file here (LocalScript)
Insert Object → LocalScript, rename ShopClient, paste STEP3 code in
✅  Press Play — you should see a 🛒 SHOP button bottom-left and 💰 cash badge top-right
✅  Data saves when you leave + every 60 seconds automatically
✅  To add items, edit the ITEMS table in STEP1 (ShopModule)
