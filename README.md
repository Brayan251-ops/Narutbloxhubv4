-- carregar a biblioteca 
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Naruthubv4☠️" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "🏠Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

--parágrafo 
Tabs.Main:AddParagraph({ Title = "Naruthubv4☠️", Content = "This is a paragraph.\nSecond line!" })
--botões
Tabs.Main:AddButton({ Title = "infinity jump", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/HeyGyt/infjump/main/main"))()
end })
Tabs.Main:AddButton({ Title = "fly", Callback = function() 
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
end })

local Tabs = {
    Main = Window:AddTab({ Title = "murder mystery🔫" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

Tabs.Main:AddButton({ Title = "op😈", Callback = function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/MarsQQ/ScriptHubScripts/master/MM2%20Admin%20Panel'),true))()
end })

local Tabs = {
    Main = Window:AddTab({ Title = "blox fruits🍎(kaitun)☠️" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

Tabs.Main:AddButton({ Title = "Button", Callback = function()
_G.KaitunConfig = {
    ["Actions Allowed"] = {
      ["Awakening Fruit"] = true,
      ["Shark Anchor"] = true,
      ["Mirror Fractal"] = true,
      ["Soul Guitar"] = true,
      ["Pole (1st Form)"] = true,
      ["Upgrading Race"] = true,
      ["Farming Boss Drop When Maxed Level"] = true,
      ["Rainbown Haki"] = true,
      ["Cursed Dual Katana"] = true,
      ["Buy accessories"] = true,
      ["Buy Hakis"] = true,
      ["Buy Guns"] = true,
      ["Buy Swords"] = true,
      ["Upgrade Weapons"] = true,
      ["Farming Boss Drops When X2 Expired"] = true,
      ["Mirage Puzzle"] = true,
      ["Saber"] = true
    },
    ["Fps Boosting"] = true,
    ["Fruit Snipping"] = true,
    ["Fruit Eating"] = true,
    ["High Ping Hop"] = true,
    ["Fruit Choosen"] = {
      ["T-Rex-T-Rex"] = true,
      ["Shadow-Shadow"] = true,
      ["Mammoth-Mammoth"] = true,
      ["Gravity-Gravity"] = true,
      ["Spirit-Spirit"] = true,
      ["Dark-Dark"] = true,
      ["Rocket-Rocket"] = true,
      ["Control-Control"] = true,
      ["Dough-Dough"] = true,
      ["Leopard-Leopard"] = true,
      ["Venom-Venom"] = true,
      ["Dragon-Dragon"] = true,
      ["Diamond-Diamond"] = true,
      ["Kitsune-Kitsune"] = true,
      ["Spring-Spring"] = true
    },
    ["Player Nearing Hop"] = true,
    ["Allow Stored"] = true,
    ["Race Choosen"] = {
      ["Human"] = true
    },
    ["Race Snipping"] = true,
    ["Tween Speed"] = 350,
    ["Same Y Tween"] = true
}
loadstring(game:HttpGet('https://lureshub.onrender.com/LureKaitun.lua'))()
end })

local Tabs = {
    Main = Window:AddTab({ Title = "Admin💀" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

Tabs.Main:AddButton({ Title = "infinity yield", Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end })
Tabs.Main:AddButton({ Title = "Fates admin", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end })
Tabs.Main:AddButton({ Title = "CMD-X", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source", true))()
end })

local Tabs = {
    Main = Window:AddTab({ Title = "Esp Players" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

Tabs.Main:AddButton({ Title = "NAME ESP", Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/ESP-Script/main/ESP.lua"))()
end })
