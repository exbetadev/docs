# oth.get_hook

Returns the replacement function attached to a hook.

```lua
oth.get_hook(fn: function): function?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The hooked function. |

## Returns

| Type | Description |
| --- | --- |
| `function?` | The hook function, or `nil`. |

## Example

```lua
local hook = oth.get_hook(old)
print(hook)
```
