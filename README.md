


local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

game:GetService("Players").LocalPlayer.Character.Weapons:FireServer()
game:GetService("Players").LocalPlayer.Character.Weapons:FireServer()

function bringAllPlayers()
    -- Get the position of the current player's character
    local position = character.HumanoidRootPart.Position

    -- Loop through all players
    for _, targetPlayer in pairs(game.Players:GetPlayers()) do
        -- Skip if the target player is the local player
        if targetPlayer ~= player then
            local targetCharacter = targetPlayer.Character
            if targetCharacter then
                -- Move the target player's character to the position
                targetCharacter:SetPrimaryPartCFrame(CFrame.new(position + Vector3.new(0, 25, -25)))
            end
        end
    end
end


spawn(function()
    while wait() do
    if _G.bringAllPlayers then
    pcall(function()
        bringAllPlayers()

    end)
    end
    end
end)




function AttackPlayer()
    local position = character.HumanoidRootPart.Position

    for _, targetPlayera in pairs(game.Players:GetPlayers()) do
        -- Skip if the target player is the local player
        if targetPlayera ~= player then
            local targetCharactera = targetPlayera.Character
            if targetCharactera then
                game:GetService("Players").LocalPlayer.Character:FindFirstChild("Cannon Ball").RemoteEvent:FireServer(CFrame.new(position + Vector3.new(0, 25, -25)) * CFrame.Angles(-0, 0, -0), targetCharactera.HumanoidRootPart)
    
            end
        end
    end
end

spawn(function()
    while wait() do
    if _G.AttackPlayer then
    pcall(function()
        AttackPlayer()

    end)
    end
    end
end)

function bringAllMonster()

    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
    local position = character.HumanoidRootPart.Position
    
    for _, monster in pairs(workspace.Enemies:GetDescendants()) do
        if monster:IsA("Model") and monster:FindFirstChild("Humanoid") then
            monster:SetPrimaryPartCFrame(CFrame.new(position + Vector3.new(0, 25, -25)))
        end
    end
end


spawn(function()
    while wait() do
    if _G.bringAllMonster then
    pcall(function()
        bringAllMonster()

    end)
    end
    end
end)

