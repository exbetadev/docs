# Line properties

Properties for Line drawings.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Visible` | `boolean` | Whether the line is shown. |
| `Color` | `Color3` | Line color. |
| `Thickness` | `number` | Line width in pixels. |
| `Transparency` | `number` | Opacity, `0` is opaque, `1` is invisible. |
| `From` | `Vector2` | Start point. |
| `To` | `Vector2` | End point. |
| `ZIndex` | `number` | Rendering layer. |

## Example

```lua
line.Thickness = 2
line.Transparency = 0.5
```
