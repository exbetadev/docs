# getrenv

Returns the global environment of the Roblox state.

```lua
getrenv(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Roblox global environment. |

## Example

```lua
local env = getrenv()
print(type(env))
```
