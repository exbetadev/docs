# Circle properties

Properties for Circle drawings.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Visible` | `boolean` | Whether the circle is shown. |
| `Color` | `Color3` | Fill or outline color. |
| `Thickness` | `number` | Outline width in pixels when not filled. |
| `Transparency` | `number` | Opacity. |
| `NumSides` | `number` | Polygon approximation quality, higher is rounder. |
| `Radius` | `number` | Circle radius in pixels. |
| `Filled` | `boolean` | `true` for filled, `false` for outline. |
| `Position` | `Vector2` | Circle center. |
| `ZIndex` | `number` | Rendering layer. |

## Example

```lua
local circle = Drawing.new("Circle")
circle.Position = Vector2.new(400, 300)
circle.Radius = 50
circle.Filled = true
circle.Color = Color3.new(0, 1, 0)
circle.Visible = true
```
