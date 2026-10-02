# Text properties

Properties for Text drawings.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Visible` | `boolean` | Whether the text is shown. |
| `Text` | `string` | The string to render. |
| `Font` | `number` | Font ID from `Drawing.Fonts`. |
| `Size` | `number` | Font size in pixels. |
| `Position` | `Vector2` | Top-left corner of the text. |
| `Color` | `Color3` | Text color. |
| `Transparency` | `number` | Opacity. |
| `Center` | `boolean` | `true` to center the text at Position. |
| `Outline` | `boolean` | `true` to add an outline. |
| `OutlineColor` | `Color3` | Outline color. |
| `ZIndex` | `number` | Rendering layer. |
| `TextBounds` | `Vector2` | Read-only, the measured size of the text. |

## Example

```lua
local text = Drawing.new("Text")
text.Text = "Hello"
text.Font = Drawing.Fonts.UI
text.Size = 18
text.Position = Vector2.new(400, 300)
text.Center = true
text.Color = Color3.new(1, 1, 1)
text.Outline = true
text.Visible = true
```
