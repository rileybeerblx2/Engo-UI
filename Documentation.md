# Engo UI
This documentation is for Engo UI Credit To The Owner

## Booting the Engo UI Library
```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/joeengo/exploiting/main/EngoUILIB_V2.lua", true))()
```




## Creating a Engo UI Window
```lua
local main = library:CreateMain("Yes", "", Enum.KeyCode.LeftAlt)
```

## Creating a Tab
```lua
local tab = main:CreateTab("Yes TAB")
```

## Creating a Label
```lua
tab:CreateLabel("Main")
```

## Creating a Toggle
```lua
tab:CreateToggle("Toggle", function(value)
   
end);
```
