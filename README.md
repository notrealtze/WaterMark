# WaterMark

```lua
local Watermark = loadstring(game:HttpGet("https://raw.githubusercontent.com/notrealtze/WaterMark/refs/heads/main/WaterMark%20source"))()
```

---

## Usage

```lua
Watermark:init() -- to start up watermark
```

---

```lua
Watermark:SetText(Test, 38384583854) -- First parm is text, second parm is the image you want as an image icon next to the text
```

---

```lua
Watermark:Position(0, 356, 1, -36) -- it accepts that only
```

---

```lua
Watermark:Size(0, 134, 0, 16) -- size
```

---

```lua
Watermark:AnchorPoint(0, 1) -- anchor point
```

---

```lua
Watermark:Forever(true) -- Reset spawn is false if true
```

---

```lua
Watermark:HideGui(true) -- will use syn protect gui if fails then it makes a folder in coregui then scrambles the name to unsupported and for Roblox and puts the name in there (apply it to GUI and every element in there)
```

---

```lua
Watermark:Transparency(0.5) -- Self explaintory
```

---

```lua
Watermark:UIStrokeTransparency(0.2) -- Again self-explanatory
```

---

```lua
Watermark:Thickness(1) -- UI stroke thickness
```

---

## Full Example

```lua
local Watermark = loadstring(game:HttpGet("https://raw.githubusercontent.com/notrealtze/WaterMark/refs/heads/main/WaterMark%20source"))()

Watermark:init() -- to start up watermark
Watermark:SetText(Test, 38384583854) -- First parm is text, second parm is the image you want as an image icon next to the text
Watermark:Position(0, 356, 1, -36) -- it accepts that only
Watermark:Size(0, 134, 0, 16) -- size
Watermark:AnchorPoint(0, 1) -- anchor point
Watermark:Forever(true) -- Reset spawn is false if true
Watermark:HideGui(true) -- will use syn protect gui if fails then it makes a folder in coregui then scrambles the name to unsupported and for Roblox and puts the name in there (apply it to GUI and every element in there)
Watermark:Transparency(0.5) -- Self explaintory
Watermark:UIStrokeTransparency(0.2) -- Again self-explanatory
Watermark:Thickness(1) -- UI stroke thickness
```
