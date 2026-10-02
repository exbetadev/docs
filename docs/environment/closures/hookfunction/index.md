# hookfunction

Replaces a function with your own and returns the original.

```lua
hookfunction(target: function, hook: function): function
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `function` | The function to replace. |
| `hook` | `function` | The replacement function. |

## Returns

| Type | Description |
| --- | --- |
| `function` | The original function, so you can still call it. |

## Aliases

- `hookfunc`
- `replaceclosure`

## Example

```lua
local old
old = hookfunction(print, function(...)
    old("[HOOKED]", ...)
end)

print("test") -- [HOOKED] test
```
