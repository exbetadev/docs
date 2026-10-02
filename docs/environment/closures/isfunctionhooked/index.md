# isfunctionhooked

Checks whether a function is currently hooked.

```lua
isfunctionhooked(fn: function): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the function is hooked. |

## Example

```lua
print(isfunctionhooked(print)) -- false
hookfunction(print, function() end)
print(isfunctionhooked(print)) -- true
```
