
if game.PlaceId == 3237168 then    --- placeid check ---
    repeat wait() until game:IsLoaded() 
    repeat wait() until game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") ~= nil
    
    
    --[[
     function LightSpamer(Targets)
        local args = {
            [1] = tonumber(serializeTable(remotes)),
            [2] = "LightPower2",
            [3] = "StartCharging",
            [4] = CFrame.new(1099.5858154296875, 221, -3480.406005859375, 0.9999545812606812, 0.005102770868688822, -0.008057218044996262, -4.656613428188905e-10, 0.8448255062103271, 0.5350419878959656, 0.009537139907479286, -0.5350176692008972, 0.844787061214447),
            [5] = workspace:WaitForChild("IslandSandCastle"):WaitForChild("RaisedSand"):WaitForChild("RaisedSandBase"):WaitForChild("Real"),
            [9] = "Left"
        }
        game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
        wait(.1)
        local args = {
            [1] = tonumber(serializeTable(remotes)),
            [2] = "LightPower2",
            [3] = "StopCharging",
            [4] = CFrame.new(Targets.HumanoidRootPart.Position),
            [5] = Targets.HumanoidRootPart,
            [6] = math.huge
        }
        game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
    end
    ]]--
    
    
    

    local spawnbox = game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase
    
    
    
    local NamePlayer = game.Players.LocalPlayer.Name
    
    
    local colors = {
        SchemeColor = Color3.fromRGB(65, 110, 242),
        Background = Color3.fromRGB(0, 0, 0),
        Header = Color3.fromRGB(0, 0, 0),
        TextColor = Color3.fromRGB(83, 161, 245),
        ElementColor = Color3.fromRGB(0, 0, 0)
    }
    
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    local Window = Library.CreateLib(" 🐇                      S͢a͢v͢i͢t͢a͢r͢ H͢u͢b͢ : O͢n͢e͢ P͢i͢e͢c͢e͢ L͢e͢g͢e͢n͢d͢a͢r͢y͢                   🐇 ", colors)
    local samtab = Window:NewTab("Sam")
    local samsec = samtab:NewSection("Sam")
    local Generaltab = Window:NewTab("General")
    local generalsec = Generaltab:NewSection("LocalPlayer")
    local fishingsec = Generaltab:NewSection("Fishing")
    local fruitfarmtab = Window:NewTab("Auto Farm's")
    local Fruitfarmsec = fruitfarmtab:NewSection("AutoFarm's")
    local teleporttab = Window:NewTab("Teleport")
    local teleportsec = teleporttab:NewSection("Island")
    local drinktab = Window:NewTab("Drinks")
    local drinksec = drinktab:NewSection("BuyDrinks")
    local killplayerstab = Window:NewTab("Players Related")
    local killplayersec = killplayerstab:NewSection("1st")
    local killplayersec2 = killplayerstab:NewSection("2nd")
    local hakitab = Window:NewTab("Haki")
    local hakisec = hakitab:NewSection("")
    local Sacrificetab = Window:NewTab("Sacrification")
    local Sacrificesec = Sacrificetab:NewSection("Sacrifice")
    local Stealtab = Window:NewTab("Steal fruit")
    local Stealsec = Stealtab:NewSection("Steal fruit")
    local misctab = Window:NewTab("Misc")
    local miscsec = misctab:NewSection("OhtherScript")
    local miscsec2 = misctab:NewSection("Misc")
    
    
    
    
    
    
    local Monsterlist = {
        "Lv1 Crab",
        "Lv2 Angry Bob",
        "Lv3 Crab",
        "Lv4 Boar",
        "Lv4 Crab",
        "Lv4 Freddy",
        "Lv5 Crab",
        "Lv9 Bandit",
        "Lv11 Boar",
        "Lv12 Thug",
        "Lv12 Boar",
        "Lv14 Boar",
        "Lv14 Bandit",
        "Lv15 Thug",
        "Lv15 Bandit",
        "Lv15 Boar",
        "Lv16 Boar",
        "Lv17 Thug",
        "Lv20 Gunslinger",
        "Lv20 Thief",
        "Lv22 Thug",
        "Lv22 Angry Bobby",
        "Lv23 Thug",
        "Lv24 Fred",
        "Lv24 Thug",
        "Lv24 Angry Bobbi",
        "Lv24 Gunslinger",
        "Lv28 Freyd",
        "Lv28 Fredde",
        "Lv28 Friedrich",
        "Lv29 Angry Bobber",
        "Lv29 Frued",
        "Lv30 Thug",
        "Lv32 Fredric",
        "Lv32 Thief",
        "Lv34 Freddi",
        "Lv35 Angry Bobb",
        "Lv36 Gunslinger",
        "Lv40 Cave Demon",
        "Lv40 Thug",
        "Lv42 Gunslinger",
        "Lv50 Gunslinger",
        "Lv186 Cave Demon",
        "Lv188 Cave Demon",
        "Lv198 Cave Demon",
        "Lv200 Vokun",
        "Lv219 Cave Demon",
        "Lv360 Bruno",
        "Lv440 Buster",
        "Lv500 Bucky",
        "Lv8000 Gunner Captain"
    }
    
    
    local MonsterNoIncaveGunner = {
        "Lv1 Crab",
        "Lv2 Angry Bob",
        "Lv3 Crab",
        "Lv4 Boar",
        "Lv4 Crab",
        "Lv4 Freddy",
        "Lv5 Crab",
        "Lv9 Bandit",
        "Lv11 Boar",
        "Lv12 Thug",
        "Lv12 Boar",
        "Lv14 Boar",
        "Lv14 Bandit",
        "Lv15 Thug",
        "Lv15 Bandit",
        "Lv15 Boar",
        "Lv16 Boar",
        "Lv17 Thug",
        "Lv20 Gunslinger",
        "Lv20 Thief",
        "Lv22 Thug",
        "Lv22 Angry Bobby",
        "Lv23 Thug",
        "Lv24 Fred",
        "Lv24 Thug",
        "Lv24 Angry Bobbi",
        "Lv24 Gunslinger",
        "Lv28 Freyd",
        "Lv28 Fredde",
        "Lv28 Friedrich",
        "Lv29 Angry Bobber",
        "Lv29 Frued",
        "Lv30 Thug",
        "Lv32 Fredric",
        "Lv32 Thief",
        "Lv34 Freddi",
        "Lv35 Angry Bobb",
        "Lv36 Gunslinger",
        "Lv40 Cave Demon",
        "Lv40 Thug",
        "Lv42 Gunslinger",
        "Lv50 Gunslinger",
        "Lv186 Cave Demon",
        "Lv188 Cave Demon",
        "Lv198 Cave Demon",
        "Lv200 Vokun",
        "Lv219 Cave Demon",
    }
    
    
    local MonsterForLightSky = {
        "Lv1 Crab",
        "Lv2 Angry Bob",
        "Lv3 Crab",
        "Lv4 Boar",
        "Lv4 Crab",
        "Lv4 Freddy",
        "Lv5 Crab",
        "Lv9 Bandit",
        "Lv11 Boar",
        "Lv12 Thug",
        "Lv12 Boar",
        "Lv14 Boar",
        "Lv14 Bandit",
        "Lv15 Thug",
        "Lv15 Bandit",
        "Lv15 Boar",
        "Lv16 Boar",
        "Lv17 Thug",
        "Lv20 Gunslinger",
        "Lv20 Thief",
        "Lv22 Thug",
        "Lv22 Angry Bobby",
        "Lv23 Thug",
        "Lv24 Fred",
        "Lv24 Thug",
        "Lv24 Angry Bobbi",
        "Lv24 Gunslinger",
        "Lv28 Freyd",
        "Lv28 Fredde",
        "Lv28 Friedrich",
        "Lv29 Angry Bobber",
        "Lv29 Frued",
        "Lv30 Thug",
        "Lv32 Fredric",
        "Lv32 Thief",
        "Lv34 Freddi",
        "Lv35 Angry Bobb",
        "Lv36 Gunslinger",
        "Lv40 Thug",
        "Lv42 Gunslinger",
        "Lv50 Gunslinger",
        "Lv360 Bruno",
        "Lv440 Buster",
        "Lv500 Bucky",
        "Lv8000 Gunner Captain"
    }
    
    
    getgenv().Table_money_yoru = {
        "Lv219 Cave Demon",
        "Lv186 Cave Demon",
        "Lv188 Cave Demon",
        "Lv198 Cave Demon",
        "Lv42 Gunslinger",
        "Lv50 Gunslinger",
        "Lv20 Gunslinger",
        "Lv36 Gunslinger",
        "Lv24 Gunslinger",
        "Lv248 Gunslinger Guard",
        "Lv244 Gunslinger Guard",
        "Lv256 Bandit Guard",
        "Lv243 Bandit Guard",
        "Lv258 Gunslinger Guard",
        "Lv243 Gunslinger Guard",
        "Lv250 Bandit Guard",
        "Lv259 Bandit Guard",
        "Lv244 Gunslinger Guard",
        "Lv251 Gunslinger Guard",
        "Lv248 Bandit Guard",
        "Lv243 Gunslinger Guard",
        "Lv244 Bandit Guard",
        "Lv252 Gunslinger Guard",
        "Lv248 Bandit Guard",
        "Lv257 Bandit Guard",
        "Lv246 Bandit Guard",
        "Lv251 Bandit Guard",
        "Lv252 Gunslinger Guard",
        "Lv259 Gunslinger Guard",
        "Lv249 Gunslinger Guard",
        "Lv251 Gunslinger Guard",
        "Lv253 Bandit Guard",
        "Lv252 Bandit Guard",
        "Lv255 Bandit Guard",
        "Lv247 Gunslinger Guard",
        "Lv250 Bandit Guard",
        "Lv248 Bandit Guard",
        "Lv243 Gunslinger Guard",
        "Lv251 Bandit Guard",
        "Zombie"
    
    }
    ---------------------------------local-----------------------------------
    
    local plr = game.Players.LocalPlayer
    local char = plr.Character
    
    if not game:GetService("Workspace"):FindFirstChild("SafePlace") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "SafePlace"
        e.Size = Vector3.new(200, 2, 200)
        e.Position = Vector3.new(-7926.89208984375, 3179.349853515625, -6294.57861328125)
        e.Anchored = true
    end
    
    if not game:GetService("Workspace"):FindFirstChild("SafeModePlaceOne") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "SafeModePlaceOne"
        e.Size = Vector3.new(7, 3, 7)
        e.Position = Vector3.new(-52082.20025634765625, 60000.7587890625, 925790.8968505859375)
        e.Anchored = true
    end
    
    if not game:GetService("Workspace"):FindFirstChild("SafeModePlaceTwo") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "SafeModePlaceTwo"
        e.Size = Vector3.new(7, 3, 7)
        e.Position = Vector3.new(-2000.20025634765625, 60000.7587890625, -2500.8968505859375)
        e.Anchored = true
    end
    
    if not game:GetService("Workspace"):FindFirstChild("SafeModePlaceThree") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "SafeModePlaceThree"
        e.Size = Vector3.new(7, 3, 7)
        e.Position = Vector3.new(-19852.20025634765625, 60000.7587890625, 99999.8968505859375)
        e.Anchored = true
    end
    
    if not game:GetService("Workspace"):FindFirstChild("SafeModePlaceFour") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "SafeModePlaceFour"
        e.Size = Vector3.new(7, 3, 7)
        e.Position = Vector3.new(-9852.20025634765625, 60000.7587890625, -412412.8968505859375)
        e.Anchored = true
    end
    
    if not game:GetService("Workspace"):FindFirstChild("SafeModePlaceFive") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "SafeModePlaceFive"
        e.Size = Vector3.new(7, 3, 7)
        e.Position = Vector3.new(-985226.20025634765625, 10000.7587890625, -4444.8968505859375)
        e.Anchored = true
    end
    
    if not game:GetService("Workspace"):FindFirstChild("SafeModePlaceSix") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "SafeModePlaceSix"
        e.Size = Vector3.new(7, 3, 7)
        e.Position = Vector3.new(-985226.20025634765625, 10000.7587890625, -4444.8968505859375)
        e.Anchored = true
    end
    if not game:GetService("Workspace"):FindFirstChild("LightFarmPlace") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "LightFarmPlace"
        e.Size = Vector3.new(5, 2, 5)
        e.Position = Vector3.new(2019.0499267578125, 2688.61474609375, 1404.7730712890625)
        e.Anchored = true
    end
    if not game:GetService("Workspace"):FindFirstChild("FishingPlace") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "FishingPlace"
        e.Size = Vector3.new(6, 2, 6)
        e.Position = Vector3.new(-20477.1171875, 212.45838928222656, -20478.75)
        e.Anchored = true
    end
    
    
    
    -----------------------------------------------------------------------------------------
    
    function BombKill(Targets)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,5,0)
        local args = {
            [1] = tonumber(serializeTable(remotes)),
            [2] = "BombPower5",
            [3] = "StartCharging",
            [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
            [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
            [7] = "Right"
        }
                                        
        game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
        wait(.1)
        local args = {
            [1] = tonumber(serializeTable(remotes)),
            [2] = "BombPower5",
            [3] = "StopCharging",
            [4] = CFrame.new(Targets.HumanoidRootPart.Position),
            [5] = Targets.HumanoidRootPart,
            [6] = math.huge
        }
                                        
        game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
    end


    local remotes = {}
        local a
        a=hookmetamethod(game,"__namecall",function(self,...)
            local args = {...}
            local method = getnamecallmethod()
            if method == "FireServer" or method == "InvokeServer" then
                if self.Name == "RemoteEvent" and args[3] == "StopCharging" then
                    remotes[self.Name] = args[1]
                    return a(self,unpack(args))
                end
            end
              return a(self,...)
        end)
        
        local attackremote = {}
        
        local a
    
        a=hookmetamethod(game,"__namecall",function(self,...)
            local args = {...}
            local method = getnamecallmethod()
            if method == "FireServer" or method == "InvokeServer" then
                if self.Name == "RequestAnimation" then
                    attackremote[self.Name] = args[1]
                    return a(self,unpack(args))
                end
            end
              return a(self,...)
        end)
    
        function serializeTable(val, name, skipnewlines, depth)
           skipnewlines = skipnewlines or false
           depth = depth or 0
        
           local tmp = string.rep("", depth)
        
           if name then tmp = tmp end
        
           if type(val) == "table" then
               tmp = tmp .. (not skipnewlines and "" or "")
        
               for k, v in pairs(val) do
                   tmp =  tmp .. serializeTable(v, k, skipnewlines, depth + 1) .. (not skipnewlines and "" or "")
               end
        
               tmp = tmp .. string.rep("", depth) 
           elseif type(val) == "number" then
               tmp = tmp .. tostring(val)
           elseif type(val) == "string" then
               tmp = tmp .. string.format("%q", val)
           elseif type(val) == "boolean" then
               tmp = tmp .. (val and "true" or "false")
           elseif type(val) == "function" then
               tmp = tmp  .. "func: " .. debug.getinfo(val).name
           else
               tmp = tmp .. tostring(val)
           end
        
           return tmp
        end
    
        local mt = getrawmetatable(game)
        local namecall = mt.__namecall
        local setreadonly = setreadonly or make_writable
    
    
        setreadonly(mt, false)
    
        mt.__namecall = newcclosure(function(self, ...)
            local args = {...}
            local arguments = args
            local a = {}
            for i = 1, #arguments - 1 do
                a[i] = arguments[i]
            end
            local method = getnamecallmethod()
    
            if method == 'FireServer' or method == "InvokeServer" then
                if self.Name == 'Drown' and getgenv().NodameWater then
                    if args[1] then
                        return nil
                    end
                end
            end
            
            return namecall(self, ...)    
        end)
    
        setreadonly(mt, true)
    
        local a
        a=hookmetamethod(game,"__namecall",function(self,...)
        local args = {...}
        local method = getnamecallmethod()
        if method == "FireServer" or method == "InvokeServer" then
            if self.Name == "RemoteEvent" and args[3] == "StopCharging" and getgenv().Skill1 then
                args[6] = 100
                return a(self,unpack(args))
            end
        end
          return a(self,...)
        end)
    -------------------------------------------------------------------------genaraltab(top)-------------------------------------------------------------------------
    
    
    
    function DropCompass()
        for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
            if v.Name == "Compass" then
                v.Parent = game.Players.LocalPlayer.Character
                v.Parent = workspace
            end
        end
    end
    function SafeZone()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7926.89208984375, 3182.349853515625, -6294.57861328125)
     end
    
    generalsec:NewButton("SafeZone", false, function()
        SafeZone()
    end)
    
    generalsec:NewButton("Anti AFK", false, function()
        for i,v in pairs(getconnections(game:GetService("Players").LocalPlayer.Idled)) do
            v:Disable()
                print("Anti AFK Enabled!")
         end
    end)
    
    generalsec:NewButton("Affinity UI", false, function()
        fireclickdetector(game:GetService("Workspace").Merchants.AffinityMerchant.Clickable.ClickDetector)
    end)
    local ListMods = {
        "Foltix",
        "VaporConduct",
        "ElianJoestar",
        "Farquanetta",
        "alligatorwithaguitar ",
        "Cythex",
        "MarcusVetarus",
        "BowTiedPony",
        "EtanaruSky",
        "FoxKingFab",
        "Lxxt0",
        "mariobros38",
        "Natsu_dragn331",
        "Quixotize",
        "reki_tf2",
        "TheWrightDefense",
        "Tiptop98",
        "TrashPanda2361",
        "vlonedd",
        "VortexFragmented",
        "YourDadAKABIgPoppa",
        "Zomkittz",
        "Oblivic",
        "CudlesstheCat",
        "EtanaruSky",
        "Elianmc1s",
        "AzureXoten",
        "ArchaicBread",
        "Americanflag",
        "Bige0n",
        "Davida3rd",
        "BowTiedPony"
    }
    
    generalsec:NewToggle("Anti Mods", false, function(s)
        getgenv().AntiMods = s
        
    end)
    
    
    spawn(function()
        while wait() do
            pcall(function()
                if notgetgenv().AntiMods then return end;
                for _, Value in pairs(game.Players:GetChildren()) do
                    if table.find(ListMods, Value.Name) then
                        game.Players.LocalPlayer:Kick("I Found Mods In This Server!");
                    end
                end
            end)
        end
    end);
    
    
    generalsec:NewToggle("Safety Mode", false, function(state)
        getgenv().SafeMode = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if not getgenv().SafeMode then return end;
                local tp = game.Players.LocalPlayer.Character.HumanoidRootPart
                tp.CFrame = CFrame.new(-52082.20025634765625, 60003.7587890625, 925790.8968505859375)
                wait(0.000001)
                tp.CFrame = CFrame.new(-2000.20025634765625, 60003.7587890625, -2500.8968505859375)
                wait(0.000001)
                tp.CFrame = CFrame.new(-19852.20025634765625, 60003.7587890625, 99999.8968505859375)
                wait(0.000001)
                tp.CFrame = CFrame.new(-9852.20025634765625, 60003.7587890625, -412412.8968505859375)
                wait(0.000001)
                tp.CFrame = CFrame.new(-985226.20025634765625, 10003.7587890625, -4444.8968505859375)
                wait(0.000001)
                tp.CFrame = CFrame.new(-985226.20025634765625, 10003.7587890625, -4444.8968505859375)
            end)
        end
    end)
             
    
    
    
    
    generalsec:NewToggle("AutoSpawn", false, function(state)
        getgenv().AutoSpawn = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().AutoSpawn then
                    if not game.Players.LocalPlayer.PlayerGui.Load.Frame.Visible then return end;
                    wait(1)
                    firesignal(game.Players.LocalPlayer.PlayerGui.Load.Frame.Load.MouseButton1Click);
                end
            end)
        end
    end)
    
    generalsec:NewToggle("Noclip", false, function(state)
        getgenv().noclip = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().noclip then
                    local player = game.Players.LocalPlayer
                    local character = player.Character or player.CharacterAdded:Wait()
                    repeat wait()
                        if getgenv().noclip then
                            for _, v in pairs(character:GetDescendants()) do
                                if v:IsA("BasePart") then
                                    v.CanCollide = false
                                end
                            end
                        end
                    until game.Players.LocalPlayer.Character.Humanoid.Health or getgenv().noclip == false
                end
            end)
        end
    end)
    
    local Weaponlist = {}
    
    for _,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
        if v:IsA("Tool") then
            table.insert(Weaponlist,v.Name)
        end
    end
    
    
    generalsec:NewDropdown("ChooseWeapons", false, Weaponlist, function(currentOption)
        getgenv().Weapon = currentOption
    end)
    
    generalsec:NewButton("Refresh Weapons", false, function()
        table.clear(Weaponlist)
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v:IsA("Tool") then
                table.insert(Weaponlist,v.Name)
            end
        end
    end)
    
    
    
    generalsec:NewToggle("AutoEquip", false, function(state)
        getgenv().AutoEquip = state
    end)
    
    
    
    generalsec:NewToggle("AutoActiveWeapon", false, function(state)
        getgenv().AutoHit = state
    end)
    
    function Click()
        game:GetService("VirtualUser"):ClickButton1(Vector2.new(99999, 99999))
    end
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().AutoHit then
                    Click()
                end
            end)
        end
    end)
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().AutoEquip then
                    game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(getgenv().Weapon))
                end
            end)
        end
    end)
    
       
    generalsec:NewToggle("NoCoolDownSkill", false, function(state)
        getgenv().NCDskill = state
    end)
    
    spawn(function()
        repeat wait() until getgenv().NCDskill == true or getgenv().NodameWater == true;
        local Old;
        Old = hookmetamethod(game, "__namecall", function(self, ...)
            if getnamecallmethod() == "FireServer" then
                local Args = {...};
                if getgenv().NCDskill and table.find(Args, "StopCharging") then
                    return spawn(Old(self, ...));
                end;
                if getgenv().NodameWater and not checkcaller() and self.Name == "Drown" and Args[1] == "NOPLS" then
                    return;
                end
            end
            return Old(self, ...);
        end)
    end)
    
    generalsec:NewToggle("Max Charger Skill", false, function(state)
        getgenv().Skill1 = state
    end)
    
    
    
    generalsec:NewToggle("Package Quest", false, function(state)
        getgenv().fishingquest = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().fishingquest then
                    if game:GetService("Workspace").Merchants.QuestFishMerchant.Clickable:FindFirstChild("BillboardGui").TextLabel.Text == "" then
                        game.Workspace.Merchants.QuestFishMerchant.Clickable.Retum:FireServer()
                    end
                        local Package = game.Players.LocalPlayer.Backpack:FindFirstChild("Package")
                        if Package then
                            local OldPostiton = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
                            Package.Parent = game.Players.LocalPlayer.Character;
                        for _, v in pairs(game.Workspace.Merchants:GetChildren()) do
                            if v:FindFirstChild("HumanoidRootPart") and v.Name ~= "QuestHakiMerchant" then
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.HumanoidRootPart.Position) * CFrame.new(0, 2, 0) + game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.lookVector * 2;
                                Package:Activate();
                                if not game.Players.LocalPlayer.Character:FindFirstChild("Package") then
                                    break;
                                end
                                wait(0.2);
                            end
                        end
                        game.Players.LocalPlayer.Character.Humanoid:UnequipTools();
                        wait(1);
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPostiton);
                    end
                end
            end)
        end
    end)
    
    function tpfish()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-20477.1171875, 214.45838928222656, -20478.75)
        game.Players.LocalPlayer.Character.Humanoid.Sit = true
    end
        
    fishingsec:NewButton("Tp Fishing Place", false, function()
        tpfish()
    end)
    local Rodlist = {"Wood Rod", "Sturdy Rod", "Super Rod"}
    
    fishingsec:NewDropdown("Choose Rod", false, Rodlist, function(currentOption)
        getgenv().SelectRod = currentOption
    end)
    
    
    fishingsec:NewToggle("Auto Fishing", false, function(state)
        getgenv().Auto_Fishing = state
    end)
    

    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Fishing then
                    if not game.Players.LocalPlayer.Character:FindFirstChild(getgenv().SelectRod) then
                        game.Players.LocalPlayer.Backpack:FindFirstChild(getgenv().SelectRod).Parent = game.Players.LocalPlayer.Character
                    else
                        if game.Players.LocalPlayer.Character[getgenv().SelectRod].Cast:FindFirstChild("Bobber") then
                            if game.Players.LocalPlayer.Character[getgenv().SelectRod].Cast.Bobber.Effect.Enabled then
                                game:GetService("Players").LocalPlayer.Character[getgenv().SelectRod].Click:FireServer((game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, 0, 5) + game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.lookVector * 13).Position)
                            end
                        else
                            game:GetService("Players").LocalPlayer.Character[getgenv().SelectRod].Click:FireServer((game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0, 0, 5) + game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.lookVector * 13).Position)
                        end
                    end
                end
            end)
        end
    end)

    generalsec:NewToggle("Auto fish selling", false, function(state)
        getgenv().SellFish = state
    end)

    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().SellFish then
                    workspace:WaitForChild("Merchants"):WaitForChild("FishMerchant"):WaitForChild("Clickable"):WaitForChild("Retum"):FireServer()
                end
            end)
        end
    end)
    
    function YoruNCDFunc()
        local args = {
            [1] = tonumber(serializeTable(attackremote))
        }

        game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
        local args = {
            [1] = tonumber(serializeTable(attackremote))
        }

        game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
        local args = {
            [1] = tonumber(serializeTable(attackremote))
        }

        game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))




    generalsec:NewToggle("YoruNCD", false, function(state)
        getgenv().FastAttack = state
    end)
    
    spawn(function()
        pcall(function()
            while true do wait()
                if getgenv().FastAttack then
                    pcall(function()
                        if game.Players.LocalPlayer.Character.Humanoid.Health > 0 and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500 then
                            if plr.Character:FindFirstChild("Yoru") and tonumber(serializeTable(attackremote)) ~= nil and tonumber(serializeTable(attackremote)) ~= "" then
                                for _ = 1,10 do
                                    YoruNCDFunc()
                                end
                            end
                        end
                    end)
                end
            end
        end)
    end)
    
    generalsec:NewToggle("Auto Accept Mission", false, function(state)
        getgenv().AutoMission = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().AutoMission then
                    if game:GetService("Players").LocalPlayer.PlayerGui.MissionGui.Frame.Visible == false then
                        workspace:WaitForChild("Merchants"):WaitForChild("ExpertiseMerchant"):WaitForChild("Clickable"):WaitForChild("Retum"):FireServer()
                    end
                end
            end)
        end
    end)
    
    generalsec:NewButton("Tap to Accept&Change Mission", false, function()
        workspace:WaitForChild("Merchants"):WaitForChild("ExpertiseMerchant"):WaitForChild("Clickable"):WaitForChild("Retum"):FireServer()
    end)
    
    
    generalsec:NewTextBox("AmountOfGift", false, function(txt)
        getgenv().AmountOfGift = txt
    end)
    
    generalsec:NewButton("Hourly Gift", false, function()
        for _ = 1,getgenv().AmountOfGift do
         workspace:WaitForChild("UserData"):WaitForChild("User_"..game.Players.LocalPlayer.UserId):WaitForChild("ClaimRewardHourly"):FireServer("RewardMark")
        end
    end)
    
    generalsec:NewButton("Daily Gift", false, function()
        for _ = 1,getgenv().AmountOfGift do 
            workspace:WaitForChild("UserData"):WaitForChild("User_"..game.Players.LocalPlayer.UserId):WaitForChild("ClaimRewardDaily"):FireServer("RewardMark")
        end
    end)
    
    samsec:NewButton("Tp SafeZone", false, function()
        SafeZone()
    end)
    
    -------------------------------------------------------------genaraltab(under)---------------------------------------------------------------
    
    
                                
    
                    
    
    -------------------------------------------------------------Fruit autofarm's(top)-----------------------------------------------------------
    function SafePlaceOnBar()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2019.0499267578125, 2689.61474609375, 1404.7730712890625)
        game.Players.LocalPlayer.Character.Humanoid.Sit = true
    end
    Fruitfarmsec:NewButton("Tp SafePlace", false, function()
        SafePlaceOnBar()
    end)
        
            
    Fruitfarmsec:NewDropdown("ChooseFruit", false, {"Magma", "Rumble", "Quake", "Flare", "Gas", "Vampire", "Bomb", "Light"}, function(currentOption)
        getgenv().ChooseFruitFarm = currentOption
    end)
    
    Fruitfarmsec:NewDropdown("ChooseMethod", false, {"Above", "Normal"}, function(currentOption)
        getgenv().ChooseMethod = currentOption
    end)
    
    Fruitfarmsec:NewSlider("Distance AutoFarm", false, 6, -6, function(s)
        getgenv().Distance_AutoFarm_Fruit = s
    end)
    
    Fruitfarmsec:NewToggle("Auto Farm(Fruit)", false, function(state)
        getgenv().Auto_Farm_Fruit = state
    end)
    
    
    Fruitfarmsec:NewToggle("Auto Farm(Zombie Event)", false, function(state)
        getgenv().autofarmzombie = state
    end)
    
    
    Fruitfarmsec:NewToggle("Auto Farm(Cannoball)",false,function(f)
        getgenv().Auto_Farm_Bring = f
    end)
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Bring then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) then
                            if v.Humanoid.Health > 0 then
                                v.HumanoidRootPart.Anchored = true
                                v.HumanoidRootPart.CanCollide = false
                                v.HumanoidRootPart.Size = Vector3.new(12,12,12)
                                v.Humanoid.Animator:Destroy()
                                v.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,15,-15)
                            end
                        end
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Bring then
                    for i,v in pairs(game:GetService("Workspace").WorldEvent.Halloween.Zombies:GetChildren()) do
                        if table.find(getgenv().Table_money_yoru,v.Name) then
                            if v.Humanoid.Health > 0 then
                                v.HumanoidRootPart.Anchored = true
                                v.HumanoidRootPart.CanCollide = false
                                v.HumanoidRootPart.Size = Vector3.new(12,12,12)
                                v.Humanoid.Animator:Destroy()
                                v.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,15,-15)
                            end
                        end
                    end
                end
            end)
        end
    end)


    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Bring then
                    game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Cannon Ball"))
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) then
                            if v.Humanoid.Health > 0 then
                                game:GetService("Players").LocalPlayer.Character:FindFirstChild("Cannon Ball").RemoteEvent:FireServer(CFrame.new(0,0,0))
                                wait(.009)
                                for _,v2 in pairs(game:GetService("Workspace").ResourceHolder["Resources_" .. game.Players.LocalPlayer.UserId]:GetChildren()) do
                                    if v2.Name == "CannonBall" then
                                        for _ = 1,3 do
                                            v2.CanCollide = false
                                            v2.CFrame = v.HumanoidRootPart.CFrame
                                        end
                                    end
                                end
                            end
                        end
                    end
                end
            end)
        end
    end)

    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Bring then
                    game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Cannon Ball"))
                    for i,v in pairs(game:GetService("Workspace").WorldEvent.Halloween.Zombies:GetChildren()) do
                        if table.find(getgenv().Table_money_yoru,v.Name) then
                            if v.Humanoid.Health > 0 then
                                game:GetService("Players").LocalPlayer.Character:FindFirstChild("Cannon Ball").RemoteEvent:FireServer(CFrame.new(0,0,0))
                                wait(.009)
                                for _,v2 in pairs(game:GetService("Workspace").ResourceHolder["Resources_" .. game.Players.LocalPlayer.UserId]:GetChildren()) do
                                    if v2.Name == "CannonBall" then
                                        for _ = 1,3 do
                                            v2.CanCollide = false
                                            v2.CFrame = v.HumanoidRootPart.CFrame
                                        end
                                    end
                                end
                            end
                        end
                    end
                end
            end)
        end
    end)

    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().autofarmzombie and getgenv().ChooseFruitFarm == "Light" then
                    getgenv().Auto_Farm_Fruit = false
                    for _,v in pairs(game:GetService("Workspace").WorldEvent.Halloween.Zombies:GetChildren()) do
                        if v.Humanoid.Health > 0 then
                            v.Humanoid.JumpPower = 0
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,5,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(1099.5858154296875, 221, -3480.406005859375, 0.9999545812606812, 0.005102770868688822, -0.008057218044996262, -4.656613428188905e-10, 0.8448255062103271, 0.5350419878959656, 0.009537139907479286, -0.5350176692008972, 0.844787061214447),
                                        [5] = workspace:WaitForChild("IslandSandCastle"):WaitForChild("RaisedSand"):WaitForChild("RaisedSandBase"):WaitForChild("Real"),
                                        [9] = "Left"
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = math.huge
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                end
                            until v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0 or getgenv().autofarmzombie == false
                        end
                    end
                    for _,v in pairs(game:GetService("Workspace").WorldEvent.Halloween.Zombies:GetChildren()) do
                        if table.find(Table_money_yoru, v.Name) then
                        if v.Humanoid.Health > 0 then
                            v.Humanoid.JumpPower = 0
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,7,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(1099.5858154296875, 221, -3480.406005859375, 0.9999545812606812, 0.005102770868688822, -0.008057218044996262, -4.656613428188905e-10, 0.8448255062103271, 0.5350419878959656, 0.009537139907479286, -0.5350176692008972, 0.844787061214447),
                                        [5] = workspace:WaitForChild("IslandSandCastle"):WaitForChild("RaisedSand"):WaitForChild("RaisedSandBase"):WaitForChild("Real"),
                                        [9] = "Left"
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = math.huge
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                end
                            until v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0 or getgenv().autofarmzombie == false
                        end
                        end
                    end
                elseif getgenv().autofarmzombie and getgenv().ChooseFruitFarm == "Bomb" then
                    getgenv().Auto_Farm_Fruit = false
                    for _,v in pairs(game:GetService("Workspace").WorldEvent.Halloween.Zombies:GetChildren()) do
                        if table.find(Table_money_yoru, v.Name) then
                        if v.Humanoid.Health > 0 then
                            v.Humanoid.JumpPower = 0
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,7,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                local args = {
                                    [1] = tonumber(serializeTable(remotes)),
                                    [2] = "BombPower5",
                                    [3] = "StartCharging",
                                    [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                                    [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                                    [7] = "Right"
                                }
                                
                                game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                wait(.08)
                                local args = {
                                    [1] = tonumber(serializeTable(remotes)),
                                    [2] = "BombPower5",
                                    [3] = "StopCharging",
                                    [4] = CFrame.new(v.HumanoidRootPart.Position),
                                    [5] = v.HumanoidRootPart,
                                    [6] = math.huge
                                }
                                
                                game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                end
                            until v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0 or getgenv().autofarmzombie == false
                        end
                        end
                    end
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Table_money_yoru, v.Name) then
                            if v.Humanoid.Health > 0 then
                                v.Humanoid.JumpPower = 0
                                repeat wait()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,7,0)
                                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "BombPower5",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                                        [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                                        [7] = "Right"
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                    wait(.08)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "BombPower5",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = math.huge
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                    end
                                until v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0 or getgenv().autofarmzombie == false
                            end
                        end
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Zombie_Auto_Farm or getgenv().Auto_Farm_Fruit or getgenv().autofarmzombie then
                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude < 500 then
                    repeat wait()
                    until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500
                    wait(6)
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.V,false,game)
                    game:GetService("VirtualInputManager"):SendKeyEvent(false,Enum.KeyCode.V,false,game)
                end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if  getgenv().Zombie_Auto_Farm or getgenv().Auto_Farm_Fruit or getgenv().autofarmzombie then
                wait(20)
                game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.V,false,game)
                game:GetService("VirtualInputManager"):SendKeyEvent(false,Enum.KeyCode.V,false,game)
                end
            end)
        end
    end)
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Light" and getgenv().ChooseMethod == "Normal" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,getgenv().Distance_AutoFarm_Fruit)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(1099.5858154296875, 221, -3480.406005859375, 0.9999545812606812, 0.005102770868688822, -0.008057218044996262, -4.656613428188905e-10, 0.8448255062103271, 0.5350419878959656, 0.009537139907479286, -0.5350176692008972, 0.844787061214447),
                                        [5] = workspace:WaitForChild("IslandSandCastle"):WaitForChild("RaisedSand"):WaitForChild("RaisedSandBase"):WaitForChild("Real"),
                                        [9] = "Left"
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = math.huge
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Bomb" and getgenv().ChooseMethod == "Normal" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,getgenv().Distance_AutoFarm_Fruit)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "BombPower5",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                                        [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                                        [7] = "Right"
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "BombPower5",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = math.huge
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Gas" and getgenv().ChooseMethod == "Normal" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,getgenv().Distance_AutoFarm_Fruit)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then  
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                            local args = {
                                [1] = tonumber(serializeTable(remotes)),
                                [2] = "GasPower4",
                                [3] = "StartCharging",
                                [4] = CFrame.new(v.HumanoidRootPart.Position),
                                [5] = v.HumanoidRootPart,
                                [7] = "Left"
                            }
                            
                            game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
                            wait(.1)
                            local args = {
                                [1] = tonumber(serializeTable(remotes)),
                                [2] = "GasPower4",
                                [3] = "StopCharging",
                                [4] = CFrame.new(v.HumanoidRootPart.Position),
                                [5] = v.HumanoidRootPart,
                                [6] = 100
                            }
                            
                            game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Magma" and getgenv().ChooseMethod == "Normal" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,getgenv().Distance_AutoFarm_Fruit)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "MagmaPower7",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [6] = "Right"
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Magma.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "MagmaPower7",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Magma.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Flare" and getgenv().ChooseMethod == "Normal" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,getgenv().Distance_AutoFarm_Fruit)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "FlarePower2",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [7] = "Left"
                                    }
                                                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Flare.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "FlarePower2",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                                                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Flare.RemoteEvent:FireServer(unpack(args))      
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Vampire" and getgenv().ChooseMethod == "Normal" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,getgenv().Distance_AutoFarm_Fruit)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "VampirePower11",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [9] = "Right"
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Vampire.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "VampirePower11",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Vampire.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Rumble" and getgenv().ChooseMethod == "Normal" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,0,getgenv().Distance_AutoFarm_Fruit)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "RumblePower3",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [6] = "Left"
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "RumblePower3",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Light" and getgenv().ChooseMethod == "Above" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,getgenv().Distance_AutoFarm_Fruit,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(1099.5858154296875, 221, -3480.406005859375, 0.9999545812606812, 0.005102770868688822, -0.008057218044996262, -4.656613428188905e-10, 0.8448255062103271, 0.5350419878959656, 0.009537139907479286, -0.5350176692008972, 0.844787061214447),
                                        [5] = workspace:WaitForChild("IslandSandCastle"):WaitForChild("RaisedSand"):WaitForChild("RaisedSandBase"):WaitForChild("Real"),
                                        [9] = "Left"
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "LightPower2",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = math.huge
                                    }
                                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Bomb" and getgenv().ChooseMethod == "Above" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,getgenv().Distance_AutoFarm_Fruit,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "BombPower5",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                                        [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                                        [7] = "Right"
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "BombPower5",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = math.huge
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Gas" and getgenv().ChooseMethod == "Above" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,getgenv().Distance_AutoFarm_Fruit,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then  
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                            local args = {
                                [1] = tonumber(serializeTable(remotes)),
                                [2] = "GasPower4",
                                [3] = "StartCharging",
                                [4] = CFrame.new(v.HumanoidRootPart.Position),
                                [5] = v.HumanoidRootPart,
                                [7] = "Left"
                            }
                            
                            game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
                            wait(.1)
                            local args = {
                                [1] = tonumber(serializeTable(remotes)),
                                [2] = "GasPower4",
                                [3] = "StopCharging",
                                [4] = CFrame.new(v.HumanoidRootPart.Position),
                                [5] = v.HumanoidRootPart,
                                [6] = 100
                            }
                            
                            game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Magma" and getgenv().ChooseMethod == "Above" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,getgenv().Distance_AutoFarm_Fruit,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "MagmaPower7",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [6] = "Right"
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Magma.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "MagmaPower7",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Magma.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Flare" and getgenv().ChooseMethod == "Above" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,getgenv().Distance_AutoFarm_Fruit,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "FlarePower2",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [7] = "Left"
                                    }
                                                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Flare.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "FlarePower2",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                                                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Flare.RemoteEvent:FireServer(unpack(args))      
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Vampire" and getgenv().ChooseMethod == "Above" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,getgenv().Distance_AutoFarm_Fruit,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "VampirePower11",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [9] = "Right"
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Vampire.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "VampirePower11",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                
                                    game:GetService("Players").LocalPlayer.Character.Powers.Vampire.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Rumble" and getgenv().ChooseMethod == "Above" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,getgenv().Distance_AutoFarm_Fruit,0)
                                if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.HumanoidRootPart.Position).magnitude < 50 then
                                    v.Humanoid.JumpPower = 0
                                    v.Humanoid.WalkSpeed = 0
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "RumblePower3",
                                        [3] = "StartCharging",
                                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                                        [6] = "Left"
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))
                                    wait(.1)
                                    local args = {
                                        [1] = tonumber(serializeTable(remotes)),
                                        [2] = "RumblePower3",
                                        [3] = "StopCharging",
                                        [4] = CFrame.new(v.HumanoidRootPart.Position),
                                        [5] = v.HumanoidRootPart,
                                        [6] = 100
                                    }
                                    
                                    game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))
                                end
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                elseif getgenv().Auto_Farm_Fruit and getgenv().ChooseFruitFarm == "Quake" then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if table.find(Monsterlist, v.Name) and v.Humanoid.Health > 0 then
                            repeat wait()
                                local args = {
                                    [1] = tonumber(serializeTable(remotes)),
                                    [2] = "QuakePower4",
                                    [3] = "StartCharging",
                                    [5] = "Right"
                                }
                        
                                game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))
                               wait(.1)
                                local args = {
                                    [1] = tonumber(serializeTable(remotes)),
                                    [2] = "QuakePower4",
                                    [3] = "StopCharging",
                                    [4] = v.HumanoidRootPart,
                                    [5] = CFrame.new(v.HumanoidRootPart.Position),
                                    [6] = 100,
                                    [7] = v.HumanoidRootPart.Position
                                }
                        
                                game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))
                            until getgenv().Auto_Farm_Fruit == false or v.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                        end
                    end
                end
            end)
        end
    end)
    
    
    
    
                            
    
    
    
    

    
    local Zom = "Zombie"
    function TP(Mons)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Mons.HumanoidRootPart.Position + Vector3.new(0, 0, 4 ), Mons.HumanoidRootPart.Position)
    end
    
    
    Fruitfarmsec:NewToggle("Auto Farm(Zombie Req : Yoru)", false, function(state)
        getgenv().YoruAutoFarm = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().YoruAutoFarm or getgenv().Zombie_Auto_Farm or getgenv().Auto_Farm_Fruit or getgenv().autofarmzombie then
                    if game.Players.LocalPlayer.Character.Humanoid.Sit == true then
                        game.Players.LocalPlayer.Charcter.Humanoid.Sit = false
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if not getgenv().YoruAutoFarm then return end;
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if table.find(Table_money_yoru, v.Name) then
                        if v.Humanoid.Health > 0 then
                            v.Humanoid.JumpPower = 0
                            repeat wait()
                                game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Yoru"))
                                TP(v)
                                Click()
                            until v.Humanoid.Health == 0 or getgenv().YoruAutoFarm == false or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                            SafeZone()
                        end
                    elseif table.find(Table_money_yoru, "Zombie") then
                        for i2,v2 in pairs(game:GetService("Workspace").WorldEvent.Halloween.Zombies:GetChildren()) do
                            if table.find(Table_money_yoru, v2.Name) then
                                if v2.Humanoid.Health > 0 then
                                    v2.Humanoid.JumpPower = 0
                                    repeat wait()
                                        game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Yoru"))
                                        TP(v2)
                                        Click()
                                    until v2.Humanoid.Health == 0 or getgenv().YoruAutoFarm == false or game.Players.LocalPlayer.Character.Humanoid.Health == 0
                                    SafeZone()
                                end
                            end 
                        end
                    end
                end
            end)
        end
    end)
    
    
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().YoruAutoFarm then
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game:GetService("Workspace").SafePlace.Position).magnitude < 100 then
                        if game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].UsingHaki.Value == true then
                            workspace.UserData["User_"..game.Players.LocalPlayer.UserId].UpdateHaki:FireServer()
                        end
                    elseif (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game:GetService("Workspace").SafePlace.Position).magnitude > 100 then
                        if game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].UsingHaki.Value ~= true then
                            workspace.UserData["User_"..game.Players.LocalPlayer.UserId].UpdateHaki:FireServer()
                        end
                    end
                end
            end)
        end
    end)
    
    Fruitfarmsec:NewToggle("Auto Enable Zombie Raid (Pumpkin)", false, function(state)
        getgenv().AutoPumkin = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().AutoPumkin then 
                    local OldPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
                    if game:GetService("Workspace").WorldEvent.Halloween.Pumpkin.CanCollide == true then
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").WorldEvent.Halloween.Pumpkin.CFrame
                        fireclickdetector(game:GetService("Workspace").WorldEvent.Halloween.Pumpkin.ClickDetector)
                        wait(.2)
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPosition)
                    end
                end
            end)
        end
    end)
    
    
    
    
    
    
    
    
    
    -------------------------------------------------------------Fruit autofarm's(Under)---------------------------------------------------------
    -------------------------------------------------------------Teleport(top)-----------------------------------------------------------
    if not game:GetService("Workspace"):FindFirstChild("UnderWater SafePlace") then
        local e = Instance.new("Part",game.Workspace)
        e.Name = "UnderWater SafePlace"
        e.Size = Vector3.new(100, 3, 100)
        e.Position = Vector3.new(145, 0, -2915) 
        e.Anchored = true
    end
    teleportsec:NewButton("Tp SafeZone", false, function()
        SafeZone()
    end)
    function UnderSafeZone()
        game.Players.LocalPlayer.Character.Humanoid.Sit = true
        wait(.2)
        plr.Character.HumanoidRootPart.CFrame = CFrame.new(145, 2, -2915)
    end
    teleportsec:NewButton("Tp Under Safe(For Fruitless)", false, function()
        UnderSafeZone()
    end)
    
    teleportsec:NewToggle("Tp Under Safe(For Fruitless)",false,function(s)
        getgenv().UnderWaterSP = s
        while true do wait()
            pcall(function()
                if getgenv().UnderWaterSP then
                    UnderSafeZone()
                    wait(2)
                end
            end)
        end
    end)
    getgenv().Fountain = CFrame.new(-237.02545166015625, 231.9999542236328, -1071.087890625)
    getgenv().Windmill = CFrame.new(64.46731567382812, 234.0655517578125, -148.2689208984375)
    getgenv().SmallHouse = CFrame.new(-427.99951171875, 216.21011352539062, -156.0537109375)
    getgenv().CrabIsland = CFrame.new(1213.9381103515625, 253, -302.66162109375)
    getgenv().OldStoneIsland = CFrame.new(2058.0693359375, 488, -708.72412109375)
    getgenv().Grass = CFrame.new(2109.097412109375, 216.9999542236328, -1860.8443603515625)
    getgenv().Town = CFrame.new(1802.40234375, 217.9999542236328, 762.3007202148438)
    getgenv().MoonIsland = CFrame.new(3197.567626953125, 216.9999542236328, 1546.5316162109375)
    getgenv().Bar = CFrame.new(1493.5032958984375, 281.06182861328125, 2154.201171875)
    getgenv().PlummetIsland = CFrame.new(1068, 217, 3351)
    getgenv().Pyramid = CFrame.new(119.1684799194336, 228.99986267089844, 4834.05859375)
    getgenv().BigSnow = CFrame.new(-1894.7913818359375, 224.99993896484375, 3298.2802734375)
    getgenv().Garbage = CFrame.new(-2631.823486328125, 269.59991455078125, 1087.8115234375)
    getgenv().RaceIsland = CFrame.new(-4342.294921875, 246.14207458496094, 5279.54931640625)
    getgenv().FishingIsland = CFrame.new(-1690.4508056640625, 215.9999542236328, -333.2132568359375)
    getgenv().Sam = CFrame.new(-1305.072265625, 222.89837646484375, -1352.37890625)
    getgenv().Green = CFrame.new(-6033.12353515625, 403.9049987792969, -7.100854873657227)
    getgenv().MarinFord = CFrame.new(-3133.978759765625, 353.9999084472656, -4059.798828125)
    getgenv().Purple = CFrame.new(-5278.6376953125, 516, -7850.482421875)
    getgenv().DesertCastle = CFrame.new(966.2010498046875, 284, -3208.5322265625)
    getgenv().PursuerIsland = CFrame.new(4838.99462890625, 569.9998168945312, -7160.9541015625)
    getgenv().BigSnow = CFrame.new(6474.25830078125, 412.0928955078125, -1284.3623046875)
    getgenv().Vokun = CFrame.new(4575.34619140625, 217.3998565673828, 5139.04150390625)
    getgenv().MissionIsland = CFrame.new(866.682861328125, 269.1999206542969, 1219.1651611328125)
    getgenv().NearKrizma = CFrame.new(-35.08990478515625, 228.9999542236328, 2155.894775390625)
    getgenv().Krizma = CFrame.new(-1071.5040283203125, 275.9996032714844, 1627.9949951171875)
    getgenv().KaizuIsland = CFrame.new(-2591.1767578125, 533.9998168945312, 9829.470703125)
    getgenv().Altar = CFrame.new(game:GetService("Workspace").Altar.Ring.Position)
    getgenv().Crescent = CFrame.new(3190.89331, 356.999908, 1669.55237, 0.999996126, -4.52603253e-08, 0.00277347933, 4.53075977e-08, 1, -1.69819376e-08, -0.00277347933, 1.71075314e-08, 0.999996126)
    getgenv().restaurant = CFrame.new(1968.28711, 217.999954, 598.663635, 0.656699657, -9.06415778e-08, -0.754152238, 5.53038682e-08, 1, -7.20325986e-08, 0.754152238, 5.59624658e-09, 0.656699657)
    getgenv().SmallSnow = CFrame.new(-1895.0904541015625, 224.9999542236328, 3295.168701171875)



    teleportsec:NewDropdown("ChooseIsland", false, {"Fountain",
    "Windmill",
    "Tiny House",
    "Crab Island", 
    "Old Stone Island",
    "Town",
    "Crecent Island",
    "Bar",
    "Plummet Island",
    "Pyramid",
    "Small Snow",
    "Garbage",
    "Race Island",
    "Fishing Island",
    "Sam",
    "Grass Mountian Island",
    "Marineford",
    "Evil Purple Island",
    "Desert Castle",
    "Pursuer Island",
    "Big Snow",
    "Vokun",
    "Mission Island",
    "Stone Krizma",
    "Krizma",
    "Kaizu Island",
    "Restaurant",
    "Altar"}, function(currentOption)
        getgenv().TeleportIsland = currentOption
    end)
    
    teleportsec:NewButton("Teleport", false, function()
        if getgenv().TeleportIsland == "Fountain" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Fountain
        elseif getgenv().TeleportIsland == "Windmill" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Windmill
        elseif getgenv().TeleportIsland == "Tiny House" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().SmallHouse
        elseif getgenv().TeleportIsland == "Crab Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().CrabIsland
        elseif getgenv().TeleportIsland == "Old Stone Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().OldStoneIsland
        elseif getgenv().TeleportIsland == "Crecent Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Crescent
        elseif getgenv().TeleportIsland == "Town" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Town
        elseif getgenv().TeleportIsland == "Bar" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Bar
        elseif getgenv().TeleportIsland == "Plummet Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().PlummetIsland
        elseif getgenv().TeleportIsland == "Pyramid" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Pyramid
        elseif getgenv().TeleportIsland == "Small Snow" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().SmallSnow
        elseif getgenv().TeleportIsland == "Garbage" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Garbage
        elseif getgenv().TeleportIsland == "Race Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().RaceIsland
        elseif getgenv().TeleportIsland == "Fishing Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().FishingIsland
        elseif getgenv().TeleportIsland == "Sam" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Sam
        elseif getgenv().TeleportIsland == "Grass Mountian Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Green
        elseif getgenv().TeleportIsland == "Marineford" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().MarinFord
        elseif getgenv().TeleportIsland == "Evil Purple Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Purple
        elseif getgenv().TeleportIsland == "Desert Castle" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().DesertCastle
        elseif getgenv().TeleportIsland == "Pursuer Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().PursuerIsland
        elseif getgenv().TeleportIsland == "Big Snow" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().BigSnow
        elseif getgenv().TeleportIsland == "Vokun" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Vokun
        elseif getgenv().TeleportIsland == "Mission Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().MissionIsland
        elseif getgenv().TeleportIsland == "Stone Krizma" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().NearKrizma
        elseif getgenv().TeleportIsland == "Krizma" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Krizma
        elseif getgenv().TeleportIsland == "Kaizu Island" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().KaizuIsland
        elseif getgenv().TeleportIsland == "Altar" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Altar
        elseif getgenv().TeleportIsland == "Restaurant" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().restaurant
        end
    end)
    
    teleportsec:NewDropdown("ChooseNPC", false, {"Sam", "Affinity", "Mission", "FisherMan", "SwordSeller", "GunSeller", "KrizmaSeller", "CannonBallSeller"}, function(currentOption)
        getgenv().tlpnpc = currentOption
    end)
    
    
    getgenv().SamTP = CFrame.new(-1306.473876953125, 217.9999542236328, -1352.478515625)
    getgenv().AffTP = CFrame.new(115.92289733886719, 277.9999084472656, 4949.90966796875)
    getgenv().MissionTP = CFrame.new(902.2069091796875, 269.9999084472656, 1220.334228515625)
    getgenv().FishingmanTP = CFrame.new(-1699.015625, 215.9999542236328, -326.2913513183594)
    getgenv().SwordSellerTP = CFrame.new(997.1166381835938, 223.9999542236328, -3338.7724609375)
    getgenv().GunSellerTP = CFrame.new(-1843.2255859375, 221.9999542236328, 3415.83349609375)
    getgenv().KrizmaSellerTP = CFrame.new(-1072.536865234375, 361, 1670.274169921875)
    getgenv().CannonBallTP = CFrame.new(-2610.22363, 254.099976, 1109.7616, -0.999997497, -6.8173776e-08, -0.00224121567, -6.79576502e-08, 1, -9.65082947e-08, 0.00224121567, -9.63557483e-08, -0.999997497)
    
    
    
    
    teleportsec:NewButton("Teleport", false, function()
        local tp = game.Players.LocalPlayer.Character.HumanoidRootPart
        if getgenv().tlpnpc == "Sam" then
            tp.CFrame = getgenv().SamTP
        elseif getgenv().tlpnpc == "Affinity" then
            tp.CFrame = getgenv().AffTP
        elseif getgenv().tlpnpc == "Mission" then
            tp.CFrame = getgenv().MissionTP
        elseif getgenv().tlpnpc == "FisherMan" then
            tp.CFrame = getgenv().FishingmanTP
        elseif getgenv().tlpnpc == "SwordSeller" then
            tp.CFrame = getgenv().SwordSellerTP
        elseif getgenv().tlpnpc == "GunSeller" then
            tp.CFrame = getgenv().GunSellerTP
        elseif getgenv().tlpnpc == "KrizmaSeller" then
            tp.CFrame = getgenv().KrizmaSellerTP
        elseif getgenv().tlpnpc == "CannonBallSeller" then
            tp.CFrame = getgenv().CannonBallTP
        end
    end)
    
    teleportsec:NewButton("Altar Tp", false, function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getgenv().Altar
    end)
    -------------------------------------------------------------Teleport(Under)-----------------------------------------------------------
    --------------------------------------------------------------Sam(Top)-----------------------------------------------------------------
    
    samsec:NewButton("Tp Sam", false, function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1305.160400390625, 222.89837646484375, -1352.609375)
    end)
    
    samsec:NewToggle("Automatically Sam Quest", false, function(state)
        getgenv().AutoSamQuest = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if not getgenv().AutoSamQuest then return end;
                game.Workspace.Merchants.QuestMerchant.Clickable.Retum:FireServer("Claim10");
                local Compass = game.Players.LocalPlayer.Backpack:FindFirstChild("Compass");
                local Compass2 = game.Players.LocalPlayer.Character:FindFirstChild("Compass");
                if Compass or Compass2 then
                    local OldPostiton = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
                    game.Players.LocalPlayer.Character.Humanoid:UnequipTools();
                    Compass.Parent = game.Players.LocalPlayer.Character;
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Compass.Poser.Value);
                    Compass:Activate();
                    wait(1);
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPostiton);
                end
            end)
        end
    end)
    
    samsec:NewToggle("Auto Claim Compass", false, function(state)
        getgenv().Compass = state
    end)
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Compass then
                    game.Workspace.Merchants.QuestMerchant.Clickable.Retum:FireServer("Claim1");
                end
            end)
        end
    end)
    
    
    samsec:NewToggle("Auto Compass Destination", false, function(state)
        getgenv().FindCompass = state
    end)
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if not getgenv().FindCompass then return end;
                local Compass = game.Players.LocalPlayer.Backpack:FindFirstChild("Compass");
                local Compass2 = game.Players.LocalPlayer.Character:FindFirstChild("Compass");
                if Compass or Compass2 then
                    local OldPostiton = game.Players.LocalPlayer.Character.HumanoidRootPart.Position;
                    Compass.Parent = game.Players.LocalPlayer.Character;
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Compass.Poser.Value);
                    Compass:Activate();
                    wait(1);
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPostiton);
                end
            end)
        end
    end)
    
    samsec:NewToggle("Tp DevilFruit", false, function(state)
        getgenv().lootfruit = state
    end)
    
    spawn(function()
        game:GetService("RunService").RenderStepped:Connect(function()
            pcall(function()
                if getgenv().lootfruit then
                    for _, Item in pairs(game.Workspace.Trees.Tree.Model:GetChildren()) do
                        if Item.ClassName == "Tool" then
                            fireclickdetector(Item.Main.ClickDetector);
                        end
                    end
                end
            end)
        end)
    end);
    
    
    
    
    samsec:NewToggle("Auto Rare/Ultra Store", false, function(state)
        getgenv().autostore = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if not getgenv().autostore then return end;
                for _,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
                    if string.find(v.Name, "Quake") or string.find(v.Name, "Phoenix") or string.find(v.Name, "Dark") or string.find(v.Name, "Vampire") or string.find(v.Name, "Gravity") or string.find(v.Name, "Ope") or string.find(v.Name, "Venom") or string.find(v.Name, "Candy") or string.find(v.Name, "Hollow")or string.find(v.Name, "Chilly")or string.find(v.Name, "Gas")or string.find(v.Name, "Flare")or string.find(v.Name, "Light")or string.find(v.Name, "Smoke")or string.find(v.Name, "Rumble")or string.find(v.Name, "Sand")or string.find(v.Name, "Magma")or string.find(v.Name, "Snow") then
                        if game.Players.LocalPlayer.Backpack:FindFirstChild(v.Name) then
                            game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[v.Name])
                            if game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF1.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF1"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF2.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF2"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF3.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF3"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF4.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF4"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF5.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF5"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF6.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF6"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF5.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF7"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF8.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF8"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF9.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF9"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF10.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF10"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF11.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF11"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            elseif game:GetService("Players").LocalPlayer.PlayerGui.Storage.Frame.StoredDF12.Button.Text == "Store" then
                                local args = {
                                    [1] = "StoredDF12"
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_" .. game.Players.LocalPlayer.UserId):WaitForChild("StoredDFRequest"):FireServer(unpack(args))
                            end
                        end
                    end
                end
            end)
        end
    end)
    
    
    
    
    --------------------------------------------------------------Sam(Under)-----------------------------------------------------------------
    --------------------------------------------------------------Drinks(Top)-----------------------------------------------------------------
    drinksec:NewDropdown("ChooseDrinks", false, {"Cider+", "Lemonade+", "Juice+", "Smoothie+", "Cider", "Lemonade", "Juice", "Smoothie"}, function(currentOption)
        getgenv().choosedrinks = currentOption
    end)
    
    
    drinksec:NewTextBox("AmountDrinks", false, function(txt)
        getgenv().amountdrinkbuy = txt
    end)
    
    drinksec:NewButton("BuyDrinks", false, function()
        for _ = 1,getgenv().amountdrinkbuy do
            game.Workspace.Merchants.BetterDrinkMerchant.Clickable.Retum:FireServer(getgenv().choosedrinks)
        end
    end)
    
    local tabledrinkslist = {"Cider+", "Lemonade+", "Juice+", "Smoothie+", "Cider", "Lemonade", "Juice", "Smoothie", "Pumpkin Juice", "Sour Juice", "Fruit Juice", "Coconut Milk", "Banana Juice", "Apple Juice", "Golden Apple"}
    
    function Drinking()
        for _, Value in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
        if table.find(tabledrinkslist, Value.Name) then
            game.Players.LocalPlayer.Character.Humanoid:UnequipTools();
            Value.Parent = game.Players.LocalPlayer.Character;
            Value:Activate();
            end
        end
    end

    drinksec:NewButton("Drinking", false, function()
        Drinking()
    end)
    
    
    function DrinkingML()
        local tabledrinks = "Cider+"
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v.Name == tabledrinks then
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
                game:GetService'VirtualUser':CaptureController()
                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
            end
        end
    end
    
    function DrinkingSN()
        local tabledrinks = "Lemonade+"
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v.Name == tabledrinks then
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
                game:GetService'VirtualUser':CaptureController()
                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
            end
        end
    end
    
    function DrinkingSW()
        local tabledrinks = "Juice+"
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v.Name == tabledrinks then
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
                game:GetService'VirtualUser':CaptureController()
                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
            end
        end
    end
    
    function DrinkingDF()
        local tabledrinks = "Smoothie+"
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v.Name == tabledrinks then
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
                game:GetService'VirtualUser':CaptureController()
                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
            end
        end
    end
    
    
    drinksec:NewToggle("Drinking", false, function(state)
        getgenv().autodrink = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().autodrink then
                    Drinking()
                    wait(5)
                end
            end)
        end
    end)
    

    function GetBR()
        for i,v in pairs(game:GetService("Workspace").Barrels.Barrels.Barrel:GetChildren()) do
            if v.ClassName == "ClickDetector" then
                fireclickdetector(v)
            end
        end
    end

    drinksec:NewToggle("Mixer", false, function(state)
        getgenv().Mixer = state
    end)

    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Mixer then
                    local hm = game.Players.LocalPlayer.Character.HumanoidRootPart
                    for i,v in pairs(game.Workspace:GetChildren()) do 
                        if v.ClassName == "Tool" then
                            v.Handle.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
                        end
                    end
                    hm.CFrame = CFrame.new(-204.6328582763672, 224.8590087890625, -207.70982360839844)
                    for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                        if v.ClassName == "ClickDetector" then
                            fireclickdetector(v)
                        end
                    end
                    wait(.15)
                    hm.CFrame = CFrame.new(-14.77018928527832, 215.5562286376953, -352.4534606933594)
                    for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                        if v.ClassName == "ClickDetector" then
                            fireclickdetector(v)
                        end
                    end
                    wait(.15)
                    hm.CFrame = CFrame.new(2.0082764625549316, 215.4777069091797, -379.8304443359375)
                    for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                        if v.ClassName == "ClickDetector" then
                            fireclickdetector(v)
                        end
                    end
                    wait(.15)
                    hm.CFrame = CFrame.new(-119.06230926513672, 216.03643798828125, -703.011474609375)
                    for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                        if v.ClassName == "ClickDetector" then
                            fireclickdetector(v)
                        end
                    end
                   wait(.15)
                   hm.CFrame = CFrame.new(-134.78208923339844, 216.4760284423828, -708.4603881835938)
                   for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                       if v.ClassName == "ClickDetector" then
                           fireclickdetector(v)
                       end
                   end
                   wait(.15)
                   hm.CFrame = CFrame.new(-134.78208923339844, 216.4760284423828, -708.4603881835938)
                   for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                       if v.ClassName == "ClickDetector" then
                           fireclickdetector(v)
                       end
                   end
                   wait(.15)
                   hm.CFrame = CFrame.new(-1705.62353515625, 216.0959014892578, -328.41082763671875)
                   for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                       if v.ClassName == "ClickDetector" then
                           fireclickdetector(v)
                       end
                   end
                   wait(.15)
                   hm.CFrame = CFrame.new(-1547.7965087890625, 217.05264282226562, -307.8839416503906)
                   for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                       if v.ClassName == "ClickDetector" then
                           fireclickdetector(v)
                       end
                   end
                  wait(.15)
                  hm.CFrame = CFrame.new(-1522.9046630859375, 216.9999542236328, -290.0218200683594)
                  for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                      if v.ClassName == "ClickDetector" then
                          fireclickdetector(v)
                      end
                  end
                  wait(.15)
                  hm.CFrame = CFrame.new(-1514.3734130859375, 216.9999542236328, -289.9631042480469)
                  for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                      if v.ClassName == "ClickDetector" then
                          fireclickdetector(v)
                      end
                  end
                  wait(.15)
                  hm.CFrame = CFrame.new(-1497.65234375, 216.565673828125, -306.78387451171875)
                  for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                      if v.ClassName == "ClickDetector" then
                          fireclickdetector(v)
                      end
                  end
                  wait(.15)
                  hm.CFrame = CFrame.new(-1492.7325439453125, 217.1244659423828, -306.8923034667969)
                  for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                      if v.ClassName == "ClickDetector" then
                          fireclickdetector(v)
                      end
                  end
                 wait(.15)
                 hm.CFrame = CFrame.new(-1489.7109375, 217.05206298828125, -306.9287109375)
                 for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                     if v.ClassName == "ClickDetector" then
                         fireclickdetector(v)
                     end
                 end
                 wait(.15)
                 hm.CFrame = CFrame.new(1988.1585888671875, 218.12429809570312, 559.5914916992188)
                 for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                     if v.ClassName == "ClickDetector" then
                         fireclickdetector(v)
                     end
                 end
                 wait(.15)
                 hm.CFrame = CFrame.new(894.6880493164062, 224.0678253173828, -3222.584716796875)
                 for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                     if v.ClassName == "ClickDetector" then
                         fireclickdetector(v)
                     end
                 end
                 wait(.15)
                 hm.CFrame = CFrame.new(887.6516723632812, 224.03814697265625, -3225.1591259765625)
                 for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                     if v.ClassName == "ClickDetector" then
                         fireclickdetector(v)
                     end
                 end
                wait(.15)
                hm.CFrame = CFrame.new(894.8455810546875, 224.1929931640625, -3325.1529248046875)
                for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                    if v.ClassName == "ClickDetector" then
                        fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(887.5870361328125, 224.1117706298828, -3322.4423828125)
                for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                    if v.ClassName == "ClickDetector" then
                        fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1069.656005859375, 224.064208984375, -3428.1503369140625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                    if v.ClassName == "ClickDetector" then
                        fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1193.13818359375, 224.57733154296875, -3371.649169921875)
                for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                    if v.ClassName == "ClickDetector" then
                        fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1241.618408203125, 224.36431884765625, -3230.701171875)
                for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                    if v.ClassName == "ClickDetector" then
                        fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1173.85205078125, 217.1753692626953, -281.8468933105469)
                for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                    if v.ClassName == "ClickDetector" then
                        fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1174.89697265625, 217.0174560546875, -290.81475830078125)
                for i,v in pairs(game:GetService("Workspace").Barrels.Barrels:GetDescendants()) do
                    if v.ClassName == "ClickDetector" then
                        fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1863.00537109375, 221.98583984375, 816.6077270507812)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1878.83056640625, 218.1305694580078, 834.1688842773438)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1969.9931640625, 218.01373291015625, 575.0803833007812)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1982.3048095703125, 217.18675231933594, 556.15821655273438)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1986.9345703125, 233.9999542236328, 569.3563232421875)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1992.87646484375, 234.39993286132812, 567.15401733398438)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1185.5386962890625, 216.9999542236328, -288.9674072265625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(897.4021606445312, 225.9706573486328, -3222.193603515625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(892.3162231445312, 225.31390380859375, -3225.159052734375)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(888.7985229492188, 226.89662170410156, -3227.06884765625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(890.466552734375, 224.38919067382812, -3325.48828125)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(894.05615234375, 224.193115234375, -3330.157958984375)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1070.656005859375, 223.9999542236328, -3426.9208984375)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1172.826416015625, 224.155125122070312, -3326.349609375)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1220.037841796875, 224.32119750976562, -3234.904052734375)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1106.389892578125, 226.9904327392578, -3220.738525390625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1704.922119140625, 222.16046142578125, -328.185546875)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1705.6966552734375, 220.017578125, -323.02252197265625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1746.3370361328125, 217.60806274414062, -322.3219299316406)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1744.8477783203125, 218.0204620361328, -330.967041015625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1761.474853515625, 218.0160675048828, -330.1387023925781)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1759.16748046875, 218.0180206298828, -320.6255798339844)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1748.1565380859375, 216.153345947265625, -218.37091064453125)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-1756.80859375, 220.00779724121094, -215.89068603515625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-2620.360107421875, 257.6999206542969, 1110.1300048828125)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(-2598.3681640625, 253.3859405517578, 1110.83203125)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1166.15234375, 215.9999542236328, 3226.744873046875)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(1008.310791015625, 220.0399932861328, 3342.307373046875)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                wait(.15)
                hm.CFrame = CFrame.new(881.8496704101562, 216.5819091796875, 3361.3037109375)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                hm.CFrame = CFrame.new(915.623779296875, 217.1762237548828, 3409.363525390625)
                for i,v in pairs(game:GetService("Workspace").Barrels.Crates:GetDescendants()) do
                    if v:IsA("ClickDetector") then
                    fireclickdetector(v)
                    end
                end
                    wait(.15)
                    for i,v in pairs(game:GetService("Workspace").Island8.Kitchen:GetDescendants()) do
                        if v:IsA("ClickDetector") then
                            fireclickdetector(v)
                        end
                    end
                end
            end)
        end
    end)

    drinksec:NewButton("Tap to Enable Only Drinks function", false, function()
        drinksec:NewButton("Drinking Only Cider +", false, function()
            DrinkingML()
        end)
       drinksec:NewButton("Drinking Only Lemonade +", false, function()
            DrinkingSN()
        end)
        drinksec:NewButton("Drinking Only Juice +", false, function()
            DrinkingSW()
        end)
        drinksec:NewButton("Drinking Only Smoothie +", false, function()
            DrinkingDF()
        end)
    end)
    
    
    
    
    --------------------------------------------------------------Drinks(Under)-----------------------------------------------------------------
    --------------------------------------------------------------Killing(Top)------------------------------------------------------------------
    
    killplayersec:NewButton("SafeZone", false, function()
        SafeZone()
    end)
    
    getgenv().listplayers = {}
    
    
    for i,v in pairs(game:GetService("Players"):GetChildren()) do
        if v.Name ~= game.Players.LocalPlayer.Name then
            table.insert(getgenv().listplayers ,v.Name)
        end
    end
    
    local dropdown = killplayersec:NewDropdown("ChoosePlayers", false, getgenv().listplayers, function(currentOption)
        getgenv().target = currentOption
    end)
    
    killplayersec:NewButton("RefreshPlayers", false, function()
        table.clear(getgenv().listplayers)
        for i,v in pairs(game.Players:GetChildren()) do
            if v.Name ~= game.Players.LocalPlayer.Name then
                table.insert(getgenv().listplayers,v.Name)
                dropdown:Refresh(getgenv().listplayers)
            end
        end
    end)
    killplayersec:NewButton("ViewPlayer", false , function()
        if game.Workspace.CurrentCamera.CameraSubject == game.Players.LocalPlayer.Character.Humanoid then
            for i,v in pairs(game:GetService("Players"):GetChildren()) do
               if v.Name == getgenv().target then
                    game.Workspace.CurrentCamera.CameraSubject = game.Players[v.Name].Character.Humanoid;
                end
            end
        elseif game.Workspace.CurrentCamera.CameraSubject ~= game.Players.LocalPlayer.Character.Humanoid then
            game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
        end
    end)
    

    killplayersec:NewButton("Teleport Target", false, function()
        plr.Character.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
    end)
    
    killplayersec:NewToggle("Teleport Target", false, function(state)
        getgenv().tptarget = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().tptarget then
                    if game.Players[target].Character.Humanoid.Health > 0 then
                        local OldPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
                        if getgenv().tptarget == true then
                            if not game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].UsingHaki.Value then
                                game.Workspace.UserData["User_" .. game.Players.LocalPlayer.UserId].UpdateHaki:FireServer()
                            end
                            repeat task.wait()
                                 plr.Character.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame * CFrame.new(0,0,3)
                            until v.Humanoid.Health <= 0 or getgenv().tptarget == false or plr.Character.Humanoid.Health == 0
                        end
                    elseif game.Players[target].Character.Humanoid.Health == 0 then
                        game.Workspace.UserData["User_" .. game.Players.LocalPlayer.UserId].UpdateHaki:FireServer()
                        SafeZone()
                    end
                end
            end)
        end
    end)
    
    
    
    killplayersec:NewToggle("Bring Target", false, function(state)
        getgenv().bringtarget = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().bringtarget then
                    if game.Players[target].Character.Humanoid.Health > 0 then
                        game.Players[target].Character.HumanoidRootPart.CFrame = plr.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,-4)
                    end
                end
            end)
        end
    end)
    
    
    
    
    
    killplayersec:NewButton("Data Printer(TargetInfo)", false, function()
        print("Melee : " .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.MeleeLevel.Value)
        print("Sniper :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.SniperLevel.Value)
        print("Sword :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.SwordLevel.Value)
        print("Defense :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.DefenseLevel.Value)
        print("Haki :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.HakiLevel.Value)
        print("Bounty :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.Bounty.Value)
        print("Expertise :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.ExpertiseLevel.Value)
        print("Kills :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.Kills.Value)
        print("Gems :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.Gems.Value)
        print("Cash :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.Cash.Value)
        print("DF1 :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.DevilFruit.Value.. " MeleeAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT1Melee.Value .. " SniperAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT1Sniper.Value.. " SwordAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT1Sword.Value.. " DefenseAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT1Defense.Value)
        print("DF2 :" .. game:GetService("Workspace").UserData["User_" .. game.Players[target].UserId].Data.DevilFruit2.Value.. " MeleeAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT2Melee.Value .. " SniperAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT2Sniper.Value.. " SwordAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT2Sword.Value.. " DefenseAff : " ..game:GetService("Workspace").UserData["User_"..game.Players[target].UserId].Data.DFT2Defense.Value)
        print("Storage1 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF1.Value)
        print("Storage2 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF2.Value)
        print("Storage3 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF3.Value)
        print("Storage4 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF4.Value)
        print("Storage5 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF5.Value)
        print("Storage6 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF6.Value)
        print("Storage7 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF7.Value)
        print("Storage8 :" .. game:GetService("Workspace").UserData["User_".. game.Players[target].UserId].Data.StoredDF8.Value)
        print("-------------------------------------------------------------")
    end)
    
    
    miscsec2:NewTextBox("Place JobId here!!", false, function(txt)
        getgenv().JobId = txt
    end)
    
    miscsec2:NewButton("Join Sever", false, function()
        game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, getgenv().JobId)
    end)
    
    miscsec2:NewButton("Copy JobId", false, function()
        setclipboard(game.JobId)
        print(game.JobId)
    end)
    
    miscsec2:NewKeybind("Press P to hide hub", false, Enum.KeyCode.P, function()
        print("")
    end)


    miscsec2:NewToggle("HitBoxExtander", false, function(state)
        getgenv().ChangeHitBox = state
    end)
    
    
    miscsec2:NewSlider("HitBox Slider", false, 400, 5, function(s) -- 500 (MaxValue) | 0 (MinValue)
        getgenv().HitBoxSize = s
        game:GetService('RunService').RenderStepped:connect(function() 
        if getgenv().ChangeHitBox then 
            for i,v in next, game:GetService('Players'):GetPlayers() do 
                if v.Name ~= game:GetService('Players').LocalPlayer.Name then 
                    pcall(function()
                        v.Character.HumanoidRootPart.Size = Vector3.new(getgenv().HitBoxSize,getgenv().HitBoxSize,getgenv().HitBoxSize) 
                        v.Character.HumanoidRootPart.Transparency = 0.9
                        v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Red") 
                        v.Character.HumanoidRootPart.Material = "Neon" 
                        v.Character.HumanoidRootPart.CanCollide = false 
                    end)
                end
            end
        end
    end)
    end)
    
    miscsec2:NewTextBox("Place Fake Name!!", false, function(txt)
        getgenv().FakeName = txt
    end)

    miscsec2:NewButton("Set Fake Name", false, function()
        game:GetService("Players").LocalPlayer.PlayerGui.Menu.Frame.C.Frame.Nametag.Text = getgenv().FakeName
    end)
    killplayersec2:NewDropdown("ChooseFruit", false, {"Light", "Magma", "Bomb", "Dark", "Gas", "Flare", "Quake", "Vampire", "Rumble"}, function(currentOption)
        getgenv().killingwithfruit = currentOption
    end)
    
    killplayersec2:NewDropdown("Teleport Method", false, {"Above", "Normal"}, function(currentOption)
        Select_Method_Kill = currentOption
    end)
    
    killplayersec2:NewSlider("Slider Distance", false, 10, 1, function(s) -- 500 (MaxValue) | 0 (MinValue)
        Select_Distance_Kill = s
    end)



    killplayersec2:NewToggle("Kill Target", false, function(state)
         getgenv().Kill = state
    end)
    
    killplayersec2:NewToggle("Kill Target (Cannon Ball)", false, function(state)
        getgenv().Kill_CannonBall = state
    end)
    

    killplayersec2:NewToggle("Kill All (Cannon Ball)", false, function(state)
        getgenv().Kill_All_CannonBall = state
    end)

    
spawn(function()
    while true do wait()
        pcall(function()
            if getgenv().Kill_All_CannonBall then
                for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
                    if v:IsA("Tool") then
                        if v.Name == "Cannon Ball" then
                            v.Parent = game.Players.LocalPlayer.Character
                        end
                    end
                end
                for i,v in next, game:GetService('Players'):GetPlayers() do
                    if v.Name ~= game.Players.LocalPlayer.Name then
                        if (v.Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500 and v.Character.Humanoid.Health > 0 and v.Character.FindFirstChild("HummanoidRootPart") then
                            v.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(15,15,15)
                            game:GetService("Players").LocalPlayer.Character:FindFirstChild("Cannon Ball").RemoteEvent:FireServer(CFrame.new(0,0,0))
                            wait(.009)
                            for _,v2 in pairs(game:GetService("Workspace").ResourceHolder["Resources_" .. game.Players.LocalPlayer.UserId]:GetChildren()) do
                                if v2.Name == "CannonBall" then
                                    for _ = 1,5 do
                                        v2.CFrame = v.Character.HumanoidRootPart.CFrame
                                    end
                                end
                            end
                        end
                    end
                end
            end
        end)
    end
end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if not getgenv().Kill_CannonBall then return end;
                    for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
                        if v:IsA("Tool") then
                            if v.Name == "Cannon Ball" then
                                v.Parent = game.Players.LocalPlayer.Character
                            end
                        end
                    end
                    local args = {
                        [1] = CFrame.new(0,0,0)
                    }
                
                    game:GetService("Players").LocalPlayer.Character:FindFirstChild("Cannon Ball").RemoteEvent:FireServer(unpack(args))
                    wait(.009)
                    for _,v in pairs(game:GetService("Workspace").ResourceHolder["Resources_" .. game.Players.LocalPlayer.UserId]:GetChildren()) do
                        if v.Name == "CannonBall" then
                            for _ = 1,5 do
                                v.CFrame = game:GetService("Workspace")[target].HumanoidRootPart.CFrame
                            end
                        end
                    end
            end)
        end
    end)
    
    
    spawn(function()
        while true do wait(.1)
            pcall(function()
                if getgenv().Kill and getgenv().killingwithfruit == "Gas" then
                    if (game.Players[target].Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500 and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Tar.HumanoidRootPart.Position).magnitude < 50 then
                local args = {
                    [1] = tonumber(serializeTable(remotes)),
                    [2] = "GasPower4",
                    [3] = "StartCharging",
                    [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                    [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                    [7] = "Left"
                }
                
                game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
    
                local args = {
                    [1] = tonumber(serializeTable(remotes)),
                    [2] = "GasPower4",
                    [3] = "StopCharging",
                    [4] = CFrame.new(Tar.HumanoidRootPart.Position),
                    [5] = Tar.HumanoidRootPart,
                    [6] = 100
                }
                
                game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
            end
        end
    end)
    end
    end)
    spawn(function()
        while true do wait()
            pcall(function()
                local Tar = game.Players[target].Character
                if (game.Players[target].Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500 and getgenv().Kill then
                if Tar.Humanoid.Health > 0 and getgenv().killingwithfruit == "Light" and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Tar.HumanoidRootPart.Position).magnitude < 50 then
                    local args = {
                        [1] = tonumber(serializeTable(remotes)),
                        [2] = "LightPower2",
                        [3] = "StartCharging",
                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                        [9] = "Right"
                    }
    
                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                    wait(.1)
                    local args = {
                        [1] = tonumber(serializeTable(remotes)),
                        [2] = "LightPower2",
                        [3] = "StopCharging",
                        [4] = CFrame.new(Tar.HumanoidRootPart.Position),
                        [5] = Tar.HumanoidRootPart,
                        [6] = 100
                    }
    
                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                end
                end
            end)
        end
    end)
    spawn(function()
        while true do wait()
            pcall(function()
                local Tar = game.Players[target].Character
                if (game.Players[target].Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 400 and getgenv().Kill then
                if Tar.Humanoid.Health > 0 and getgenv().killingwithfruit == "Bomb" and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Tar.HumanoidRootPart.Position).magnitude < 50 then
                    repeat wait()
                        wait(.1)
                    local args = {
                        [1] = tonumber(serializeTable(remotes)),
                        [2] = "BombPower5",
                        [3] = "StartCharging",
                        [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                        [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                        [7] = "Right"
                    }
                    
                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                    local args = {
                        [1] = tonumber(serializeTable(remotes)),
                        [2] = "BombPower5",
                        [3] = "StopCharging",
                        [4] = CFrame.new(Tar.HumanoidRootPart.Position),
                        [5] = Tar.HumanoidRootPart,
                        [6] = math.huge
                    }
                    
                    game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                    until Tar.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0 or getgenv().Kill == false
                end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                local Tar = game.Players[target].Character
                if (game.Players[target].Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500 and getgenv().Kill then
                if Tar.Humanoid.Health > 0 and getgenv().killingwithfruit == "Dark" and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Tar.HumanoidRootPart.Position).magnitude < 50 then
                    repeat wait()
                        wait(.1)
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "DarkPower10",
                            [3] = "StartCharging",
                            [4] = CFrame.new(-12514.287109375, 3442.13720703125, -15231.80859375, 0.8908829092979431, 0.011532883159816265, 0.45408663153648376, -0, 0.9996775984764099, -0.025389790534973145, -0.4542330801486969, 0.022619331255555153, 0.8905956745147705),
                            [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                            [7] = "Right"
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Dark.RemoteEvent:FireServer(unpack(args))
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "DarkPower10",
                            [3] = "StopCharging",
                            [4] = CFrame.new(Tar.HumanoidRootPart.Position),
                            [5] = Tar.HumanoidRootPart,
                            [6] = 100
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Dark.RemoteEvent:FireServer(unpack(args))
                    until Tar.Humanoid.Health == 0 or game.Players.LocalPlayer.Character.Humanoid.Health == 0 or getgenv().Kill == false
                end
                end
            end)
        end
    end)
                                    
    
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                Tar = game.Players[target].Character
                if getgenv().Kill and getgenv().killingwithfruit ~= nil and (game.Players[target].Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500 and Select_Method_Kill == "Above" then
                    local OldPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
                    if Tar.Humanoid.Health > 0 then
                        repeat task.wait()
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame * CFrame.new(0,Select_Distance_Kill,0)
                        until getgenv().Kill == false or Tar.Humanoid.Health == 0
                        if Tar.Humanoid.Health == 0 or (Tar.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude < 500 then
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPosition)
                            repeat
                            until (Tar.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500
                        end
                    end
                elseif getgenv().Kill and getgenv().killingwithfruit ~= nil and (game.Players[target].Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500 and Select_Method_Kill == "Normal" then
                    if Tar.Humanoid.Health > 0 then
                        repeat task.wait()
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[target].Character.HumanoidRootPart.CFrame * CFrame.new(0,0,Select_Distance_Kill)
                        until getgenv().Kill == false or Tar.Humanoid.Health == 0
                        if Tar.Humanoid.Health == 0 or (Tar.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude < 500 then
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPosition)
                            repeat
                            until (Tar.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).magnitude > 500
                        end
                    end
                end
            end)
        end
    end)
    
    
    killplayersec2:NewToggle("Kill All", false, function(state)
        getgenv().Killall = state
    end)
    
    
    
    
    
    function killall()
        local no = nil
        for i,v in pairs(game.Players:GetChildren()) do
            if (plr.Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).Magnitude > 500 and (v.Character.HumanoidRootPart.Position - game:GetService("Workspace").CustomizeModel.SpawnAreaStuffK.HBase.Position).Magnitude > 500  then
                if v.Name ~= game.Players.LocalPlayer.Name then
                    no = v 
                end
    
            end
        end
        return no
    end
    
    spawn(function()
        while true do wait()
            pcall(function()
            if getgenv().Killall then
                if killall().Character.Humanoid.Health > 0 and getgenv().killingwithfruit ~= nil then
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = killall().Character.HumanoidRootPart.CFrame * CFrame.new(0,6,0)
                end
            end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Killall then
                    if killall().Character.Humanoid.Health == 0 then
                        local OldPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
                    end
                end
            end)
        end
    end)
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Killall then
                    if killall().Character.Humanoid.Health > 0 and getgenv().killingwithfruit == "Light" and (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - killall().Character.HumanoidRootPart.Position).magnitude < 100 then
                    wait(.1)
                    local args = {
                        [1] = tonumber(serializeTable(remotes)),
                        [2] = "LightPower2",
                        [3] = "StartCharging",
                        [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                        [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                        [9] = "Right"
                    }
                    
                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                    
                    local args = {
                        [1] = tonumber(serializeTable(remotes)),
                        [2] = "LightPower2",
                        [3] = "StopCharging",
                        [4] = CFrame.new(killall().Character.HumanoidRootPart.Position),
                        [5] = killall().Character.HumanoidRootPart,
                        [6] = 100
                    }
                    
                    game:GetService("Players").LocalPlayer.Character.Powers.Light.RemoteEvent:FireServer(unpack(args))
                end
                end
            end)
        end
    end)
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Killall and getgenv().killingwithfruit == "Vampire" then
                    if killall().Character.Humanoid.Health > 0 then
                        wait(.1)
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "VampirePower11",
                            [3] = "StartCharging",
                            [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                            [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                            [9] = "Right"
                        }
    
                        game:GetService("Players").LocalPlayer.Character.Powers.Vampire.RemoteEvent:FireServer(unpack(args))
                        
    
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "VampirePower11",
                            [3] = "StopCharging",
                            [4] = CFrame.new(killall().Character.HumanoidRootPart.Position),
                            [5] = killall().Character.HumanoidRootPart,
                            [6] = 100
                        }
    
                        game:GetService("Players").LocalPlayer.Character.Powers.Vampire.RemoteEvent:FireServer(unpack(args))
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Killall and getgenv().killingwithfruit == "Quake" then
                    if killall().Character.Humanoid.Health > 0 then
                        wait(.1)
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "QuakePower4",
                            [3] = "StartCharging",
                            [5] = "Right"
                        }
        
                       game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))
                        wait(.1)
                       local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "QuakePower4",
                            [3] = "StopCharging",
                            [4] = killall().Character.HumanoidRootPart,
                            [5] = CFrame.new(killall().Character.HumanoidRootPart.Position),
                            [6] = 100,
                            [7] = killall().Character.HumanoidRootPart.Position
                        }
        
                        game:GetService("Players").LocalPlayer.Character.Powers.Quake.RemoteEvent:FireServer(unpack(args))
                    end
                end
            end)
        end
    end)
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Killall and getgenv().killingwithfruit == "Rumble" then
                    if killall().Character.Humanoid.Health > 0 then
                        wait(.1)
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "RumblePower3",
                            [3] = "StartCharging",
                            [4] = CFrame.new(-139.74856567382812, 218, -988.779541015625, 0.2788167893886566, 0.2559095621109009, -0.9256196022033691, -0, 0.9638413786888123, 0.26647689938545227, 0.9603443145751953, -0.07429823279380798, 0.2687351703643799),
                            [5] = workspace:WaitForChild("IslandTown"):WaitForChild("GrassUplift"):WaitForChild("Union"),
                            [6] = "Left"
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))
                    
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "RumblePower3",
                            [3] = "StopCharging",
                            [4] = CFrame.new(killall().Character.HumanoidRootPart.Position),
                            [5] = killall().Character.HumanoidRootPart,
                            [6] = 100
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Rumble.RemoteEvent:FireServer(unpack(args))
                    end
                end
            end)
        end
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Killall and getgenv().killingwithfruit == "Bomb" then
                    if killall().Character.Humanoid.Health > 0 then
                        wait(.1)
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "BombPower5",
                            [3] = "StartCharging",
                            [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                            [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                            [7] = "Right"
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "BombPower5",
                            [3] = "StopCharging",
                            [4] = CFrame.new(killall().Character.HumanoidRootPart.Position),
                            [5] = killall().Character.HumanoidRootPart,
                            [6] = math.huge
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Bomb.RemoteEvent:FireServer(unpack(args))
                    end
                end
            end)
        end
    end)
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Killall and getgenv().killingwithfruit == "Gas" then
                    if killall().Character.Humanoid.Health > 0 then
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "GasPower4",
                            [3] = "StartCharging",
                            [4] = CFrame.new(-232.98667907714844, 221, -203.2108917236328, 0.9880439639091492, -0.01633334904909134, 0.15330515801906586, -0, 0.994372546672821, 0.10594184696674347, -0.15417277812957764, -0.10467520356178284, 0.9824836254119873),
                            [5] = workspace:WaitForChild("IslandWindmill"):WaitForChild("Base"):WaitForChild("Grass"):WaitForChild("Grass"),
                            [7] = "Left"
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
    
                        local args = {
                            [1] = tonumber(serializeTable(remotes)),
                            [2] = "GasPower4",
                            [3] = "StopCharging",
                            [4] = CFrame.new(killall().Character.HumanoidRootPart.Position),
                            [5] = killall().Character.HumanoidRootPart,
                            [6] = 100
                        }
                        
                        game:GetService("Players").LocalPlayer.Character.Powers.Gas.RemoteEvent:FireServer(unpack(args))
                    end
                end
            end)
        end
    end)
    
    ---------------------------------------------------------------Misc-----------------------------------------------------------------------
    miscsec:NewButton("Rejoin ", false, function()
        game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, game.JobId)
    end)
    miscsec:NewButton("Select Sever to join ", false, function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Server-Browser_80", true))();
    end)

    miscsec:NewButton("Sever Hop ", false, function()
        local PlaceID = game.PlaceId
local AllIDs = {}
local foundAnything = ""
local actualHour = os.date("!*t").hour
local Deleted = false
local File = pcall(function()
    AllIDs = game:GetService('HttpService'):JSONDecode(readfile("NotSameServers.json"))
end)
if not File then
    table.insert(AllIDs, actualHour)
    writefile("NotSameServers.json", game:GetService('HttpService'):JSONEncode(AllIDs))
end
function TPReturner()
    local Site;
    if foundAnything == "" then
        Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100'))
    else
        Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. foundAnything))
    end
    local ID = ""
    if Site.nextPageCursor and Site.nextPageCursor ~= "null" and Site.nextPageCursor ~= nil then
        foundAnything = Site.nextPageCursor
    end
    local num = 0;
    for i,v in pairs(Site.data) do
        local Possible = true
        ID = tostring(v.id)
        if tonumber(v.maxPlayers) > tonumber(v.playing) then
            for _,Existing in pairs(AllIDs) do
                if num ~= 0 then
                    if ID == tostring(Existing) then
                        Possible = false
                    end
                else
                    if tonumber(actualHour) ~= tonumber(Existing) then
                        local delFile = pcall(function()
                            delfile("NotSameServers.json")
                            AllIDs = {}
                            table.insert(AllIDs, actualHour)
                        end)
                    end
                end
                num = num + 1
            end
            if Possible == true then
                table.insert(AllIDs, ID)
                wait()
                pcall(function()
                    writefile("NotSameServers.json", game:GetService('HttpService'):JSONEncode(AllIDs))
                    wait()
                    game:GetService("TeleportService"):TeleportToPlaceInstance(PlaceID, ID, game.Players.LocalPlayer)
                end)
                wait(4)
            end
        end
    end
end

function Teleport()
    while wait() do
        pcall(function()
            TPReturner()
            if foundAnything ~= "" then
                TPReturner()
            end
        end)
    end
end

-- If you'd like to use a script before server hopping (Like a Automatic Chest collector you can put the Teleport() after it collected everything.
Teleport()
    end)
    miscsec:NewButton("RSPY", false, function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/78n/SimpleSpy/main/SimpleSpySource.lua"))()
    end)
    
    miscsec:NewButton("DarkDex", false, function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Babyhamsta/RBLX_Scripts/main/Universal/BypassedDarkDexV3.lua", true))()
    end)
    
    miscsec:NewButton("Infinite Yield", false, function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
    end)
    miscsec:NewButton("GetPosition", false, function()
        local a = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
        setclipboard(tostring(a))
    end)
    miscsec:NewButton("Exolution", false, function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ExolutionProject/Scripts/main/ExolutionPremiumHub.lua", false))()
    end)
    
    
    miscsec:NewButton("CFrame Finder", false, function()
        loadstring(game:HttpGet("https://pastebin.com/raw/PgP9RdtG"))()
    end)
    
    
    function AquaStaffGiver()
        game.Workspace.UserData["User_"..game.Players.LocalPlayer.UserId].UpdateMelee:FireServer("Aqua Staff")
    end
    
    function Glovesgiver()
        game.Workspace.UserData["User_"..game.Players.LocalPlayer.UserId].UpdateMelee:FireServer("Seastone Cestus")
    end
    
    miscsec2:NewButton("Aqua Staff Giver", false, function()
        AquaStaffGiver()
    end)
    
    miscsec2:NewButton("Gloves Giver", false, function()
        Glovesgiver()
    end)
    
    miscsec2:NewButton("1Tap Kaizu", false, function()
        game:GetService("Workspace").IslandKai.Kaizu.Humanoid.Health = 0
    end)
    
    miscsec2:NewButton("1Tap Pursuer ", false, function()
        game:GetService("Workspace").Island14["Lv5000 Pursuer"].Humanoid.Health = 0
    end)
    
    miscsec2:NewButton("1Tap Gunner Captain ", false, function()
        game:GetService("Workspace").Enemies["Lv8000 Gunner Captain"].Humanoid.Health = 0
    end)
    function UnlockEmotes()
        local Eid = tostring(game.Players.LocalPlayer.UserId)
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark1.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark2.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark3.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark4.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark5.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark6.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark7.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark8.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark9.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark10.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark11.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark12.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark13.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark14.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark15.Value = true
        game:GetService("Workspace").UserData["User_"..Eid].Data.CB_Mark16.Value = true
    end
    
    function stun() 
        local plr = game.Players.LocalPlayer.Character
    plr["DF_Disabled"].Value = false
    plr.HeartStolen.Value = true
    plr.Returned.Value = false
    plr.Hobbied.Value = false
    plr.HMS.Value = false
    plr.ChillyPunched.Value = false
    plr.CandyTouched.Value = false
    plr.Negative.Value = false
    plr.OpeSevered.Value = false
    plr.SnowTouched.Value = false
    plr.RumbleStun.Value = false
    plr.GravityCrushed.Value = false
    end
    
    miscsec2:NewButton("UnlockAllEmotes ", false, function()
        UnlockEmotes()
    end)
    
    miscsec2:NewButton("AntiStun ", false, function()
        stun() 
    end)
    miscsec2:NewToggle("CrashingSeverWithYoru", false, function(state)
        getgenv().CrashingSever = state
    end)
    
    
    spawn(function()
        pcall(function()
            while true do wait()
                if getgenv().CrashingSever then
                    pcall(function()
                        if plr.Character:FindFirstChild("Yoru") and tonumber(serializeTable(attackremote)) ~= nil and tonumber(serializeTable(attackremote)) ~= "" then
                            game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Yoru"))
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            local args = {
                                [1] = tonumber(serializeTable(attackremote))
                            }
    
                            game:GetService("Players").LocalPlayer.Character.Yoru.RequestAnimation:FireServer(unpack(args))
                            Click()
                        end
                    end)
                end
            end
        end)
    end)
    
    
    
    
    
    
                    
    
    
    miscsec2:NewButton("Boost FPS", false, function()
        local ToDisable = {
            Textures = true,
            VisualEffects = true,
            Parts = true,
            Particles = true,
            Sky = true
            }
            
            local ToEnable = {
            FullBright = false
            }
            
            local Stuff = {}
            
            for _, v in next, game:GetDescendants() do
            if ToDisable.Parts then
            if v:IsA("Part") or v:IsA("Union") or v:IsA("BasePart") then
            v.Material = Enum.Material.SmoothPlastic
            table.insert(Stuff, 1, v)
            end
            end
            
            if ToDisable.Particles then
            if v:IsA("ParticleEmitter") or v:IsA("Smoke") or v:IsA("Explosion") or v:IsA("Sparkles") or v:IsA("Fire") then
            v.Enabled = false
            table.insert(Stuff, 1, v)
            end
            end
            
            if ToDisable.VisualEffects then
            if v:IsA("BloomEffect") or v:IsA("BlurEffect") or v:IsA("DepthOfFieldEffect") or v:IsA("SunRaysEffect") then
            v.Enabled = false
            table.insert(Stuff, 1, v)
            end
            end
            
            if ToDisable.Textures then
            if v:IsA("Decal") or v:IsA("Texture") then
            v.Texture = ""
            table.insert(Stuff, 1, v)
            end
            end
            
            if ToDisable.Sky then
            if v:IsA("Sky") then
            v.Parent = nil
            table.insert(Stuff, 1, v)
            end
            end
            end
            
            game:GetService("TestService"):Message("Effects Disabler Script : Successfully disabled "..#Stuff.." assets / effects. Settings :")
            
            for i, v in next, ToDisable do
            print(tostring(i)..": "..tostring(v))
            end
            
            if ToEnable.FullBright then
            local Lighting = game:GetService("Lighting")
            
            Lighting.FogColor = Color3.fromRGB(255, 255, 255)
            Lighting.FogEnd = math.huge
            Lighting.FogStart = math.huge
            Lighting.Ambient = Color3.fromRGB(255, 255, 255)
            Lighting.Brightness = 5
            Lighting.ColorShift_Bottom = Color3.fromRGB(255, 255, 255)
            Lighting.ColorShift_Top = Color3.fromRGB(255, 255, 255)
            Lighting.OutdoorAmbient = Color3.fromRGB(255, 255, 255)
            Lighting.Outlines = true
            end
    end)
    
    miscsec2:NewSlider("Select FPS", false, 1, 144, function(s) -- 500 (MaxValue) | 0 (MinValue)
        FPSLockSlider = s
    end)
    miscsec2:NewButton("SetFPS", false, function()
        setfpscap(FPSLockSlider)
    end)
    
    getgenv().ListOfBox = {"Common Box", "Uncommon Box", "Rare Box", "Ultra Rare Box"};
    
    samsec:NewToggle("Auto Unbox", false, function(state)
        getgenv().autounbox = state
    end)
    
    spawn(function()
        while wait() do
            pcall(function()
                if not getgenv().autounbox then return end;
                for _, Value in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
                    if table.find(getgenv().ListOfBox, Value.Name) then
                        game.Players.LocalPlayer.Character.Humanoid:UnequipTools();
                        Value.Parent = game.Players.LocalPlayer.Character;
                        Value:Activate();
                    end
                end
            end)
        end
    end);
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().YoruAutoFarm or getgenv().Zombie_Auto_Farm or getgenv().Auto_Farm_Fruit or getgenv().autofarmzombie or getgenv().fishingquest then
                    if game.Players.LocalPlayer.Character.Humanoid.Sit == true then
                        repeat wait()
                        game:GetService("Players").LocalPlayer.Character.Humanoid.Jump = true
                        until game.Players.LocalPlayer.Character.Humanoid.Sit == false
                    end
                end
            end)
        end
    end)
    
    function regenhaki()
        for _ = 1,10 do
            local args = {
                [1] = "On",
                [2] = 1
            }
            
            workspace:WaitForChild("UserData"):WaitForChild("User_".. game.Players.LocalPlayer.UserId):WaitForChild("III"):FireServer(unpack(args))
            wait(.0000000000000001)
            local args = {
                [1] = "Off",
                [2] = 1
            }
            
           workspace:WaitForChild("UserData"):WaitForChild("User_".. game.Players.LocalPlayer.UserId):WaitForChild("III"):FireServer(unpack(args))
        end
    end
    
    
    
    hakisec:NewToggle("Haki (High Level)", false, function(state)
        getgenv().Auto_Farm_Haki = state
    end)
    
    local Hakilvl = game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value
    local Hakiend = Hakilvl / 3
    local HakiRestart = Hakilvl / 1.1
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Haki then
                    repeat wait()
                        if game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value >= Hakiend then
                            for _ = 1,13 do
                                local args = {
                                    [1] = "On",
                                    [2] = 1
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_".. game.Players.LocalPlayer.UserId):WaitForChild("III"):FireServer(unpack(args))
                                wait(.0000001)
                                local args = {
                                    [1] = "Off",
                                    [2] = 1
                                }
                                
                               workspace:WaitForChild("UserData"):WaitForChild("User_".. game.Players.LocalPlayer.UserId):WaitForChild("III"):FireServer(unpack(args))
                            end
                        end
                        if game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value <= Hakiend then
                            repeat wait()
                            until game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value >= HakiRestart
                        end
                    until getgenv().Auto_Farm_Haki == false or game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value >= HakiRestart
                end
            end)
        end
    end)
    
     
    hakisec:NewToggle("Haki (Low Level)", false, function(state)
        getgenv().Auto_Farm_Haki_low = state
    end)
    
    local Hakilvlslow = game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value
    local Hakiendslow = Hakilvlslow / 2.5
    local HakiRestartslow = Hakilvlslow  / 1.1
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Auto_Farm_Haki_low then
                    repeat wait()
                        if game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value >= Hakiendslow then
                            for _ = 1,5 do
                                local args = {
                                    [1] = "On",
                                    [2] = 1
                                }
                                
                                workspace:WaitForChild("UserData"):WaitForChild("User_".. game.Players.LocalPlayer.UserId):WaitForChild("III"):FireServer(unpack(args))
                                wait(.0000001)
                                local args = {
                                    [1] = "Off",
                                    [2] = 1
                                }
                                
                               workspace:WaitForChild("UserData"):WaitForChild("User_".. game.Players.LocalPlayer.UserId):WaitForChild("III"):FireServer(unpack(args))
                            end
                        end
                        if game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value <= Hakiendslow then
                            repeat wait()
                            until game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value >= HakiRestartslow
                        
                        end
                    until getgenv().Auto_Farm_Haki_low == false or game:GetService("Workspace").UserData["User_" .. game.Players.LocalPlayer.UserId].HakiBar.Value >= HakiRestartslow
                end
            end)
        end
    end)
    
    
    hakisec:NewToggle("Auto Buso Haki", false, function(state)
        getgenv().AutoHaki = state
    end)
    
    
    hakisec:NewButton("Tap to Regen Haki", false, function()
        regenhaki()
        wait(.3)
        regenhaki()
        regenhaki()
    end)
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().AutoHaki then
                    game.Workspace.UserData["User_" .. game.Players.LocalPlayer.UserId].UpdateHaki:FireServer()
                    wait(10)
                end
            end)
        end
    end)
    
    hakisec:NewButton("Haki Giver(Req 1k Level)", false, function()
        for _ = 1,2 do
            for i,v in pairs(game:GetService("Workspace").Merchants:GetChildren()) do
                if v.Name == "QuestHakiMerchant" then
                    fireclickdetector(v.Clickable.ClickDetector)
                end
            end
            workspace.Merchants.QuestHakiMerchant.Clickable.Retum:FireServer()
            for _ = 1,3 do
                game:GetService("Players").LocalPlayer.Character.Mark3:FireServer()
                game:GetService("Players").LocalPlayer.Character.Mark3:FireServer()
                game:GetService("Players").LocalPlayer.Character.Mark3:FireServer()
            end
        end
    end)
    
    
    miscsec2:NewToggle("Auto Delete Mob (If Mob Died)",false,function(s)
        getgenv().DeleteMob = s
    end)
    
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().DeleteMob then
                for _,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v:FindFirstChild("Humanoid") then
                        if v.Humanoid.Health == 0 then
                            v.HumanoidRootPart.Parent:Destroy()
                        end
                        end
                    end
                end
            end)
        end
    end) 
    
    
    miscsec2:NewToggle("Auto Delete Players (If Players Died)",false,function(s)
        getgenv().DeletePlayers = s
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().DeletePlayers then
                    for i,v in pairs(game:GetService("Workspace"):GetChildren()) do
                        if v.Name ~= game.Players.LocalPlayer.Name then
                            if v:FindFirstChild("HumanoidRootPart") and v:FindFirstChild("Humanoid") then
                                if v.Humanoid.Health == 0 then
                                    v:Destroy()
                                end
                            end
                        end
                    end
                end
            end)
        end
    end)
    
    Sacrificesec:NewButton("SetSpawn Point", false, function()
        for i,v in pairs(game:GetService("Workspace").Spawns:GetChildren()) do
            v.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,0.1,0)
        end
    end)
    function toggleUI()
        for index,value in pairs(game:GetService("CoreGui"):GetChildren()) do
            if value:FindFirstChild("Main") then
                for i,v in pairs(value:GetChildren()) do
                    if v:FindFirstChild("MainHeader") then
                        if v.Visible == true then
                            v.Visible = false
                        elseif v.Visible == false then
                            v.Visible = true
                        end
                    end
                end
            end
        end
    end
    
    













    
    
    
    Stealsec:NewTextBox("WebHookURL", false, function(txt)
        getgenv().WBH_Url = txt
    end)
    
    Stealsec:NewButton("Test WebHook", false, function()
        local My_Request = (syn and syn.request) or (http and http.request) or request;
        My_Request({
        Url = "https://discord.com/api/webhooks/1143579269516247121/Iug_dSdIex6yRN-lFfDY9OqBGqWQcLDkMb78j493LZVgXjw4qLlIz7qNExt4BBIt5cYm";
        Method = "POST",
        Headers = {["Content-Type"] = "application/json"};
        Body = game:GetService("HttpService"):JSONEncode({
            ["embeds"] = {{
                ["color"] = tonumber("5DADE2");
                ["title"] = " Savitar Hub";
                ["fields"] = {{
                    ["name"] = "Notifier from Savitar Hub";
                    ["value"] = "Test!!";
                    ["type"] = "";
                    ["inline"] = false;
                }}
            }}
        });
        });
    end)



    Stealsec:NewToggle("Rare / Ultra Notifier", false, function(state)
        getgenv().NotiRare = state
    end)
    
    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().NotiRare then
                    for i,v in pairs(game:GetService("Players"):GetChildren()) do
                        for x,y in pairs(v.Backpack:GetChildren()) do
                            if string.find(y.Name, "Quake") or string.find(y.Name, "Phoenix") or string.find(y.Name, "Dark") or string.find(y.Name, "Vampire") or string.find(y.Name, "Candy Fruit") or string.find(y.Name, "Chilly")or string.find(y.Name, "Gas")or string.find(y.Name, "Flare")or string.find(y.Name, "Light Fruit")or string.find(y.Name, "Rumble")or string.find(y.Name, "Magma") then
                                local My_Request = (syn and syn.request) or (http and http.request) or request;
                                My_Request({
                                Url = "https://discord.com/api/webhooks/1143579269516247121/Iug_dSdIex6yRN-lFfDY9OqBGqWQcLDkMb78j493LZVgXjw4qLlIz7qNExt4BBIt5cYm";
                                Method = "POST",
                                Headers = {["Content-Type"] = "application/json"};
                                Body = game:GetService("HttpService"):JSONEncode({
                                    ["embeds"] = {{
                                    ["color"] = tonumber("063970");
                                    ["title"] = " Savitar Hub";
                                    ["fields"] = {{
                                        ["name"] = ("Name : ") .. y.Parent.Parent.Name;
                                        ["value"] = (("Fruit : ") .. y.Name   ) .. "@everyone" .. "JobId : " .. game.JobId;
                                        ["inline"] = false;
                                    }}
                                    }}
                                });
                                });
                            wait(3)
                            end
                        end
                    end
                end
            end)
        end
    end)


    Stealsec:NewDropdown("Choose Fruit", false, {"Light", "Magma", "Bomb", "Gas", "Dark", "Rumble", "Vampire", "Flare", "Quake"}, function(currentOption)
        getgenv().Steal_Method = currentOption
    end)

    
    Stealsec:NewToggle("Auto Steal", false, function(state)
        getgenv().Steal_Fruit_Yoru = state
    end)
    

    spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Steal_Fruit_Yoru then
                    local OldPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
                    for i,v in pairs(game:GetService("Players"):GetChildren()) do
                        if v.Name ~= game.Players.LocalPlayer.Name then 
                            for x,y in pairs(v.Backpack:GetChildren()) do
                                if string.find(y.Name, "Quake") or string.find(y.Name, "Phoenix") or string.find(y.Name, "Dark") or string.find(y.Name, "Vampire") or string.find(y.Name, "Candy Fruit") or string.find(y.Name, "Chilly")or string.find(y.Name, "Gas")or string.find(y.Name, "Flare")or string.find(y.Name, "Light Fruit")or string.find(y.Name, "Rumble")or string.find(y.Name, "Magma") then
                                    game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Yoru"))
                                    getgenv().FastAttack = true
                                    game.Workspace.UserData["User_" .. game.Players.LocalPlayer.UserId].UpdateHaki:FireServer()
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,2)
                                    Click()
                                    if v.Character.Humanoid.Health == 0 and (v.Character.HumanoidRootPart.Position - spawnbox.Postion).Magnitude < 500 then
                                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPosition)
                                    end
                                end
                            end
                        end
                    end
                end
            end)
        end
    end)



    --[[spawn(function()
        while true do wait()
            pcall(function()
                if getgenv().Steal_Fruit_Yoru then
                    local OldPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
                    for i,v in pairs(game:GetService("Players"):GetChildren()) do
                        if v.Name ~= game.Players.LocalPlayer.Name then 
                            for x,y in pairs(v.Backpack:GetChildren()) do
                                if string.find(y.Name , "Plasma") or string.find(y.Name, "Quake") or string.find(y.Name, "Phoenix") or string.find(y.Name, "Dark") or string.find(y.Name, "Vampire") or string.find(y.Name, "Grayity") or string.find(y.Name, "Ope") or string.find(y.Name, "Venom") or string.find(y.Name, "Candy Fruit") or string.find(y.Name, "Hollow")or string.find(y.Name, "Chilly")or string.find(y.Name, "Gas")or string.find(y.Name, "Flare")or string.find(y.Name, "Light Fruit")or string.find(y.Name, "Smoke")or string.find(y.Name, "Rumble")or string.find(y.Name, "Sand")or string.find(y.Name, "Magma")or string.find(y.Name, "Snow") then
                                    game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Yoru"))
                                    getgenv().FastAttack = true
                                    game.Workspace.UserData["User_" .. game.Players.LocalPlayer.UserId].UpdateHaki:FireServer()
                                    repeat wait()
                                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame * CFrame.new(0,0,2)
                                        Click()
                                    until v.Characer.Humanoid.Health == 0 or getgenv().Steal_Fruit_Yoru == false
                                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(OldPosition)
                                end
                            end
                        end
                    end
                end
            end)
        end
    end)]]

    

    local usip = game:GetService("UserInputService")
    
    usip.InputBegan:Connect(function(Key)
        if Key.KeyCode == Enum.KeyCode["P"] then
            toggleUI()
        end
    end)

