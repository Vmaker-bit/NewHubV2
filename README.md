--NewHubV2

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/slf0Dev/Ocerium_Project/main/Library.lua"))()
Window = Library.Main("Nigger","A")

--//tab
local Tab = Window.NewTab("BloxFruit")


--//section
local Section = Tab.NewSection("Bloxfruit")

--// Button
local Button = Section.NewButton("RipperHub",function()
    _G.Color = Color3.fromRGB(52, 190, 255)
loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/NEWBF.lua"))()
end)
local button = Section.NewButton("Newhub" ,function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/Xeter"))()
end)
local button = Section.NewButton("ThunderZ" ,function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-05/HUB/main/Script"))()
end)

--New
local TabFs = Window.NewTabFs("fightingStyle")
local fsSection = Tab.NewSection2("FightingStyle")

local button = fsSection.NewButton("DeathStep" ,function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
end)
local button = fsSection.NewButton("Superhuman" ,function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
end)
local button = fsSection.NewButton("DragonTalon" ,function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
end)
local button = fsSection.NewButton("SharkmanKarate" ,function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
end)
local button = fsSection.NewButton("E-Claw" ,function()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
end)
