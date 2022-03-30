# DF-Power-
local Tool = script.Parent

Tool.Activated:Connect (function()
    local Character = Tool.Parent
    local Player = game.play:GetPlayerFromCharacter(Character)
    if player then
        local leaderstats = player:FindFirstChild("leaderstats")
        if leaderstats then
            local DF = leaderstats:FindFirstChild("DF")
            if DF then
                DF.Valur = "Mera Mera"
