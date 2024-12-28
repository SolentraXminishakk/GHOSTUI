-- Gui to Lua
-- Version: 3.2

-- Instances:

local GHOST = Instance.new("ScreenGui")
local GHOSTGUI = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local _120FOV = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local _100FOV = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local _80FOV = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local _20FOV = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local DefaultFOV = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local _60FOV = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local _40FOV = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local FOVSection = Instance.new("TextLabel")
local Optimization = Instance.new("TextLabel")
local MotionBlur = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local OptimizedRender = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local BetterFPS = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local OptimizedPing = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local GHOSTUI = Instance.new("TextLabel")

--Properties:

GHOST.Name = "GHOST"
GHOST.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
GHOST.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

GHOSTGUI.Name = "GHOSTGUI"
GHOSTGUI.Parent = GHOST
GHOSTGUI.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
GHOSTGUI.BorderColor3 = Color3.fromRGB(0, 0, 0)
GHOSTGUI.BorderSizePixel = 0
GHOSTGUI.Position = UDim2.new(0.341772139, 0, 0.316239327, 0)
GHOSTGUI.Size = UDim2.new(0, 629, 0, 424)

UICorner.Parent = GHOSTGUI

_120FOV.Name = "120FOV"
_120FOV.Parent = GHOSTGUI
_120FOV.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
_120FOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
_120FOV.BorderSizePixel = 0
_120FOV.Position = UDim2.new(0.0317083932, 0, 0.881626368, 0)
_120FOV.Size = UDim2.new(0, 168, 0, 40)
_120FOV.Font = Enum.Font.SourceSans
_120FOV.Text = "120 FOV"
_120FOV.TextColor3 = Color3.fromRGB(255, 255, 255)
_120FOV.TextSize = 14.000

UICorner_2.Parent = _120FOV

_100FOV.Name = "100FOV"
_100FOV.Parent = GHOSTGUI
_100FOV.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
_100FOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
_100FOV.BorderSizePixel = 0
_100FOV.Position = UDim2.new(0.0317083932, 0, 0.766060293, 0)
_100FOV.Size = UDim2.new(0, 168, 0, 40)
_100FOV.Font = Enum.Font.SourceSans
_100FOV.Text = "100 FOV"
_100FOV.TextColor3 = Color3.fromRGB(255, 255, 255)
_100FOV.TextSize = 14.000

UICorner_3.Parent = _100FOV

_80FOV.Name = "80FOV"
_80FOV.Parent = GHOSTGUI
_80FOV.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
_80FOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
_80FOV.BorderSizePixel = 0
_80FOV.Position = UDim2.new(0.0317083932, 0, 0.652852774, 0)
_80FOV.Size = UDim2.new(0, 168, 0, 40)
_80FOV.Font = Enum.Font.SourceSans
_80FOV.Text = "80 FOV"
_80FOV.TextColor3 = Color3.fromRGB(255, 255, 255)
_80FOV.TextSize = 14.000

UICorner_4.Parent = _80FOV

_20FOV.Name = "20FOV"
_20FOV.Parent = GHOSTGUI
_20FOV.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
_20FOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
_20FOV.BorderSizePixel = 0
_20FOV.Position = UDim2.new(0.0317083932, 0, 0.322664082, 0)
_20FOV.Size = UDim2.new(0, 168, 0, 40)
_20FOV.Font = Enum.Font.SourceSans
_20FOV.Text = "20 FOV"
_20FOV.TextColor3 = Color3.fromRGB(255, 255, 255)
_20FOV.TextSize = 14.000

UICorner_5.Parent = _20FOV

DefaultFOV.Name = "DefaultFOV"
DefaultFOV.Parent = GHOSTGUI
DefaultFOV.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
DefaultFOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
DefaultFOV.BorderSizePixel = 0
DefaultFOV.Position = UDim2.new(0.0317083932, 0, 0.209456533, 0)
DefaultFOV.Size = UDim2.new(0, 168, 0, 40)
DefaultFOV.Font = Enum.Font.SourceSans
DefaultFOV.Text = "RESET FOV"
DefaultFOV.TextColor3 = Color3.fromRGB(255, 255, 255)
DefaultFOV.TextSize = 14.000

UICorner_6.Parent = DefaultFOV

_60FOV.Name = "60FOV"
_60FOV.Parent = GHOSTGUI
_60FOV.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
_60FOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
_60FOV.BorderSizePixel = 0
_60FOV.Position = UDim2.new(0.0317083932, 0, 0.544362187, 0)
_60FOV.Size = UDim2.new(0, 168, 0, 40)
_60FOV.Font = Enum.Font.SourceSans
_60FOV.Text = "60 FOV"
_60FOV.TextColor3 = Color3.fromRGB(255, 255, 255)
_60FOV.TextSize = 14.000

UICorner_7.Parent = _60FOV

_40FOV.Name = "40FOV"
_40FOV.Parent = GHOSTGUI
_40FOV.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
_40FOV.BorderColor3 = Color3.fromRGB(0, 0, 0)
_40FOV.BorderSizePixel = 0
_40FOV.Position = UDim2.new(0.0317083932, 0, 0.435871631, 0)
_40FOV.Size = UDim2.new(0, 168, 0, 40)
_40FOV.Font = Enum.Font.SourceSans
_40FOV.Text = "40 FOV"
_40FOV.TextColor3 = Color3.fromRGB(255, 255, 255)
_40FOV.TextSize = 14.000

UICorner_8.Parent = _40FOV

FOVSection.Name = "FOV Section"
FOVSection.Parent = GHOSTGUI
FOVSection.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
FOVSection.BorderColor3 = Color3.fromRGB(0, 0, 0)
FOVSection.BorderSizePixel = 0
FOVSection.Position = UDim2.new(0.0302066766, 0, 0.101415098, 0)
FOVSection.Size = UDim2.new(0, 168, 0, 32)
FOVSection.Font = Enum.Font.SourceSans
FOVSection.Text = "Fov"
FOVSection.TextColor3 = Color3.fromRGB(255, 255, 255)
FOVSection.TextSize = 26.000

Optimization.Name = "Optimization"
Optimization.Parent = GHOSTGUI
Optimization.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Optimization.BorderColor3 = Color3.fromRGB(0, 0, 0)
Optimization.BorderSizePixel = 0
Optimization.Position = UDim2.new(0.682034969, 0, 0.101415098, 0)
Optimization.Size = UDim2.new(0, 168, 0, 32)
Optimization.Font = Enum.Font.SourceSans
Optimization.Text = "Optimization"
Optimization.TextColor3 = Color3.fromRGB(255, 255, 255)
Optimization.TextSize = 26.000

MotionBlur.Name = "MotionBlur"
MotionBlur.Parent = GHOSTGUI
MotionBlur.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
MotionBlur.BorderColor3 = Color3.fromRGB(0, 0, 0)
MotionBlur.BorderSizePixel = 0
MotionBlur.Position = UDim2.new(0.672407925, 0, 0.209456533, 0)
MotionBlur.Size = UDim2.new(0, 168, 0, 40)
MotionBlur.Font = Enum.Font.SourceSans
MotionBlur.Text = "Motion Blur"
MotionBlur.TextColor3 = Color3.fromRGB(255, 255, 255)
MotionBlur.TextSize = 14.000

UICorner_9.Parent = MotionBlur

OptimizedRender.Name = "OptimizedRender"
OptimizedRender.Parent = GHOSTGUI
OptimizedRender.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
OptimizedRender.BorderColor3 = Color3.fromRGB(0, 0, 0)
OptimizedRender.BorderSizePixel = 0
OptimizedRender.Position = UDim2.new(0.672407925, 0, 0.322664082, 0)
OptimizedRender.Size = UDim2.new(0, 168, 0, 40)
OptimizedRender.Font = Enum.Font.SourceSans
OptimizedRender.Text = "Optimized Render"
OptimizedRender.TextColor3 = Color3.fromRGB(255, 255, 255)
OptimizedRender.TextSize = 14.000

UICorner_10.Parent = OptimizedRender

BetterFPS.Name = "BetterFPS"
BetterFPS.Parent = GHOSTGUI
BetterFPS.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
BetterFPS.BorderColor3 = Color3.fromRGB(0, 0, 0)
BetterFPS.BorderSizePixel = 0
BetterFPS.Position = UDim2.new(0.672407925, 0, 0.435871631, 0)
BetterFPS.Size = UDim2.new(0, 168, 0, 40)
BetterFPS.Font = Enum.Font.SourceSans
BetterFPS.Text = "BetterFPS"
BetterFPS.TextColor3 = Color3.fromRGB(255, 255, 255)
BetterFPS.TextSize = 14.000

UICorner_11.Parent = BetterFPS

OptimizedPing.Name = "Optimized Ping"
OptimizedPing.Parent = GHOSTGUI
OptimizedPing.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
OptimizedPing.BorderColor3 = Color3.fromRGB(0, 0, 0)
OptimizedPing.BorderSizePixel = 0
OptimizedPing.Position = UDim2.new(0.672407925, 0, 0.544362187, 0)
OptimizedPing.Size = UDim2.new(0, 168, 0, 40)
OptimizedPing.Font = Enum.Font.SourceSans
OptimizedPing.Text = "Optimized Ping"
OptimizedPing.TextColor3 = Color3.fromRGB(255, 255, 255)
OptimizedPing.TextSize = 14.000

UICorner_12.Parent = OptimizedPing

GHOSTUI.Name = "GHOSTUI"
GHOSTUI.Parent = GHOSTGUI
GHOSTUI.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
GHOSTUI.BorderColor3 = Color3.fromRGB(0, 0, 0)
GHOSTUI.BorderSizePixel = 0
GHOSTUI.Position = UDim2.new(0.379968196, 0, 0.047169812, 0)
GHOSTUI.Size = UDim2.new(0, 150, 0, 32)
GHOSTUI.Font = Enum.Font.Unknown
GHOSTUI.Text = "GHOSTUI"
GHOSTUI.TextColor3 = Color3.fromRGB(255, 255, 255)
GHOSTUI.TextSize = 40.000

-- Scripts:

local function JSEPWXJ_fake_script() -- _120FOV.120Fov 
	local script = Instance.new('LocalScript', _120FOV)

	local camera = workspace.CurrentCamera
	local button = script.Parent
	local applied = false
	
	button.MouseButton1Click:Connect(function()
		if not applied then
			camera.FieldOfView = 120
			applied = true
		end
	end)
end
coroutine.wrap(JSEPWXJ_fake_script)()
local function LJAG_fake_script() -- _100FOV.100FOV 
	local script = Instance.new('LocalScript', _100FOV)

	local camera = workspace.CurrentCamera
	local button = script.Parent
	local applied = false
	
	button.MouseButton1Click:Connect(function()
		if not applied then
			camera.FieldOfView = 100
			applied = true
		end
	end)
end
coroutine.wrap(LJAG_fake_script)()
local function LOBX_fake_script() -- _80FOV.80fov 
	local script = Instance.new('LocalScript', _80FOV)

	local camera = workspace.CurrentCamera
	local button = script.Parent
	local applied = false
	
	button.MouseButton1Click:Connect(function()
		if not applied then
			camera.FieldOfView = 80
			applied = true
		end
	end)
end
coroutine.wrap(LOBX_fake_script)()
local function QGWJB_fake_script() -- _20FOV.20fov 
	local script = Instance.new('LocalScript', _20FOV)

	local camera = workspace.CurrentCamera
	local button = script.Parent
	local applied = false
	
	button.MouseButton1Click:Connect(function()
		if not applied then
			camera.FieldOfView = 20
			applied = true
		end
	end)
end
coroutine.wrap(QGWJB_fake_script)()
local function FTMXB_fake_script() -- DefaultFOV.resetfov 
	local script = Instance.new('LocalScript', DefaultFOV)

	local camera = workspace.CurrentCamera
	local button = script.Parent
	local applied = false
	
	button.MouseButton1Click:Connect(function()
		if not applied then
			camera.FieldOfView = 70
			applied = true
		end
	end)
end
coroutine.wrap(FTMXB_fake_script)()
local function SBUSVD_fake_script() -- _60FOV.60fov 
	local script = Instance.new('LocalScript', _60FOV)

	local camera = workspace.CurrentCamera
	local button = script.Parent
	local applied = false
	
	button.MouseButton1Click:Connect(function()
		if not applied then
			camera.FieldOfView = 60
			applied = true
		end
	end)
end
coroutine.wrap(SBUSVD_fake_script)()
local function MQSE_fake_script() -- _40FOV.40FOV 
	local script = Instance.new('LocalScript', _40FOV)

	local camera = workspace.CurrentCamera
	local button = script.Parent
	local applied = false
	
	button.MouseButton1Click:Connect(function()
		if not applied then
			camera.FieldOfView = 40
			applied = true
		end
	end)
end
coroutine.wrap(MQSE_fake_script)()
local function PAHPB_fake_script() -- GHOSTGUI.Draggable 
	local script = Instance.new('LocalScript', GHOSTGUI)

	local GUI = script.Parent
	local UserInputService = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local dragging = false
	local dragStart = Vector2.new(0, 0)
	local dragOffset = Vector2.new(0, 0)
	
	GUI.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			dragStart = Vector2.new(input.Position.X, input.Position.Y)
			dragOffset = Vector2.new(GUI.Position.X.Offset, GUI.Position.Y.Offset)
		end
	end)
	
	GUI.InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = false
		end
	end)
	
	RunService.RenderStepped:Connect(function()
		if dragging then
			local mousePosition = Vector2.new(UserInputService:GetMouseLocation().X, UserInputService:GetMouseLocation().Y)
			local newPosition = Vector2.new(mousePosition.X - (dragStart.X - dragOffset.X), mousePosition.Y - (dragStart.Y - dragOffset.Y))
			GUI.Position = UDim2.new(0, newPosition.X, 0, newPosition.Y)
		end
	end)
end
coroutine.wrap(PAHPB_fake_script)()
local function ERPLNM_fake_script() -- GHOSTGUI.ALThide 
	local script = Instance.new('LocalScript', GHOSTGUI)

	local GUI = script.Parent
	local UserInputService = game:GetService("UserInputService")
	
	UserInputService.InputBegan:Connect(function(input)
		if input.KeyCode == Enum.KeyCode.LeftAlt then
			if GUI.Visible then
				GUI.Visible = false
			else
				GUI.Visible = true
			end
		end
	end)
end
coroutine.wrap(ERPLNM_fake_script)()
