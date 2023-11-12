# PabloLibV3Tutorial
# PabloLibV3Tutorial
<[[UPDATE LOGS]]>
------------------------------
2. added delete tab and 2 more things(look on extras)

-------------------------
Hello! In this tutorial I will show how to use the "Pablo Lib V3"!

Let's start!

### 1. To create the lib use this code:
```lua
local PabloLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/BatuKvi123/PabloLibV3/main/PabloLibV3"))()
```

###  2. To get the lib use this code:
```lua
local window = PabloLib:Create(
"Name", -- Name here.
"Enabled", -- If you want draggable set here to "Enabled" if you dont want set to "Disabled".
"p" -- You can put any keybind here to open close.
)
```

### 3 . To create a tab use this following code:
```lua
local tab1 = window:CreateTab("Tab1")
```
### 4. To create a button use this following code:
```lua
tab1:CreateButton("Button", function()
print("Hello World")
end)
```

### 5. To create a toggle use this following code:
```lua
tab1:CreateToggle("Toggle", function(state)
if state then
print("Enabled!")
else
print("Disabled!")
end)
```

### 6. To create a slider use this following code:
```lua
tab1:CreateSlider("Slider", 0, 100, function(arg)
print(arg)
end)
```

### 7. To create a textbox use this following code:
```lua
tab1:CreateTextbox("Textbox", function(a)
print(a)
end)
```

### 8. To create a label use this following code:
```lua
tab1:CreateLabel("Label")
```

### 9. To create an Info use this following code:
```lua
tab1:CreateInfo("Info")
```

### 10. To create an Warning use this following code:
```lua
tab1:CreateWarning("Warning")
```




# EXTRAS
### Extra 1. Deleting an any tab element(button, slider, textbox, Toggle, label, info, warning)
```lua
local button = tab1:CreateButton("Print hi", function()
print("hi")
end)

tab1:CreateButton("Delete print hi button", function()
button:Delete()
end)
```
### NOTE: THIS IS NOT ONLY WORKS ON BUTTON THIS IS WORKING ON BUTTON, TOGGLE, SLIDER, TEXTBOX, LABEL, INFO, WARNING!

### Extra 2. Deleting a Tab
```lua
local tab1 = window:CreateTab("Tab")
tab1:CreateButton("Destroy this tab", function()
tab1:DeleteTab()
end)
```

### NOTE: THIS IS WORKS ON ANY TAB!

### Extra 3. Closing the Pablo Lib
```lua
tab1:CreateButton("Destroy Pablo Lib", function()
PabloLib:Close()
end)
```

Thats all for now! I hope yall like the new updates and new ui!
Have a good day! :)
