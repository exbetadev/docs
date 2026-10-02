# gethiddenproperty

Reads a hidden or internal property.

```lua
gethiddenproperty(instance: Instance, property: string): any
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to read. |
| `property` | `string` | Property name. |

## Returns

| Type | Description |
| --- | --- |
| `any` | The property value. |

## Example

```lua
local value = gethiddenproperty(workspace, "SignalBehavior")
print(value)
```
