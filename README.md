while true do
    game:GetService("ReplicatedStorage"):WaitForChild("AddStaminaEvent"):FireServer()
    task.wait(0.1)
end
