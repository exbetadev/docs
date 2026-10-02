# setcallbackvalue

Writes a callback property.

```lua
setcallbackvalue(instance: Instance, property: string, fn: function): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to modify. |
| `property` | `string` | Callback property name. |
| `fn` | `function` | The new callback. |

## Example

```lua
setcallbackvalue(bindable, "OnInvoke", function() return 1 end)
```
