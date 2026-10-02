# oth.get_root_callback

Returns the original callback behind the current hook.

```lua
oth.get_root_callback(): function?
```

## Returns

| Type | Description |
| --- | --- |
| `function?` | The original function, or `nil` outside a hook. |

## Example

```lua
local root = oth.get_root_callback()
if root then
    print(root)
end
```
