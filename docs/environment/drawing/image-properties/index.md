# Image properties

Properties for Image drawings.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Visible` | `boolean` | Whether the image is shown. |
| `Data` | `string` | Image file data (PNG, JPEG). |
| `Size` | `Vector2` | Image dimensions. |
| `Position` | `Vector2` | Top-left corner. |
| `Rounding` | `number` | Corner rounding radius in pixels. |
| `Transparency` | `number` | Opacity. |
| `ZIndex` | `number` | Rendering layer. |

## Example

```lua
local image = Drawing.new("Image")
image.Data = readfile("icon.png")
image.Position = Vector2.new(10, 10)
image.Size = Vector2.new(64, 64)
image.Visible = true
```
