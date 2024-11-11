|local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "P9 HUB ENJOY!", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "SCRIPT EXECUTION",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "p9 loading"
})

OrionLib:MakeNotification({
	Name = "LOADED!",
	Content = "Notification content... what will it say??",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddButton({
	Name = "LOAD SCRIPT!",
	Callback = function(loadstring(game:HttpGet("https://raw.githubusercontent.com/PantherScriptzzz/P9-HUB/refs/heads/main/P9HUB.lua"))())
      		print("SCRIPT LOADED")
  	end    
})

Tab:AddBind({
	Name = "Right Control",
	Default = Enum.KeyCode.E,
	Hold = false,
	Callback = function()
		print("Closed UI!")
	end    
})

OrionLib:Init()
