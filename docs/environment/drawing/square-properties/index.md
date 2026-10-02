# Square properties

Properties for Square (rectangle) drawings.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Visible` | `boolean` | Whether the square is shown. |
| `Color` | `Color3` | Fill or outline color. |
| `Thickness` | `number` | Outline width when not filled. |
| `Transparency` | `number` | Opacity. |
| `Filled` | `boolean` | `true` for filled, `false` for outline. |
| `Size` | `Vector2` | Width and height. |
| `Position` | `Vector2` | Top-left corner. |
| `ZIndex` | `number` | Rendering layer. |

## Example

```lua
local square = Drawing.new("Square")
square.Position = Vector2.new(100, 100)
square.Size = Vector2.new(200, 100)
square.Filled = false
square.Thickness = 2
square.Color = Color3.new(1, 1, 1)
square.Visible = true
```
