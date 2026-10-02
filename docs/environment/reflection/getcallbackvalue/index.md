# getcallbackvalue

Reads a callback property, such as a BindableFunction callback.

```lua
getcallbackvalue(instance: Instance, property: string): function?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to read. |
| `property` | `string` | Callback property name. |

## Returns

| Type | Description |
| --- | --- |
| `function?` | The callback function, or `nil`. |

## Example

```lua
local callback = getcallbackvalue(bindable, "OnInvoke")
```
