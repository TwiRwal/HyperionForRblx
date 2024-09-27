# Hyperion Ui Library
## Example
#### Classic CSGO Hyperion Cheat Gui By NoHyper

## Gui Library
```lua
local NoHyper = loadstring(game:HttpGet("https://raw.githubusercontent.com/TwiRwal/HyperionForRblx/main/HyperionUiLibrary"))()
```
## Notify + Gui Opening Timer
```lua
local Notify = NoHyper:MakeNotify({
        Title = "Example", -- Write Your Title OFC
        Text = "This Is Example of Notify", -- Write Description Of Title
        Time = 5 -- Write Time Till Notify Gui Gone
      })
Wait() -- Choose Time for Gui Open Or You Can Remove It
```
## Themes
```lua
NoHyper.set_theme('nohyper') -- Yes You Can Rename It BecuzIts Not My GUI -- Theme Are | nohyper , bedol , neverlose, green
```
## Window
```lua
local Window = NoHyper.new('Hello, '..game.Players.LocalPlayer.DisplayName,"rbxassetid://128467316314125",'Welcome back!') -- My Logo you can replace it
Window:NewSize(UDim2.new(0.1,430,0.1,300))
```
## Share Websites
```lua
Window:AddYoutube('https://www.youtube.com/your-youtube-channel')
Window:AddWebsite('https://example.com/your-website')
Window:AddDiscord('https://discord.gg/your-discord')
```
## Tabs
```lua
local General = Window:NewTab('General','earth') -- Icon: ads list folder earth locked home positon notify close color
local Setting = Window:NewTab('Setting','list')
```
## Sections
```lua
local Example = General:NewSection('Example','positon','left') -- [left , right]
local RightSection = General:NewSection('Section','ads','right')
local SettingSection = Setting:NewSection('Settings','crown','left')
```
## Toggle
```lua
SettingSection:AddToggle('Auto Save',false,function()
	print('auto save')
end)
```
## Button
```lua
Example:AddButton('Example',function()
	print('click!')
end)
```
## KeyBind
```lua
Example:AddKeybind('Keybind',Enum.KeyCode.E,function(value)
	print('bind!')
end)
```
## Silder
```lua
Example:AddSlider('Keybind',{Min = 0,Max = 100,Default = 50,ValueT = '%'},function(value)
	print('number is ')
end)
```
## Dropdown
```lua
Example:AddDropdown('Dropdown',{1,2,3,4,5,6,7,8,9,10},5,function(value)
	print('select')
end)
```
## Credits
```
Hyperion Made By NoHyper For CsGo And We Are Make Roblox Version Of It
Made By TwiRwal
Gui By Catsus
```
