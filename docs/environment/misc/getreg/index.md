# getreg

Returns the Lua registry table.

```lua
getreg(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | The registry. |

## Example

```lua
local registry = getreg()
print(type(registry))
```
