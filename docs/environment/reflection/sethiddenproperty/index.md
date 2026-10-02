# sethiddenproperty

Writes a hidden or internal property.

```lua
sethiddenproperty(instance: Instance, property: string, value: any): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to modify. |
| `property` | `string` | Property name. |
| `value` | `any` | The new value. |

## Example

```lua
sethiddenproperty(workspace, "SignalBehavior", 1)
```
