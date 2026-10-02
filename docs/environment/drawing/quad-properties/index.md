# Quad properties

Properties for Quad drawings.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Visible` | `boolean` | Whether the quad is shown. |
| `Color` | `Color3` | Fill or outline color. |
| `Thickness` | `number` | Outline width when not filled. |
| `Transparency` | `number` | Opacity. |
| `Filled` | `boolean` | `true` for filled, `false` for outline. |
| `PointA` | `Vector2` | First corner. |
| `PointB` | `Vector2` | Second corner. |
| `PointC` | `Vector2` | Third corner. |
| `PointD` | `Vector2` | Fourth corner. |
| `ZIndex` | `number` | Rendering layer. |

## Example

```lua
local quad = Drawing.new("Quad")
quad.PointA = Vector2.new(100, 100)
quad.PointB = Vector2.new(200, 100)
quad.PointC = Vector2.new(200, 200)
quad.PointD = Vector2.new(100, 200)
quad.Color = Color3.new(1, 0, 1)
quad.Filled = true
quad.Visible = true
```
