local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "pepis hub",
   LoadingTitle = "loanding downloader script and buttons  ",
   LoadingSubtitle = "By Nyc3reX scripts",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Player Changer"
   },
   Discord = {
      Enabled = true,
      Invite = "5tBNqX3Ngp", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local MainTab = Window:CreateTab("Main", nil) -- Title, Image
local MainSection = MainTab:CreateSection("Main")

Rayfield:Notify({
   Title = "Executed The Script Successfully",
   Content = "A Good Script Hub",
   Duration = 5,
   Image = nil,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Okay!",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})


   Name = "Infinite Yield",
   Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,



local Button = MainTab:CreateButton({
   Name = "GHOST HUB X",
   Callback = function()
        --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
   end,
})

local Button = MainTab:CreateButton({
   Name = "blox fruit script",
   Callback = function()
      _G.Quest = {
         ['RGB Aura Haki'] = true,
         ['Pull Lever'] = true,
         ['Quest Dough Awaken'] = true
     }
     _G.Race = {
         ['Select Race'] = {'Human','Fishman','Skypiea','Mink'},
         ['Lock Race'] = true,
         ['Evo Race V3'] = true
     }
     _G.Melee = {
         ['Godhuman'] = true
     }
     _G.Sword = {
         ['Saber'] = true,
         ['Midnight Blade'] = true,
         ['Shisui'] = true,
         ['Saddi'] = true,
         ['Wando'] = true,
         ['Yama'] = true,
         ['Koko'] = false,
         ['Rengoku'] = true,
         ['Canvander'] = true,
         ['Buddy Sword'] = true,
         ['Twin Hooks'] = true,
         ['SpikeyTrident'] = true,
         ['Hallow Scryte'] = true,
         ['Dark Dagger'] = true,
         ['Tushita'] = true,
         ['True Triple Katana'] = true,
         ['Cursed Dual Katana'] = true,
         ['Shark Anchor'] = true
     }
     _G.Gun = {
         ['Kabucha'] = true,
         ['Acidum Rifle'] = true,
         ['Soul Guitar'] = true,
         ['Serpent Bow'] = true
     }
     _G.Fruit = {
         ['Main Fruit'] = {'Kitsune-Kitsune','T-Rex-T-Rex','Mammoth-Mammoth'},
         ['Select Fruit'] = {'Dark-Dark','Magma-Magma'}
     }
     _G.Mastery = {
         ['Melee'] = true,
         ['Sword'] = true,
         ['Fruit'] = true
     }
     _G.Setting = {
         ['FPS Booster'] = true,
         ['Auto Close Ui'] = false
     }
     loadstring(game:HttpGet("https://raw.githubusercontent.com/NGUYENVUDUY1/Super/refs/heads/main/Kaitun.lua"))()
   end,
})

local Button = MainTab:CreateButton({
   Name = "no fucional",
   Callback = function()
        --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt"))() 
   end,
})

local Button = MainTab:CreateButton({
   Name = "FLING POWER (no ban)",
   Callback = function()
        --[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_rf6iQURzu1fqrytcnLBAvW34C9N55kS9g9G3CKz086rC47M6632sEd4ZZYB0AYgV.lua.txt'),true))()
   end,
})

local Tab = Window:CreateTab("Info", nil) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "Info", Content = "By RAZER#6027"})

local Paragraph = Tab:CreateParagraph({Title = "Info", Content = "Discord Server : https://discord.gg/5tBNqX3Ngp"})

local Button = MainTab:CreateButton({
   Name = "game hub v3",
   Callback = function()
        --[[
	--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamerScripter/Game-Hub/main/loader"))()
   end,
})

local Button = MainTab:CreateButton({
   Name = "fe trolling gui",
   Callback = function()
        --[[
	loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub/main/FE%20Trolling%20GUI.luau"))()
   end,
})
	
