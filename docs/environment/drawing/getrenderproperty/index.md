# getrenderproperty

Reads a drawing property.

```lua
getrenderproperty(drawing: DrawingObject, property: string): any
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `drawing` | `DrawingObject` | The drawing to inspect. |
| `property` | `string` | Property name. |

## Returns

| Type | Description |
| --- | --- |
| `any` | The property value. |

## Example

```lua
print(getrenderproperty(line, "Visible"))
```
