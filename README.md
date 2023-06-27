# Quick-Roblox-Functions
just a selection of quick and easy functions for me to use

# Create Script with some text
```
local function createScript(text, name)
	name = name or "ModuleScript"
	local m = Instance.new("ModuleScript")
	m.Source = text
	m.Name = name
	m.Parent = workspace
end
```

# Create part at position with color
```
local function createPart(pos, color)
	color = color or BrickColor.new("Medium stone grey").Color
	local p = Instance.new("Part")
	p.CFrame = CFrame.new(pos)
	p.Color = color
	p.Parent = workspace
end
```
