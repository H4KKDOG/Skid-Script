########## Credits to all owner of main source code i use
#### Anime Adventures
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/AnimeAdventure(FixTouch)"))()
```
#### Da Hood/Hood Custom
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/MobileSilentAim"))()
DaHoodSettings.Prediction = 0.181
Aiming.TargetPart = {"Head", "UpperTorso", "LowerTorso", "HumanoidRootPart", "RightFoot", "LeftFoot"}
Aiming.FOV = 40
Aiming.FOVSides = 25
Aiming.HitChance = 110
Aiming.ShowFOV = true
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
#### Arsenal
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/ArsenalScript"))()
```
