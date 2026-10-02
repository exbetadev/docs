# oth.is_hook_thread

Checks whether the current context is a hook thread.

```lua
oth.is_hook_thread(): boolean
```

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when running inside a hook. |

## Example

```lua
print(oth.is_hook_thread())
```
