-- Gui to Lua
-- Version: 3.2

-- Instances:

local MainScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Title = Instance.new("Folder")
local MainBackAText = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local Stats = Instance.new("Folder")
local StatsLabel = Instance.new("TextLabel")
local FarmedGemIcon = Instance.new("ImageLabel")
local FarmedGems = Instance.new("TextLabel")
local CloseGui = Instance.new("Folder")
local DestroyGui = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Footer = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local UserInfo = Instance.new("Folder")
local pfp = Instance.new("ImageLabel")
local UICorner_5 = Instance.new("UICorner")
local Username = Instance.new("TextLabel")
local GuiStatus = Instance.new("TextLabel")
local MainFarms = Instance.new("Folder")
local FirstFarm = Instance.new("Folder")
local DiamondMineFarmbutton = Instance.new("TextButton")
local DiamondMineFarm = Instance.new("TextLabel")
local Comet = Instance.new("Folder")
local CometFarmText = Instance.new("TextLabel")
local CometFarm = Instance.new("TextButton")
local LoadingScreen = Instance.new("Frame")
local UICorner_6 = Instance.new("UICorner")
local FarmedGems_2 = Instance.new("TextLabel")
local Info = Instance.new("TextLabel")
local Loading = Instance.new("TextLabel")

--Properties:

MainScreenGui.Name = "MainScreenGui"
MainScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
MainScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = MainScreenGui
Main.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Main.Position = UDim2.new(0.27543804, 0, 0.223191991, 0)
Main.Size = UDim2.new(0.448263407, 0, 0.552369118, 0)
Main.Visible = false

UICorner.CornerRadius = UDim.new(0, 19)
UICorner.Parent = Main

Title.Name = "Title"
Title.Parent = Main

MainBackAText.Name = "MainBackAText"
MainBackAText.Parent = Title
MainBackAText.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
MainBackAText.Position = UDim2.new(0.00136279734, 0, 3.44442164e-08, 0)
MainBackAText.Size = UDim2.new(0.995911658, 0, 0.158013538, 0)
MainBackAText.Font = Enum.Font.FredokaOne
MainBackAText.Text = "A1 Josh"
MainBackAText.TextColor3 = Color3.fromRGB(255, 255, 255)
MainBackAText.TextSize = 46.000
MainBackAText.TextWrapped = true

UICorner_2.CornerRadius = UDim.new(0, 19)
UICorner_2.Parent = MainBackAText

Stats.Name = "Stats"
Stats.Parent = Main

StatsLabel.Name = "StatsLabel"
StatsLabel.Parent = Stats
StatsLabel.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
StatsLabel.BackgroundTransparency = 1.000
StatsLabel.Position = UDim2.new(0.6391325, 0, 0.203160286, 0)
StatsLabel.Size = UDim2.new(0.279102087, 0, 0.13995485, 0)
StatsLabel.Font = Enum.Font.FredokaOne
StatsLabel.Text = "Stat Tracker"
StatsLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
StatsLabel.TextScaled = true
StatsLabel.TextSize = 46.000
StatsLabel.TextWrapped = true

FarmedGemIcon.Name = "FarmedGemIcon"
FarmedGemIcon.Parent = Stats
FarmedGemIcon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FarmedGemIcon.BackgroundTransparency = 1.000
FarmedGemIcon.Position = UDim2.new(0.62757951, 0, 0.345008314, 0)
FarmedGemIcon.Size = UDim2.new(0.0474311188, 0, 0.0767494291, 0)
FarmedGemIcon.Image = "rbxassetid://13751507714"

FarmedGems.Name = "FarmedGems"
FarmedGems.Parent = Stats
FarmedGems.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
FarmedGems.BackgroundTransparency = 1.000
FarmedGems.Position = UDim2.new(0.685463667, 0, 0.343115121, 0)
FarmedGems.Size = UDim2.new(0.285915881, 0, 0.081264101, 0)
FarmedGems.Font = Enum.Font.FredokaOne
FarmedGems.Text = "Farmed 100,000,000 Gems"
FarmedGems.TextColor3 = Color3.fromRGB(255, 255, 255)
FarmedGems.TextScaled = true
FarmedGems.TextSize = 46.000
FarmedGems.TextWrapped = true

CloseGui.Name = "CloseGui"
CloseGui.Parent = Main

DestroyGui.Name = "DestroyGui"
DestroyGui.Parent = CloseGui
DestroyGui.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
DestroyGui.Position = UDim2.new(0.89805603, 0, 3.35276127e-08, 0)
DestroyGui.Size = UDim2.new(0.1046694, 0, 0.16027087, 0)
DestroyGui.Font = Enum.Font.FredokaOne
DestroyGui.Text = "X"
DestroyGui.TextColor3 = Color3.fromRGB(255, 255, 255)
DestroyGui.TextScaled = true
DestroyGui.TextSize = 14.000
DestroyGui.TextWrapped = true

UICorner_3.CornerRadius = UDim.new(0, 20)
UICorner_3.Parent = DestroyGui

Footer.Name = "Footer"
Footer.Parent = Main
Footer.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Footer.Position = UDim2.new(-0.000148767998, 0, 0.865060985, 0)
Footer.Size = UDim2.new(0.997462511, 0, 0.133976534, 0)

UICorner_4.CornerRadius = UDim.new(0, 19)
UICorner_4.Parent = Footer

UserInfo.Name = "UserInfo"
UserInfo.Parent = Footer

pfp.Name = "pfp"
pfp.Parent = UserInfo
pfp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
pfp.Position = UDim2.new(0.0287990645, 0, 0.0625, 0)
pfp.Size = UDim2.new(0, 59, 0, 55)
pfp.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner_5.Parent = pfp

Username.Name = "Username"
Username.Parent = UserInfo
Username.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Username.BackgroundTransparency = 1.000
Username.Position = UDim2.new(0.124397993, 0, 0.0505482852, 0)
Username.Size = UDim2.new(0.338356972, 0, 0.511837125, 0)
Username.Font = Enum.Font.FredokaOne
Username.Text = "Welcome A1Josh "
Username.TextColor3 = Color3.fromRGB(255, 255, 255)
Username.TextSize = 20.000
Username.TextWrapped = true
Username.TextXAlignment = Enum.TextXAlignment.Left

GuiStatus.Name = "GuiStatus"
GuiStatus.Parent = UserInfo
GuiStatus.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
GuiStatus.BackgroundTransparency = 1.000
GuiStatus.Position = UDim2.new(0.125765041, 0, 0.556010604, 0)
GuiStatus.Size = UDim2.new(0.10732425, 0, 0.292803466, 0)
GuiStatus.Font = Enum.Font.FredokaOne
GuiStatus.Text = "Premium"
GuiStatus.TextColor3 = Color3.fromRGB(0, 195, 255)
GuiStatus.TextScaled = true
GuiStatus.TextSize = 46.000
GuiStatus.TextWrapped = true

MainFarms.Name = "MainFarms"
MainFarms.Parent = Main

FirstFarm.Name = "FirstFarm"
FirstFarm.Parent = MainFarms

DiamondMineFarmbutton.Name = "DiamondMineFarmbutton"
DiamondMineFarmbutton.Parent = FirstFarm
DiamondMineFarmbutton.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
DiamondMineFarmbutton.BorderColor3 = Color3.fromRGB(50, 50, 50)
DiamondMineFarmbutton.BorderSizePixel = 3
DiamondMineFarmbutton.Position = UDim2.new(0.383983105, 0, 0.237020329, 0)
DiamondMineFarmbutton.Size = UDim2.new(0.0433079191, 0, 0.069977425, 0)
DiamondMineFarmbutton.ZIndex = 5
DiamondMineFarmbutton.Font = Enum.Font.FredokaOne
DiamondMineFarmbutton.Text = ""
DiamondMineFarmbutton.TextColor3 = Color3.fromRGB(255, 255, 255)
DiamondMineFarmbutton.TextScaled = true
DiamondMineFarmbutton.TextSize = 14.000
DiamondMineFarmbutton.TextWrapped = true

DiamondMineFarm.Name = "DiamondMineFarm"
DiamondMineFarm.Parent = FirstFarm
DiamondMineFarm.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
DiamondMineFarm.BackgroundTransparency = 1.000
DiamondMineFarm.Position = UDim2.new(0.0405170172, 0, 0.200902954, 0)
DiamondMineFarm.Size = UDim2.new(0.279102087, 0, 0.13995485, 0)
DiamondMineFarm.Font = Enum.Font.FredokaOne
DiamondMineFarm.Text = "Farm Enabled"
DiamondMineFarm.TextColor3 = Color3.fromRGB(255, 255, 255)
DiamondMineFarm.TextSize = 33.000
DiamondMineFarm.TextWrapped = true

Comet.Name = "Comet"
Comet.Parent = MainFarms

CometFarmText.Name = "CometFarmText"
CometFarmText.Parent = Comet
CometFarmText.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
CometFarmText.BackgroundTransparency = 1.000
CometFarmText.Position = UDim2.new(0.0282447189, 0, 0.313769758, 0)
CometFarmText.Size = UDim2.new(0.279102087, 0, 0.13995485, 0)
CometFarmText.Font = Enum.Font.FredokaOne
CometFarmText.Text = "Comet Farm"
CometFarmText.TextColor3 = Color3.fromRGB(255, 255, 255)
CometFarmText.TextSize = 33.000
CometFarmText.TextWrapped = true

CometFarm.Name = "CometFarm"
CometFarm.Parent = Comet
CometFarm.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
CometFarm.BorderColor3 = Color3.fromRGB(50, 50, 50)
CometFarm.BorderSizePixel = 3
CometFarm.Position = UDim2.new(0.383983105, 0, 0.347629786, 0)
CometFarm.Size = UDim2.new(0.0433079191, 0, 0.069977425, 0)
CometFarm.ZIndex = 5
CometFarm.Font = Enum.Font.FredokaOne
CometFarm.Text = ""
CometFarm.TextColor3 = Color3.fromRGB(255, 255, 255)
CometFarm.TextScaled = true
CometFarm.TextSize = 14.000
CometFarm.TextWrapped = true

LoadingScreen.Name = "LoadingScreen"
LoadingScreen.Parent = MainScreenGui
LoadingScreen.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
LoadingScreen.Position = UDim2.new(0.331672788, 0, 0.392768085, 0)
LoadingScreen.Size = UDim2.new(0.336405188, 0, 0.21321699, 0)

UICorner_6.CornerRadius = UDim.new(0, 19)
UICorner_6.Parent = LoadingScreen

FarmedGems_2.Name = "FarmedGems"
FarmedGems_2.Parent = LoadingScreen
FarmedGems_2.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
FarmedGems_2.BackgroundTransparency = 1.000
FarmedGems_2.Position = UDim2.new(0.135370761, 0, 0.0575400777, 0)
FarmedGems_2.Size = UDim2.new(0.727446198, 0, 0.413379163, 0)
FarmedGems_2.Font = Enum.Font.FredokaOne
FarmedGems_2.Text = "A1 Josh Loader - PSX"
FarmedGems_2.TextColor3 = Color3.fromRGB(255, 255, 255)
FarmedGems_2.TextScaled = true
FarmedGems_2.TextSize = 46.000
FarmedGems_2.TextWrapped = true

Info.Name = "Info"
Info.Parent = LoadingScreen
Info.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Info.BackgroundTransparency = 1.000
Info.Position = UDim2.new(0.209867597, 0, 0.396721303, 0)
Info.Size = UDim2.new(0.578452528, 0, 0.150221378, 0)
Info.Font = Enum.Font.FredokaOne
Info.Text = "Thank you for choosing A1Josh"
Info.TextColor3 = Color3.fromRGB(60, 60, 60)
Info.TextScaled = true
Info.TextSize = 46.000
Info.TextWrapped = true

Loading.Name = "Loading"
Loading.Parent = LoadingScreen
Loading.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Loading.BackgroundTransparency = 1.000
Loading.Position = UDim2.new(0.244390532, 0, 0.735902548, 0)
Loading.Size = UDim2.new(0.509406567, 0, 0.191157028, 0)
Loading.Font = Enum.Font.FredokaOne
Loading.Text = "[ Loading Gui...]"
Loading.TextColor3 = Color3.fromRGB(255, 255, 255)
Loading.TextScaled = true
Loading.TextSize = 46.000
Loading.TextWrapped = true

-- Scripts:

local function MJFM_fake_script() -- Main.DragGui 
	local script = Instance.new('Script', Main)

	-- Place this script inside the GUI panel you want to make movable
	
	local gui = script.Parent
	local userInputService = game:GetService("UserInputService")
	
	local dragging
	local dragStart
	local startPos
	local sensitivity = 0.5 -- Adjust this value to control the movement speed
	
	local function updateDrag(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X * sensitivity, startPos.Y.Scale, startPos.Y.Offset + delta.Y * sensitivity)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement then
			if dragging then
				updateDrag(input)
			end
		end
	end)
	
end
coroutine.wrap(MJFM_fake_script)()
local function QSDUF_fake_script() -- FarmedGems.Script 
	local script = Instance.new('Script', FarmedGems)

	local GemCount = require(game:GetService("ReplicatedStorage").Library).Save.Get().Diamonds
	local LastGems = 0
	
	local function CalculateGemDifference(gems)
		if GainsOnly then
			if gems < LastGems then
				gems = LastGems
			end
		end
		local formatted = tostring(gems)
		while true do
			formatted, k = string.gsub(formatted, "^(-?%d+)(%d%d%d)", '%1,%2')
			if (k == 0) then
				break
			end
		end
		LastGems = gems
		return "Farmed " .. formatted .. " Gems"
	end
	
	while wait(0.033) do
		script.Parent.Text = CalculateGemDifference(require(game:GetService("ReplicatedStorage").Library).Save.Get().Diamonds - GemCount)
	end
	
end
coroutine.wrap(QSDUF_fake_script)()
local function ULZBMU_fake_script() -- DestroyGui.Script 
	local script = Instance.new('Script', DestroyGui)

	local button = script.Parent
	local maingui = script.Parent.Parent.Parent.Parent.Main
	
	button.MouseButton1Click:Connect(function()
		maingui:Destroy()
		
	end)
end
coroutine.wrap(ULZBMU_fake_script)()
local function RGJJN_fake_script() -- Username.Script 
	local script = Instance.new('Script', Username)

	local username = script.Parent
	local player = game.Players.LocalPlayer
	
	username.Text = "Welcome, " .. player.Name
	
end
coroutine.wrap(RGJJN_fake_script)()
local function GPSJKJ_fake_script() -- GuiStatus.Script 
	local script = Instance.new('Script', GuiStatus)

	local text = script.Parent
	local player = game.Players.LocalPlayer
	
	if player.Name == ("user1434323525325") then
		text.Text = "Premium" 
	else
		text.Text = "Standard"
	end
	
end
coroutine.wrap(GPSJKJ_fake_script)()
local function ADKKOH_fake_script() -- DiamondMineFarmbutton.Script 
	local script = Instance.new('Script', DiamondMineFarmbutton)

	local button = script.Parent
	
	local defaultColor = Color3.fromRGB(30, 30, 30)
	local altColor = Color3.fromRGB(50, 50, 50)
	
	local isDefaultColor = true
	
	button.AutoButtonColor = false
	
	button.MouseButton1Click:Connect(function()
		if isDefaultColor then
			button.BackgroundColor3 = altColor
			isDefaultColor = false
		else
			button.BackgroundColor3 = defaultColor
			isDefaultColor = true
		end
	end)
	
	local webhook = "WEBHOOK_URL_HERE"
	local currencyName = "Diamonds"
	local updateDelay = 600
	
	local playerId = game.Players.LocalPlayer.UserId
	
	local Library = require(game.ReplicatedStorage.Library)
	Library.Load()
	
	local function formatNumber(number)
		return tostring(number):reverse():gsub("%d%d%d", "%1,"):reverse():gsub("^,", "")
	end
	
	local function getCurrentCurrencyAmount()
		local saveData = Library.Save.Get()
		if not saveData then return nil end
		return saveData[currencyName]
	end
	
	local function sendUpdate(currentAmount, totalAmount, deltaAmount, totalTime)
		local embed = {
			["title"] = "Currency Update",
			["color"] = tonumber("0x00FF00", 16),
			["fields"] = {
				{
					["name"] = "Current "..currencyName,
					["value"] = formatNumber(currentAmount),
					["inline"] = true
				},
				{
					["name"] = "Total "..currencyName.." Earned / Total Time",
					["value"] = formatNumber(totalAmount).." / "..formatNumber(totalTime).." minutes",
					["inline"] = true
				},
				{
					["name"] = "Last 10 minutes",
					["value"] = formatNumber(deltaAmount),
					["inline"] = true
				}
			},
			["footer"] = {
				["text"] = "I like tacos idk"
			}
		}
	
		(syn and syn.request or http_request or http.request) {
			Url = webhook;
			Method = 'POST';
			Headers = {
				['Content-Type'] = 'application/json';
			};
			Body = game:GetService('HttpService'):JSONEncode({
				username = "Gem Tracker",
				avatar_url = 'https://i.imgur.com/5b6NmEo.png',
				embeds = {embed}
			})
		}
	end
	
	local currentAmount = getCurrentCurrencyAmount() or 0
	local totalAmount = 0
	local last10MinAmount = 0
	local totalTime = 0
	
	sendUpdate(currentAmount, totalAmount, last10MinAmount, totalTime)
	
	while true do
		wait(updateDelay)
		local newAmount = getCurrentCurrencyAmount() or 0
		local deltaAmount = newAmount - currentAmount
		totalAmount = totalAmount + deltaAmount
		last10MinAmount = deltaAmount
		currentAmount = newAmount
		totalTime = totalTime + (updateDelay / 60)
		sendUpdate(currentAmount, totalAmount, last10MinAmount, totalTime)
	end
	
end
coroutine.wrap(ADKKOH_fake_script)()
local function VGJHXSA_fake_script() -- CometFarm.Script 
	local script = Instance.new('Script', CometFarm)

	local TextButton = script.Parent
	
	
	local defaultColor = Color3.fromRGB(30, 30, 30)
	local altColor = Color3.fromRGB(50, 50, 50)
	
	local isDefaultColor = true
	
	TextButton.AutoButtonColor = false
	
	TextButton.MouseButton1Click:Connect(function()
		if isDefaultColor then
			TextButton.BackgroundColor3 = altColor
			isDefaultColor = false
		else
			TextButton.BackgroundColor3 = defaultColor
			isDefaultColor = true
		end
	end)
	
		TextButton.MouseButton1Click:Connect(function()
			spawn(function()
				while not game:IsLoaded() do
				wait(1)
			end
				wait(4)
				targetmulti = 5 -- If The Multiplier Of A Coin Is Higher Or Equal To This It Will Break It
				breakgiantchest = true -- Weather To Break The Giant Mine Chest Even If Its Below The Multi
				breakbigchests = true -- Weather To Break The Big Mine Chests Even If They Are Below The Multi
			WEBHOOK = "https://discord.com/api/webhooks/1118635565013807184/Wd04kH2J5yeqqqKF22mNduFqzU8pAqX6JDfLZIr92F9c-6wYn68RjvS4Qq1r_41XEP7c" -- Webhook
	
				local oldJob = game.JobId
	
				local v1 = require(game.ReplicatedStorage:WaitForChild("Framework"):WaitForChild("Library"))
				while not v1.Loaded do
				game:GetService("RunService").Heartbeat:Wait()
			end
	
				local Network = require(game:GetService("ReplicatedStorage").Library.Client.Network)
				local Fire, Invoke = Network.Fire, Network.Invoke
	
				local old
				old = hookfunction(getupvalue(Fire, 1), function(...)
					return true
				end)
	
				Lib = require(game:GetService("ReplicatedStorage").Library)
	
				wait(6)
	
				local function serverHop()
					repeat
					local data = game:GetService("HttpService"):JSONDecode(game:HttpGet("https://games.roblox.com/v1/games/"..game.PlaceId.."/servers/Public?sortOrder=Asc&excludeFullGames=true&limit=100"))
					local bestserver
					for i,v in pairs(data.data) do
						if (tonumber(v.playing) < 12) and (tonumber(v.playing) > 1) then
							bestserver = v.id
						end
					end
	
					game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, bestserver, game.Players.LocalPlayer)
					task.wait(1)
				until oldJob ~= game.JobId
				end
	
				local TimeElapsed = 0
				local GemsEarned = 0
				local TotalGemsEarned = 0
				local Library = require(game:GetService("ReplicatedStorage").Library)
				local StartingGems = Library.Save.Get().Diamonds
	
				local timer = coroutine.create(function()
					while 1 do
					TimeElapsed = TimeElapsed + 1
					wait(1)
				end
				end)
				coroutine.resume(timer)
	
				AREATOCHECK = "Mystic Mine"
				function add_suffix(inte)
					local gems = inte
					local gems_formatted
	
					if gems >= 1000000000000 then  -- if gems are greater than or equal to 1 trillion
					gems_formatted = string.format("%.1ft", gems / 1000000000000)  -- display gems in trillions with one decimal point
				elseif gems >= 1000000000 then  -- if gems are greater than or equal to 1 billion
					gems_formatted = string.format("%.1fb", gems / 1000000000)  -- display gems in billions with one decimal point
				elseif gems >= 1000000 then  -- if gems are greater than or equal to 1 million
					gems_formatted = string.format("%.1fm", gems / 1000000)  -- display gems in millions with one decimal point
				elseif gems >= 1000 then  -- if gems are greater than or equal to 1 thousand
					gems_formatted = string.format("%.1fk", gems / 1000)  -- display gems in thousands with one decimal point
				else  -- if gems are less than 1 thousand
					gems_formatted = tostring(gems)  -- display gems as is
				end
	
					return gems_formatted
				end
				HttpService = game:GetService("HttpService")
				function WH()
					request({
						Url = WEBHOOK,
						Method = "POST",
						Headers = {
							["Content-Type"] = "application/json"
						},
						Body = HttpService:JSONEncode{
							["content"] = "",
							["embeds"] = {
								{
									["title"] = "Server Hop Stat Update",
									["description"] = "Successfully Broke Everything In Server. Hopping To New Server!",
									["color"] = 5814783,
									["fields"] = {
										{
											["name"] = "Stats",
											["value"] = ":clock1: **Time Taken:** ``"..TimeElapsed.."s``\n:gem: **Gems Earned:** ``"..add_suffix(GemsEarned).."``\n:map: **Farming:** ``"..AREATOCHECK.."``"
										}
									},
									["author"] = {
										["name"] = "Mystic Farmer - Stats"
									}
								}
							}
						}
					})
				end
	
				function GetMulti(B)
					if not B then return 0 end
					local totalMultiplier = 0    
					if B.l then
					for _, v in pairs(B.l) do
						pcall(function() 
							if v.m and tonumber(v.m) then
								totalMultiplier = totalMultiplier + v.m
							end
						end)
					end
	
				end
					return totalMultiplier
				end
	
	
				AllC = Invoke("Get Coins")
				AllNeededCoins = {}
				for i, v in pairs(AllC) do
				if v.a == "Mystic Mine" then
					M = GetMulti(v.b)
					if breakgiantchest then
						if string.find(v.n, "Giant") then
							AllNeededCoins[i] = v
						end
					end
					if breakbigchests then
						if string.find(tostring(v.mh), "320") then
							AllNeededCoins[i] = v
						end
					end
					if M >= targetmulti then
						AllNeededCoins[i] = v
					end
				end
			end
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(9043.19141, -14.3321552, 2424.63647, -0.938255966, 7.68024719e-08, 0.345941782, 8.24376656e-08, 1, 1.57588176e-09, -0.345941782, 2.99972136e-08, -0.938255966)
				Fire("Performed Teleport")
				wait(0.5)
				PETS = Lib.Save.Get().PetsEquipped
				newP = {}
				for i,v in pairs(PETS) do table.insert(newP, i) end
				function ForeverPickupOrbs()
					while true do
					orbs = {}
					for i, v in pairs (game.Workspace['__THINGS'].Orbs:GetChildren()) do
						table.insert(orbs, v.Name)
					end
					Fire("Claim Orbs", orbs)
					wait(0.1)
					for i, v in pairs(game.Workspace['__THINGS'].Lootbags:GetChildren()) do
						Fire("Collect Lootbag", v.Name, v.Position)
					end
				end
				end
				c1 = coroutine.create(ForeverPickupOrbs)
				coroutine.resume(c1)
				for i, v in pairs(AllNeededCoins) do
				local v86 = Invoke("Join Coin", i, newP)
				for v88, v89 in pairs(v86) do
					Fire("Farm Coin", i, v88);
				end
				while 1 do
					wait(0.1)
					AllC = Invoke("Get Coins")
					f = false
					for i2,v2 in pairs(AllC) do
						if i2 == i then f = true end
					end
					if not f then break end
				end
			end
				wait(5)
				local EndingGems = Library.Save.Get().Diamonds
				GemsEarned = EndingGems - StartingGems
				WH()
				wait(1)
				writefile("HOP.txt", "a")
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
	
				while wait() do
				pcall(function()
					TPReturner()
					if foundAnything ~= "" then
						TPReturner()
					end
				end)
			end
			end)
		end)
	
end
coroutine.wrap(VGJHXSA_fake_script)()
local function VFWJ_fake_script() -- Main.Fadeinscript 
	local script = Instance.new('Script', Main)

	local frame = script.Parent -- Replace 'script.Parent' with the path to your frame
	local tweenService = game:GetService("TweenService")
	
	-- Set the frame's initial transparency
	frame.BackgroundTransparency = 1
	
	-- Define the fade-in duration (in seconds)
	local fadeInDuration = 1.5
	
	-- Create a tween for the fade-in animation
	local fadeInTween = tweenService:Create(frame, TweenInfo.new(fadeInDuration, Enum.EasingStyle.Quad, Enum.EasingDirection.In), {BackgroundTransparency = 0})
	
	-- Start the fade-in animation
	fadeInTween:Play()
	
end
coroutine.wrap(VFWJ_fake_script)()
local function EHKBTVA_fake_script() -- LoadingScreen.Script 
	local script = Instance.new('Script', LoadingScreen)

	local loadingscreen = script.Parent
	local maingui = script.Parent.Parent.Main
	
	if loadingscreen.Visible == true then
		wait(3.5)
		maingui.Visible = true
		wait()
		loadingscreen.Visible = false
	end
	
end
coroutine.wrap(EHKBTVA_fake_script)()
local function UJNB_fake_script() -- LoadingScreen.Fadeinscript 
	local script = Instance.new('Script', LoadingScreen)

	local frame = script.Parent -- Replace 'script.Parent' with the path to your frame
	local tweenService = game:GetService("TweenService")
	
	-- Set the frame's initial transparency
	frame.BackgroundTransparency = 1
	
	-- Define the fade-in duration (in seconds)
	local fadeInDuration = 1.5
	
	-- Create a tween for the fade-in animation
	local fadeInTween = tweenService:Create(frame, TweenInfo.new(fadeInDuration, Enum.EasingStyle.Quad, Enum.EasingDirection.In), {BackgroundTransparency = 0})
	
	-- Start the fade-in animation
	fadeInTween:Play()
	
end
coroutine.wrap(UJNB_fake_script)()
