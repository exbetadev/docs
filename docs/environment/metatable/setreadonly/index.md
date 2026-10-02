# setreadonly

Sets or clears the read-only flag on a table.

```lua
setreadonly(table: table, readonly: boolean): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `table` | `table` | The table to modify. |
| `readonly` | `boolean` | `true` to lock, `false` to unlock. |

## Example

```lua
local mt = getrawmetatable(game)
setreadonly(mt, false)
-- modify mt here
setreadonly(mt, true)
```
