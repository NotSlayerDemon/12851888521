if game.PlaceId == 12851888521 then
    local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
    local Window = OrionLib:MakeWindow({Name = "Develeper Version of NSD HUB's Punch Wall Simulator", HidePremium = false, IntroEnabled = false,IntroText = "Welcome Back NSD", SaveConfig = true, ConfigFolder = "PWSTest"})
    local player = game.Players.LocalPlayer
  
    -- Values
    getgenv().AutoGetWins = true
    getgenv().AutoGetStrength = true
    getgenv().BestEggOpen3 = true
    getgenv().BestEggOpen1 = true
    getgenv().RandomPotion = true
    getgenv().AutoRebirth = true
   
    function AutoGetWins()
        while getgenv().AutoGetWins == true do
        wait(1.25)
        local player = game.Players.LocalPlayer
        local TpLocation
            
        function teleport(loc) -- Nymphoria on v3rmillion.net
            TpLocation = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = loc
        end

        
        teleport(CFrame.new(-341.3334655761719, 3.2828691005706787, -1294.6268310546875)) -- 50k
        wait(0.5)
        teleport(CFrame.new(-271.3183288574219, 3.3800456523895264, -1585.685302734375)) -- 25k
        wait(0.5)
        teleport(CFrame.new(-185.82351684570312, 3.380322217941284, -1609.427001953125)) -- 15k
        wait(0.5)
        teleport(TpLocation)
        end
    end
        
    function AutoGetStrength()
        while getgenv().AutoGetStrength == true do
        wait(0.1)
        local player = game.Players.LocalPlayer
        local TpLocation
      
        function teleport(loc) -- Nymphoria on v3rmillion.net
            TpLocation = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = loc
        end

        teleport(CFrame.new(-329.8829345703125, 2.8555665016174316, -1462.1856689453125))
        wait(0.1)
        teleport(CFrame.new(-351.64093017578125, 2.8559553623199463, -1458.0946044921875))
        wait(0.1)
        teleport(CFrame.new(-369.8104248046875, 2.856020212173462, -1455.268798828125))
        wait(0.1)
        teleport(TpLocation)
        end
    end
    
    function BestEggOpen1()
        while getgenv().BestEggOpen1 == true do
        wait(0)
        local args = {
            [1] = 324,
            [2] = "Candy Egg"
        }

        game:GetService("ReplicatedStorage"):FindFirstChild("functions-shared/network@GlobalFunctions"):FindFirstChild("s:openEgg"):FireServer(unpack(args))
        end    
    end
    
    function BestEggOpen3()
        while getgenv().BestEggOpen3 == true do
        wait(0)
        local args = {
            [1] = 606,
            [2] = "Candy Egg"
        }

        game:GetService("ReplicatedStorage"):FindFirstChild("functions-shared/network@GlobalFunctions"):FindFirstChild("s:openTripleEgg"):FireServer(unpack(args))
        end    
    end

    function RandomPotion()
        while getgenv().RandomPotion == true do
        wait(0)
        local args = {
            [1] = 174
        }

        game:GetService("ReplicatedStorage"):FindFirstChild("functions-shared/network@GlobalFunctions"):FindFirstChild("s:claimCauldronReward"):FireServer(unpack(args))
        wait(480)
        end
    end
    
    function AutoRebirth()
        while getgenv().AutoRebirth == true do
        wait(0.5)
        local args = {
            [1] = 344
        }

        game:GetService("ReplicatedStorage"):FindFirstChild("functions-shared/network@GlobalFunctions"):FindFirstChild("s:rebirth"):FireServer(unpack(args))
        end
    end
    -- Tabs
    local PWSTab = Window:MakeTab({
        Name = "Farm like a exploiter Tehe would do XD",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })
    
    
    -- Toggles
    PWSTab:AddToggle({
        Name = "-- Auto Get Wins --",
        Default = false,
        Callback = function(Value)
            getgenv().AutoGetWins = Value
            AutoGetWins()
        end
    })
    
    PWSTab:AddToggle({
        Name = "-- Auto Get Strength --",
        Default = false,
        Callback = function(Value)
            getgenv().AutoGetStrength = Value
            AutoGetStrength()
        end
          
    }) 
    
    PWSTab:AddToggle({
        Name = "-- Auto Rebirth --",
        default = false,
        Callback = function(Value)
            getgenv().AutoRebirth = Value
            AutoRebirth()
        end
    })

    PWSTab:AddToggle({
        Name = "Open 1 Of BestEgg in the Game", -- (if game is updated change the script)
        default = false,
        Callback = function(Value)
            getgenv().BestEggOpen1 = Value
            BestEggOpen1()
        end
    })

    PWSTab:AddToggle({
        Name = "Open 3 Of BestEgg in the Game", -- (if game is updated change the script)
        default = false,
        Callback = function(Value)
            getgenv().BestEggOpen3 = Value
            BestEggOpen3()
        end
    })
    PWSTab:AddToggle({
        Name = "Random Potion Every 10min",
        Default = false,
        Callback = function(Value)
            getgenv().RandomPotion = Value
            RandomPotion()
        end
    })
    
    OrionLib:MakeNotification({
        Name = "Ty for using the my script",
        Content = "You Executed me "..Player.Name..".",
        Image = "rbxassetid://4483345998",
        Time = 5
    })
end
OrionLib:Init()-- End of this script 
