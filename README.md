# Exi-Trash

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Exi Hub", "DarkTheme")

local Tab = Window:NewTab("Auto Fram")
local Section = Tab:NewSection("Auto Fram")

Section:NewToggle("ลองเองExiHub "ลองเองExiHub.Info"
    if state then
        print("Toggle On")
    else
        print("Toggle Off")
    end
end)

local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("Teleport")

Section:NewButton(ใช้ยังไม่ได้ExiHub", "ใช้ยังไม่ได้ExiHub.Info", function()
    print("Clicked")
end)
