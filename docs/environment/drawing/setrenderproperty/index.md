# setrenderproperty

Writes a drawing property.

```lua
setrenderproperty(drawing: DrawingObject, property: string, value: any): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `drawing` | `DrawingObject` | The drawing to modify. |
| `property` | `string` | Property name. |
| `value` | `any` | The new value. |

## Example

```lua
setrenderproperty(line, "Color", Color3.new(1, 0, 0))
```
