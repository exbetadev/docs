# oth.get_original_thread

Returns the thread the hook was called from.

```lua
oth.get_original_thread(): thread?
```

## Returns

| Type | Description |
| --- | --- |
| `thread?` | The original thread, or `nil`. |

## Example

```lua
local thread = oth.get_original_thread()
print(thread)
```
