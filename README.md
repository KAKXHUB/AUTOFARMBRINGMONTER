local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("KAK HUB", "Sentinel")

local Tab = Window:NewTab("TELEPORT")
local Section = Tab:NewSection("TELEPORT")

Section:NewButton("Boss Aura", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1575.63281, 219.278564, 9939.50684, 0.99147594, -1.15348042e-09, 0.130290106, 6.03497918e-09, 1, -3.70715512e-08, -0.130290106, 3.75418487e-08, 0.99147594)
end)

local Tab = Window:NewTab("Spam Skill1")
local SpamSection = Tab:NewSection("Spam Skill Devil Fruit1")

SpamSection:NewButton("Rumble", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Rumble.RemoteEvent:FireServer("RumblePower4","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Dark", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Dark.RemoteEvent:FireServer("DarkPower4","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Light", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Light.RemoteEvent:FireServer("LightPower2","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Magma", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Magma.RemoteEvent:FireServer("MagmaPower1","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Flare", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Flare.RemoteEvent:FireServer("FlarePower2","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Bomb", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Bomb.RemoteEvent:FireServer("BombPower5","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Gas", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Gas.RemoteEvent:FireServer("GasPower4","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Phoenix", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Phoenix.RemoteEvent:FireServer("PhoenixPower3","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Chilly", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Chilly.RemoteEvent:FireServer("ChillyPower5","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

SpamSection:NewButton("Vampire", "ButtonInfo", function()
  while wait(0.1) do
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Vampire.RemoteEvent:FireServer("VampirePower5","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end
end)

local Tab = Window:NewTab("Spam Skill2")
local Spam2Section = Tab:NewSection("Spam Skill2")

Spam2Section:NewToggle("Rumble", " ", function(a)
SpamTeleport = a   
end)

spawn(function()
while wait() do
if SpamTeleport then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Rumble.RemoteEvent:FireServer("RumblePower10","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Dark", " ", function(a)
SpamTeleport1 = a
end)

spawn(function()
while wait() do
if SpamTeleport1 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Dark.RemoteEvent:FireServer("DarkPower10","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Light", " ", function(a)
SpamTeleport2 = a
end)

spawn(function()
while wait() do
if SpamTeleport2 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Light.RemoteEvent:FireServer("LightPower8","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Magma", " ", function(a)
SpamTeleport3 = a
end)

spawn(function()
while wait() do
if SpamTeleport3 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Magma.RemoteEvent:FireServer("MagmaPower7","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Flare", " ", function(a)
SpamTeleport4 = a
end)

spawn(function()
while wait() do
if SpamTeleport4 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Flare.RemoteEvent:FireServer("FlarePower8","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Bomb", " ", function(a)
SpamTeleport5 = a
end)

spawn(function()
while wait() do
if SpamTeleport5 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Bomb.RemoteEvent:FireServer("BombPower11","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Gas", " ", function(a)
SpamTeleport6 = a 
end)

spawn(function()
while wait() do
if SpamTeleport6 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Gas.RemoteEvent:FireServer("GasPower10","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Phoenix", " ", function(a)
SpamTeleport7 = a
end)

spawn(function()
while wait() do
if SpamTeleport7 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Phoenix.RemoteEvent:FireServer("PhoenixPower9","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Chilly", " ", function(a)
SpamTeleport8 = a
end)

spawn(function()
while wait() do
if SpamTeleport8 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Chilly.RemoteEvent:FireServer("ChillyPower11","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end
end
end)

Spam2Section:NewToggle("Vampire", " ", function(a)
SpamTeleport9 = a
end)

spawn(function()
while wait() do
if SpamTeleport9 then
pcall(function()
local plr = game:GetService("Players").LocalPlayer
plr.Character.Powers.Vampire.RemoteEvent:FireServer("VampirePower11","StopCharging",plr.Character.HumanoidRootPart.CFrame,workspace.IslandSnowyMountains.Stone.Stone,100)
end)
end  
end
end)

Section:NewButton("Crab island", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6.00764561, 215.999954, -304.312866, 0.999960184, -1.31916487e-08, -0.00892135222, 1.31739979e-08, 1, -2.03728945e-09, 0.00892135222, 1.91967842e-09, 0.999960184)
end)

Section:NewButton("Vokun", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4564.3999, 526, 5712.5, 1, -8.67146355e-09, 8.66510802e-13, 8.67146355e-09, 1, -1.25880606e-09, -8.66499851e-13, 1.25880606e-09, 1)
end)

Section:NewButton("Purple", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5283, 534.199829, -7761.5, 1, -6.71749234e-09, 5.83083386e-14, 6.71749234e-09, 1, -9.7488162e-10, -5.83017928e-14, 9.7488162e-10, 1)
end)

Section:NewButton("Rocky", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-32.2999992, 228.999954, 2156.6001, 1, -2.293989e-09, 7.4222253e-15, 2.293989e-09, 1, -3.32853189e-10, -7.42146213e-15, 3.32853189e-10, 1)
end)

Section:NewButton("Boss", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4809.43555, 590.268005, -7000.63379, 0.986272573, -1.30538051e-08, -0.16512543, 1.18410401e-08, 1, -8.32888958e-09, 0.16512543, 6.25929886e-09, 0.986272573)
end)

Section:NewButton("Sand Castle", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(921, 223.999954, -3275, 1, -1.85406162e-08, 1.83611891e-14, 1.85406162e-08, 1, -8.88946783e-09, -1.81963734e-14, 8.88946783e-09, 1)
end)

Section:NewButton("Boss sniper", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1075.32813, 360.999908, 1676.62024, 1, -1.30933424e-08, 1.62521296e-14, 1.30933424e-08, 1, -6.27673913e-09, -1.61699471e-14, 6.27673913e-09, 1)
end)

Section:NewButton("Snow", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1897, 224.999954, 3298, 1, -1.10378416e-07, 1.67164324e-15, 1.10378416e-07, 1, -4.98986497e-09, -1.12086981e-15, 4.98986497e-09, 1)
end)

Section:NewButton("Drink", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1505, 260.38623, 2170.8999, 1, -6.83510564e-08, 3.47501386e-15, 6.83510564e-08, 1, -3.08943671e-09, -3.2638477e-15, 3.08943671e-09, 1)
end)

Section:NewButton("Tree", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1166, 217.079941, 3287, 1, -1.51681228e-08, 1.25091922e-15, 1.51681228e-08, 1, -6.85466572e-10, -1.240522e-15, 6.85466572e-10, 1)
end)

Section:NewButton("Big Snow", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6616, 417.998901, -1497.30005, 1, -1.03510274e-07, 2.07181146e-15, 1.03510274e-07, 1, -4.67721728e-09, -1.58767146e-15, 4.67721728e-09, 1)
end)

Section:NewButton("Cave", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-79.5663376, 215.999985, -890.889465, 1, -7.63786403e-08, 2.29127389e-15, 7.63786403e-08, 1, -3.4506964e-09, -2.02771429e-15, 3.4506964e-09, 1)
end)

Section:NewButton("Forest", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6006.75977, 402, 7.19999981, 1, 1.18328082e-07, 2.90348834e-15, -1.18328082e-07, 1, 5.34521405e-09, -2.27099952e-15, -5.34521405e-09, 1)
end)

Section:NewButton("Pyramid", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119, 310, 4945.8999, 1, 5.51431327e-08, 5.2718581e-15, -5.51431327e-08, 1, 2.49052534e-09, -5.13452272e-15, -2.49052534e-09, 1)
end)

Section:NewButton("Sam", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1281.68347, 218, -1351.09534, -1, 5.86880518e-08, 7.24010242e-05, 5.86823248e-08, 1, -7.91251793e-08, -7.24010242e-05, -7.91209303e-08, -1)
end)

Section:NewButton("Fish Man", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1683.59998, 216, -333.299988, 1, 2.53821355e-08, 1.40738617e-13, -2.53821355e-08, 1, 3.42112827e-08, -1.39870266e-13, -3.42112827e-08, 1)
end)

Section:NewButton("Mountain", "ButtonInfo", function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2053.5, 492, -637, 1, 2.26101395e-08, 2.04295639e-14, -2.26101395e-08, 1, 3.047208e-08, -1.97405856e-14, -3.047208e-08, 1)
end)

local Tab = Window:NewTab("Players")
local PlayersSection = Tab:NewSection("TELEPORT TO Players")

players = {}

for i,v in pairs(game:GetService("Players"):GetChildren()) do
   table.insert(players,v.Name)
end

PlayersSection:NewDropdown("Select Player", " ", players, function(abc)
    Select = abc
end)


PlayersSection:NewButton("Refresh", " ", function()
    table.clear(players)
for i,v in pairs(game:GetService("Players"):GetChildren()) do
   table.insert(players,v.Name)
end
end)

PlayersSection:NewButton("Teleport", " ", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[Select].Character.HumanoidRootPart.CFrame
end)

PlayersSection:NewToggle("Auto Teleport", " ", function(a)
SpamTeleport1g = a
end)

spawn(function()
while wait() do
if SpamTeleport1g then
pcall(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[Select].Character.HumanoidRootPart.CFrame * CFrame.new(0,30,0)
end)
end
end
end)

PlayersSection:NewToggle("Bring Player", " ", function(a)
SpamTeleport1c = a
end)
    
spawn(function()
while wait() do
if SpamTeleport1c then
pcall(function()
game.Players[Select].Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

local Tab = Window:NewTab("GET ITEM")
local itemSection = Tab:NewSection("User_number after profile you")

itemSection:NewTextBox("Seastone Cestus", "", function(txt)
local A_1 = "Seastone Cestus"
local Event = game:GetService("Workspace").UserData[txt].UpdateMelee
Event:FireServer(A_1)
end)

local Tab = Window:NewTab("Setting")
local SettingSection = Tab:NewSection("Setting")

SettingSection:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.RightControl, function()
	Library:ToggleUI()
end)

local Tab = Window:NewTab("Auto farm")
local farmSection = Tab:NewSection("Auto farm")

farmSection:NewButton("Light", "ButtonInfo", function()

while wait(0.1) do
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-358.26531982422, 222.11312866211, -472.46112060547), Vector3.new(-0.5162478685379, -0.15350259840488, -0.84257054328918)),
        [4] = workspace.Rock,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
     
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-417.04028320312, 214.12658691406, -199.61256408691), Vector3.new(-0.96515822410583, -0.25610193610191, 0.053680088371038)),
        [4] = workspace.Enemies:FindFirstChild("Lv12 Thug"):FindFirstChild("Left Leg"),
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-75.010223388672, 213, -293.06854248047), Vector3.new(0.78645247220993, -0.35974085330963, -0.50207471847534)),
        [4] = workspace.IslandWindmill.Beach.Beach,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-75.010223388672, 213, -293.06854248047), Vector3.new(0.78645247220993, -0.35974085330963, -0.50207471847534)),
        [4] = workspace.IslandWindmill.Beach.Beach,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(63.991317749023, 221, -30.275924682617), Vector3.new(0.6120730638504, -0.087860263884068, 0.78590536117554)),
        [4] = workspace.IslandWindmill.Base.Grass.Grass,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(218.0140838623, 215.70497131348, 4.1675176620483), Vector3.new(0.73340916633606, -0.42937967181206, 0.52701431512833)),
        [4] = workspace.Enemies:FindFirstChild("Lv9 Bandit"):FindFirstChild("Left Arm"),
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-251.11801147461, 272, 348.22186279297), Vector3.new(-0.31219702959061, -0.13836766779423, 0.93988698720932)),
        [4] = workspace.IslandWindmill.OutterDune.Beach,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-993.73510742188, 283, 1624.4263916016), Vector3.new(-0.59242898225784, -0.25974464416504, 0.76260125637054)),
        [4] = workspace.IslandCaver.Stones.Stone,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-905.16833496094, 214, 1621.771484375), Vector3.new(0.52009379863739, -0.76283675432205, 0.38416501879692)),
        [4] = workspace.IslandCaver.Grass.Grass,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    
    wait(0.1)
    

    
    local args = {
        [1] = "LightPower2",
        [2] = "StopCharging",
        [3] = CFrame.new(Vector3.new(-1035.837890625, 214, 1510.5050048828), Vector3.new(-0.57756620645523, -0.6092734336853, -0.54332602024078)),
        [4] = workspace.IslandCaver.Grass.Grass,
        [5] = 100
    }
    
    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    end
end)

farmSection:NewButton("Rumble", "ButtonInfo", function()

while wait(0.1) do
local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-359.24087524414, 226.37106323242, -478.37158203125),
    [4] = workspace.Rock,
    [5] = 200,
    [6] = Vector3.new(-343.06158447266, 216.5, -439.70068359375)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-83.829093933105, 213, -294.02258300781),
    [4] = workspace.IslandWindmill.Beach.Beach,
    [5] = 188,
    [6] = Vector3.new(-128.67938232422, 216.5, -314.5989074707)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-83.829093933105, 213, -294.02258300781),
    [4] = workspace.IslandWindmill.Beach.Beach,
    [5] = 188,
    [6] = Vector3.new(-128.67938232422, 216.5, -314.5989074707)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-83.829093933105, 213, -294.02258300781),
    [4] = workspace.IslandWindmill.Beach.Beach,
    [5] = 188,
    [6] = Vector3.new(-128.67938232422, 216.5, -314.5989074707)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(217.2951965332, 213, 3.7251434326172),
    [4] = workspace.IslandWindmill.Beach.Beach,
    [5] = 200,
    [6] = Vector3.new(173.03219604492, 236.63011169434, -23.675079345703)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-250.8815612793, 272, 360.30731201172),
    [4] = workspace.IslandWindmill.OutterDune.Beach,
    [5] = 200,
    [6] = Vector3.new(-22.627199172974, 216.49995422363, 44.879180908203)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-416.06164550781, 213, -202.07725524902),
    [4] = workspace.IslandWindmill.Beach.Beach,
    [5] = 200,
    [6] = Vector3.new(-58.822944641113, 224.49995422363, -76.233093261719)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(65.235214233398, 214, -921.97888183594),
    [4] = workspace.Cave.Stone,
    [5] = 200,
    [6] = Vector3.new(32.107860565186, 217.5, -899.43988037109)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-985.06958007812, 283, 1610.5286865234),
    [4] = workspace.IslandCaver.Stones.Stone,
    [5] = 200,
    [6] = Vector3.new(-937.14587402344, 272.5, 1550.5992431641)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-906.60778808594, 214, 1621.8117675781),
    [4] = workspace.IslandCaver.Grass.Grass,
    [5] = 200,
    [6] = Vector3.new(-937.19506835938, 272.5, 1550.5926513672)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-1032.6613769531, 214, 1509.9426269531),
    [4] = workspace.IslandCaver.Grass.Grass,
    [5] = 200,
    [6] = Vector3.new(-939.29632568359, 272.5, 1548.5124511719)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(-1009.0948486328, 322, 1689.8887939453),
    [4] = workspace.IslandCaver.Stones.Stone,
    [5] = 200,
    [6] = Vector3.new(-938.93811035156, 272.5, 1549.4638671875)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))

wait(0.50)

local args = {
    [1] = "RumblePower2",
    [2] = "StopCharging",
    [3] = Vector3.new(77.15007019043, 223, -250.02792358398),
    [4] = workspace.IslandWindmill.SandMounds.Model.Beach,
    [5] = 200,
    [6] = Vector3.new(45.414310455322, 216.49995422363, -251.20835876465)
}

game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))
end
end)

farmSection:NewButton("Quake", "ButtonInfo", function()
-- Script generated by SimpleSpy - credits to exx#9394
while wait(0.1) do
local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.Rock,
    [4] = CFrame.new(Vector3.new(-365.74432373047, 225.73776245117, -477.5325012207), Vector3.new(0.28470024466515, -0.14880463480949, -0.94699680805206)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandWindmill.Beach.Beach,
    [4] = CFrame.new(Vector3.new(-87.648941040039, 213, -294.58609008789), Vector3.new(0.7351353764534, -0.46560508012772, 0.49273511767387)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandWindmill.SandMounds.Model.Beach,
    [4] = CFrame.new(Vector3.new(75.937728881836, 223, -253.43142700195), Vector3.new(-0.064422681927681, -0.54657047986984, 0.83493143320084)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandWindmill.Base.Grass.Grass,
    [4] = CFrame.new(Vector3.new(61.570350646973, 221, -31.109996795654), Vector3.new(0.79696768522263, -0.53143674135208, 0.2870846092701)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandWindmill.Beach.Beach,
    [4] = CFrame.new(Vector3.new(208.37385559082, 213, 7.732048034668), Vector3.new(0.86345362663269, -0.45437458157539, -0.21906964480877)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandWindmill.Beach.Beach,
    [4] = CFrame.new(Vector3.new(-425.48114013672, 213, -215.09509277344), Vector3.new(-0.97387915849686, -0.21704150736332, -0.066726833581924)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandWindmill.OutterDune.Beach,
    [4] = CFrame.new(Vector3.new(-248.10726928711, 272, 353.81106567383), Vector3.new(0.030227974057198, -0.91596406698227, 0.40012010931969)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandCaver.Stones.Stone,
    [4] = CFrame.new(Vector3.new(-994.05242919922, 283, 1621.1989746094), Vector3.new(-0.3858679831028, -0.79688268899918, 0.46484825015068)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandCaver.Grass.Grass,
    [4] = CFrame.new(Vector3.new(-1036.5325927734, 214, 1501.82421875), Vector3.new(-0.45734798908234, -0.82259160280228, -0.33789917826653)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.IslandCaver.Grass.Grass,
    [4] = CFrame.new(Vector3.new(-908.90026855469, 214, 1620.1252441406), Vector3.new(-0.20331089198589, -0.76694774627686, 0.60865092277527)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))

wait(0.50)

-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "QuakePower10",
    [2] = "StopCharging",
    [3] = workspace.Cave.Stone,
    [4] = CFrame.new(Vector3.new(100.59931945801, 214, -925.53265380859), Vector3.new(-0.41887265443802, -0.42189392447472, -0.80408412218094)),
    [5] = 100,
    [6] = Vector3.new(-302.34173583984, 243.59512329102, -93.936317443848)
}

game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))
end
end)

local farmSection = Tab:NewSection("Bring mod")

farmSection:NewToggle("Lv1 Crab", " ", function(a)
SpamTeleport0a = a
end)

spawn(function()
while wait() do
if SpamTeleport0a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv1 Crab"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv2 Angry Bob", " ", function(a)
SpamTeleport1a = a
end)
    
spawn(function()
while wait() do
if SpamTeleport1a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv2 Angry Bob"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv4 Boar", " ", function(a)
 SpamTeleport2a = a
end)
        
spawn(function()
while wait() do
if SpamTeleport2a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv4 Boar"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv4 Freddy", " ", function(a)
SpamTeleport3a = a
end)
           
spawn(function()
while wait() do
if SpamTeleport3a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv4 Freddy"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv9 Bandit", " ", function(a)
SpamTeleport4a = a
end)
               
spawn(function()
while wait() do
if SpamTeleport4a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv9 Bandit"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv12 Thug", " ", function(a)
SpamTeleport5a = a
end)
                   
spawn(function()
while wait() do
if SpamTeleport5a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv12 Thug"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv20 Thief", " ", function(a)
SpamTeleport6a = a
end)
                       
spawn(function()
while wait() do
if SpamTeleport6a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv20 Thief"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv20 Gunslinger", " ", function(a)
SpamTeleport7a = a
end)
                           
spawn(function()
while wait() do
if SpamTeleport7a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv20 Gunslinger"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv24 Gunslinger", " ", function(a)
SpamTeleport8a = a
end)
                               
spawn(function()
while wait() do
if SpamTeleport8a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv24 Gunslinger"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv36 Gunslinger", " ", function(a)
SpamTeleport9a = a
end)
                                   
spawn(function()
while wait() do
if SpamTeleport9a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv36 Gunslinger"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv40 Cave Demon", " ", function(a)
SpamTeleport10a = a
end)
                                       
spawn(function()
while wait() do
if SpamTeleport10a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv40 Cave Demon"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv42 Gunslinger", " ", function(a)
SpamTeleport11a = a
end)
                                           
spawn(function()
while wait() do
if SpamTeleport11a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv42 Gunslinger"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv50 Gunslinger", " ", function(a)
SpamTeleport12a = a
end)
                                               
spawn(function()
while wait() do
if SpamTeleport12a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv50 Gunslinger"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv200 Vokun", " ", function(a)
SpamTeleport13a = a
end)
                                                   
spawn(function()
while wait() do
if SpamTeleport13a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv200 Vokun"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv360 Bruno", " ", function(a)
SpamTeleport14a = a
end)
                                                       
spawn(function()
while wait() do
if SpamTeleport14a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv360 Bruno"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv440 Buster", " ", function(a)
SpamTeleport15a = a
end)
                                                           
spawn(function()
while wait() do
if SpamTeleport15a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv440 Buster"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv500 Bucky", " ", function(a)
SpamTeleport16a = a
end)
                                                               
spawn(function()
while wait() do
if SpamTeleport16a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv500 Bucky"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv8000 Gunner Captain", " ", function(a)
SpamTeleport17a = a
end)
                                                                   
spawn(function()
while wait() do
if SpamTeleport17a then
pcall(function()
    game:GetService("Workspace").Enemies["Lv8000 Gunner Captain"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)
  
--------------------------------------------------------------

farmSection:NewToggle("Lv3 Crab", " ", function(a)
SpamTeleport0b = a
end)
                                                                   
spawn(function()
while wait() do
if SpamTeleport0b then
pcall(function()
    game:GetService("Workspace").Enemies["Lv3 Crab"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
end)
end
end
end)

farmSection:NewToggle("Lv4 Crab", " ", function(a)
    SpamTeleport1b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport1b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv4 Crab"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end) 

farmSection:NewToggle("Lv5 Crab", " ", function(a)
    SpamTeleport2b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport2b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv5 Crab"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end) 

farmSection:NewToggle("Lv11 Boar", " ", function(a)
    SpamTeleport3b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport3b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv11 Boar"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv12 Boar", " ", function(a)
    SpamTeleport4b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport4b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv12 Boar"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv14 Boar", " ", function(a)
    SpamTeleport5b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport5b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv14 Boar"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv14 Bandit", " ", function(a)
    SpamTeleport6b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport6b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv14 Bandit"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv15 Thug", " ", function(a)
    SpamTeleport7b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport7b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv15 Thug"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv15 Bandit", " ", function(a)
    SpamTeleport8b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport8b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv15 Bandit"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv15 Boar", " ", function(a)
    SpamTeleport9b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport9b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv15 Boar"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv16 Boar", " ", function(a)
    SpamTeleport10b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport10b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv16 Boar"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv17 Thug", " ", function(a)
    SpamTeleport11b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport11b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv17 Thug"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv20 Thief", " ", function(a)
    SpamTeleport12b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport12b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv20 Thief"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv22 Thug", " ", function(a)
    SpamTeleport13b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport13b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv22 Thug"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv22 Angry Bobby", " ", function(a)
    SpamTeleport14b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport14b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv22 Angry Bobby"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv23 Thug", " ", function(a)
    SpamTeleport15b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport15b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv23 Thug"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv24 Fred", " ", function(a)
    SpamTeleport16b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport16b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv24 Fred"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv24 Thug", " ", function(a)
    SpamTeleport17b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport17b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv24 Thuga"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv24 Angry Bobbi", " ", function(a)
    SpamTeleport18b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport18b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv24 Angry Bobbi"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv28 Freyd", " ", function(a)
    SpamTeleport19b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport19b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv28 Freyd"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv28 Fredde", " ", function(a)
    SpamTeleport20b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport20b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv28 Fredde"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv28 Friedrich", " ", function(a)
    SpamTeleport21b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport21b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv28 Friedrich"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv29 Angry Bobber", " ", function(a)
    SpamTeleport22b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport22b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv29 Angry Bobber"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv29 Frued", " ", function(a)
    SpamTeleport23b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport23b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv29 Frued"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv30 Thug", " ", function(a)
    SpamTeleport24b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport24b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv30 Thug"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv32 Fredric", " ", function(a)
    SpamTeleport25b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport25b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv32 Fredric"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv32 Thief", " ", function(a)
    SpamTeleport26b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport26b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv32 Thief"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv34 Freddi", " ", function(a)
    SpamTeleport27b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport27b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv34 Freddi"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv35 Angry Bobb", " ", function(a)
    SpamTeleport28b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport28b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv35 Angry Bobb"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv40 Thug", " ", function(a)
    SpamTeleport29b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport29b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv40 Thug"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv186 Cave Demon", " ", function(a)
    SpamTeleport30b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport30b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv186 Cave Demon"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv188 Cave Demon", " ", function(a)
    SpamTeleport31b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport31b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv188 Cave Demon"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv198 Cave Demon", " ", function(a)
    SpamTeleport32b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport32b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv198 Cave Demon"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)

farmSection:NewToggle("Lv219 Cave Demon", " ", function(a)
    SpamTeleport33b = a
end)
                                                                       
spawn(function()
    while wait() do
    if SpamTeleport33b then
    pcall(function()
        game:GetService("Workspace").Enemies["Lv219 Cave Demon"].HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-5)
    end)
    end
    end
end)
