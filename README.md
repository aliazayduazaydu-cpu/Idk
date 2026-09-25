local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("سكربتات مابات", "BloodTheme")

local Tab = Window:NewTab("onوoff")
local Section = Tab:NewSection("افضل هاك")

Section:NewToggle("ToggleText", "ToggleInfo", function(state)
    if state then
        print("Toggle On")
    else
        print("Toggle Off")
    end
end)

local Tab = Window:NewTab("ضغطه وحده")
local Section = Tab:NewSection("افضل هاك")

Section:NewButton("ButtonText", "ButtonInfo", function()
    print("Clicked")
end)
