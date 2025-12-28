return function(player, power)
    local character = player.Character or player.CharacterAdded:Wait()
    local humanoid = character:WaitForChild("Humanoid")
    humanoid.JumpPower = power or 590
    print(player.Name .. "のジャンプ力を" .. humanoid.JumpPower .. "に変更しました！")
end
