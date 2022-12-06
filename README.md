## Random scripts i found in the internet (Credits to owner of the source code)

#### Anime Adventures
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/AnimeAdventure(FixTouch)"))()
```

#### Da Hood/Hood Custom (Mobile)
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/MobileSilentAim"))()
DaHoodSettings.Prediction = 0.181
Aiming.TargetPart = {"Head", "UpperTorso", "LowerTorso", "HumanoidRootPart", "RightFoot", "LeftFoot"}
Aiming.FOV = 50
Aiming.FOVSides = 25
Aiming.HitChance = 110
Aiming.ShowFOV = true

-- DONT MESS WITH SHIT BELOW -- 
_G.PRED = .00225
game:GetService("RunService").RenderStepped:Connect(function()

    local ping = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()
    local Value = tostring(ping)
    local pingValue = Value:split(" ")
    local PingNumber = pingValue[1]
    
    DaHoodSettings.Prediction = _G.PRED * PingNumber

end)
```

#### Da Hood/Hood Custom (PC)
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/SilentAim(Settings)"))()
DaHoodSettings.Prediction = 0.181
Aiming.TargetPart = {"Head", "UpperTorso", "LowerTorso", "HumanoidRootPart", "RightFoot", "LeftFoot"}
Aiming.FOV = 10
Aiming.FOVSides = 25
Aiming.HitChance = 110
Aiming.ShowFOV = true

-- DONT MESS WITH SHIT BELOW -- 
_G.PRED = .00225
game:GetService("RunService").RenderStepped:Connect(function()

    local ping = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()
    local Value = tostring(ping)
    local pingValue = Value:split(" ")
    local PingNumber = pingValue[1]
    
    DaHoodSettings.Prediction = _G.PRED * PingNumber

end)
```

#### Arsenal
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/ArsenalScript"))()
```

#### CamLock(FPSGUI)
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/H4KKDOG/Skid-Script/main/CamLock(DH)"))()
```
