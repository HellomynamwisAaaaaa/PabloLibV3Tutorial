# PabloLibV3Tutorial
# PabloLibV3Tutorial
<[[UPDATE LOGS]]>
------------------------------
1. added info, warning
<>
2. changed ui look

-------------------------
Hello! In this tutorial I will show how to use the "Pablo Lib V3"!

Let's start!

### 1. To get the lib use this code:
```lua
local PabloLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/BatuKvi123/PabloLibV3/main/PabloLibV3"))()
```

###  2. To create the lib use this code:
```lua
local window = PabloLib:Create("Name")
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

Thats all for now! I hope yall like the new updates and new ui!
Have a good day! :)
