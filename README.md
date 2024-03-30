local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "menu", HidePremium = false, SaveConfig = true, introtext = "menu", ConfigFolder = "menu"})

OrionLib:MakeNotification({
  Name = "hey",
  Content = "enjoy your script",
  Image = "rbxassetid://4483345998",
  Time = 5

local maainTab = Window:MakeTab({
  Name = "menu",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
})

local Section = tutTab:AddSection({
	Name = "menu section
})



    tutTab:AddButton({
      Name = "Button!",
      Callback = function()
              print("Enjoy")
        end    
    })

   tut Tab:AddToggle({
	Name = "god mode toggle!",
	Default = false,
	Callback = function(Value)
		print("enjoy")
	end    
})

tutTab:AddColorpicker({
	Name = "Colorpicker",
	Default = Color3.fromRGB(255, 0, 0),
	Callback = function(Value)
		print(Value)
	end	  
})

tutTab:AddSlider({
      Name = "Slider",
      Min = 0,
      Max = 20,
      Default = 5,
      Color = Color3.fromRGB(255,255,255),
      Increment = 1,
      ValueName = "bananas",
      Callback = function(Value)
        print(Value)
      end    
    })
    
end
OrionLib:Init() 
