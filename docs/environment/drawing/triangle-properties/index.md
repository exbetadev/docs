# Triangle properties

Properties for Triangle drawings.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Visible` | `boolean` | Whether the triangle is shown. |
| `Color` | `Color3` | Fill or outline color. |
| `Thickness` | `number` | Outline width when not filled. |
| `Transparency` | `number` | Opacity. |
| `Filled` | `boolean` | `true` for filled, `false` for outline. |
| `PointA` | `Vector2` | First vertex. |
| `PointB` | `Vector2` | Second vertex. |
| `PointC` | `Vector2` | Third vertex. |
| `ZIndex` | `number` | Rendering layer. |

## Example

```lua
local triangle = Drawing.new("Triangle")
triangle.PointA = Vector2.new(300, 100)
triangle.PointB = Vector2.new(250, 200)
triangle.PointC = Vector2.new(350, 200)
triangle.Color = Color3.new(1, 1, 0)
triangle.Filled = true
triangle.Visible = true
```
