# Drawing.new

Creates a new drawing object of the specified type.

```lua
Drawing.new(type: string): DrawingObject
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `type` | `string` | One of `Line`, `Circle`, `Square`, `Quad`, `Triangle`, `Image`, `Text`. |

## Returns

| Type | Description |
| --- | --- |
| `DrawingObject` | The newly created drawing. |

## Example

```lua
local line = Drawing.new("Line")
line.From = Vector2.new(0, 0)
line.To = Vector2.new(100, 100)
line.Color = Color3.new(1, 0, 0)
line.Visible = true
```
