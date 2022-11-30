
#### Anime Adventures
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/NewArponAA(MOBILE)"))()
```



#### Da Hood/Hood Custom
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/MajuNuko/SIll/main/MIKO.silentaim.gg/credsFuckedUrmom"))()
DaHoodSettings.Prediction = 0.14573
Aiming.TargetPart = {"Head", "UpperTorso", "LowerTorso", "HumanoidRootPart", "RightFoot", "LeftFoot"}
Aiming.FOV = 35.3
Aiming.FOVSides = 25
Aiming.HitChance = 110
Aiming.ShowFOV = false
-- dont Mess with Shit below --
local RunService = game:GetService("RunService")

RunService.Heartbeat:Connect(function()
    pcall(function()
        for i,v in pairs(game.Players:GetChildren()) do
            if v.Name ~= game.Players.LocalPlayer.Name then
                local hrp = v.Character.HumanoidRootPart
                hrp.Velocity = Vector3.new(hrp.Velocity.X, 0, hrp.Velocity.Z)    
                hrp.AssemblyLinearVelocity = Vector3.new(hrp.Velocity.X, 0, hrp.Velocity.Z)   
            end
        end
    end)
end)
```
