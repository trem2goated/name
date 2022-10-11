local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("jailbreak gui", "Sentinel")

--MAIN
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Main")


MainSection:NewButton("Auto rob", "it well auto rob ", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/wawsdasdacx/ohascriptnrrewading/main/jbsaxcriptidk1"))()
end)


MainSection:NewButton("tp out of jail", "tp out of jail", function()
    game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(239.09440612793, 18.738416671753, 1179.3385009766)
wait(0.1)
local ggg;
ggg = game.Players.LocalPlayer.Character.HumanoidRootPart:GetPropertyChangedSignal("CFrame"):connect(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(239.09440612793, 18.738416671753, 1179.3385009766)
    wait(1)
    ggg:Disconnect()
    wait(0.5)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(252.56745910645, 18.565673828125, 1185.0828857422)
end)
end)


MainSection:NewButton("get keycard", "u well not see the keycard but game well read that u have it", function()
    local plrUtils = game:GetService("ReplicatedStorage").Game.PlayerUtils
local oldHasKey = require(plrUtils).hasKey
require(plrUtils).hasKey = function() 
    return true
end
end)



-- LOCAL PLAYER 
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")

PlayerSection:NewSlider("Walk speed", "makes u walk more fast", 500, 16, function(s) -- 500 (MaxValue) | 16 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("Jumppower", "makes u jump more high", 350, 50, function(s) -- 350 (MaxValue) | 50 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)



-- TROLL
local Troll = Window:NewTab("Troll")
local TrollSection = Troll:NewSection("Troll")
