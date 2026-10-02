# oth.replace_hook

Replaces the hook function without unhooking the target.

```lua
oth.replace_hook(fn: function, hook: function): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The hooked function. |
| `hook` | `function` | The new hook function. |

## Example

```lua
oth.replace_hook(old, function() end)
```
