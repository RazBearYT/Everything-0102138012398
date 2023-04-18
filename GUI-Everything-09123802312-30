-- Gui to Lua
-- Version: 3.2

-- Instances:
repeat task.wait() until game:IsLoaded()
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(17, 92, 255)
Frame.BorderSizePixel = 3
Frame.Position = UDim2.new(0.0428100973, 0, 0.127016127, 0)
Frame.Size = UDim2.new(0, 778, 0, 593)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(17, 92, 255)
TextLabel.Size = UDim2.new(0, 777, 0, 90)
TextLabel.Font = Enum.Font.Arial
TextLabel.Text = "Roblox Gui Panel Accesser"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 40.000

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(52, 255, 221)
TextButton.Position = UDim2.new(0, 0, 0.151770651, 0)
TextButton.Size = UDim2.new(0, 140, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "NukeVsCity"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

-- Scripts:

local function VRYU_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	repeat task.wait() until game:IsLoaded() and game.Players.LocalPlayer.Character
	-- Create a ScreenGui object
	local gui = Instance.new("ScreenGui")
	gui.Parent = game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")
	-- Create a Frame object and set its properties
	local frame = Instance.new("Frame")
	frame.Parent = gui
	frame.Size = UDim2.new(0.8, 0, 0.8, 0) -- Change the size to 80% of the screen width and height
	frame.Position = UDim2.new(0.1, 0, 0.1, 0) -- Position the frame 10% from the top and left of the screen
	frame.BackgroundColor3 = Color3.new(0, 0, 0)
	frame.BackgroundTransparency = 0.5
	-- Create a TextLabel object and set its properties
	local textLabel = Instance.new("TextLabel")
	textLabel.Parent = frame
	textLabel.Text = "Credits to the makers of the scripts. I AM NOT RESPONSIBLE IF YOU GET BANNED"
	textLabel.Size = UDim2.new(1, 0, 1, 0)
	textLabel.Position = UDim2.new(0, 0, 0, 0)
	textLabel.TextColor3 = Color3.new(1, 1, 1)
	textLabel.BackgroundTransparency = 1
	textLabel.Font = Enum.Font.SourceSans
	textLabel.TextSize = 24
	-- Create a Tween object to fade out the Frame over 5 seconds
	local tweenFrame = game:GetService("TweenService"):Create(frame, TweenInfo.new(5), {BackgroundTransparency = 1})
	-- Create a Tween object to fade out the TextLabel over 5 seconds
	local tweenText = game:GetService("TweenService"):Create(textLabel, TweenInfo.new(5), {TextTransparency = 1})
	-- Start the Tween animations after a 1 second delay
	wait(1)
	tweenFrame:Play()
	tweenText:Play()
	game:GetService("Chat"):Chat(game.Players.LocalPlayer.Character.Head , "Loading In NukeVsCity Gui" , Enum.ChatColor.White)
	loadstring(game:HttpGet("https://raw.githubusercontent.com/NukeVsCity/TheALLHACKLoader/main/NukeLoader"))()
end
coroutine.wrap(VRYU_fake_script)()
local function SGPTTI_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	-- Create a ScreenGui object to hold the GUI frame
	local gui = Instance.new("ScreenGui")
	gui.Name = "RealTimeGUI"
	gui.ResetOnSpawn = false
	gui.DisplayOrder = 10
	gui.Parent = game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")
	
	-- Create a Frame object to hold the time display
	local frame = Instance.new("Frame")
	frame.Size = UDim2.new(0, 150, 0, 50)
	frame.Position = UDim2.new({0.311, 0},{0.127, 0})
	frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	frame.BorderSizePixel = 2
	frame.Parent = gui
	
	-- Create a TextLabel object to display the time
	local timeLabel = Instance.new("TextLabel")
	timeLabel.Size = UDim2.new(1, 0, 1, 0)
	timeLabel.Font = Enum.Font.SourceSansBold
	timeLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
	timeLabel.TextSize = 24
	timeLabel.Parent = frame
	
	-- Function to update the time display
	local function updateTime()
		local realTime = os.time()
		local dateTable = os.date("*t", realTime)
		local hour = dateTable.hour
		local minute = dateTable.min
		local second = dateTable.sec
		timeLabel.Text = string.format("%02d:%02d:%02d", hour, minute, second)
	end
	
	-- Update the time display every second
	while true do
		updateTime()
		wait(1)
	end
end
coroutine.wrap(SGPTTI_fake_script)()
