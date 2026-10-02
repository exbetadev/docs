# makereadonly

Locks a table against writes.

```lua
makereadonly(table: table): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `table` | `table` | The table to lock. |

## Example

```lua
local config = { debug = false }
makereadonly(config)
print(isreadonly(config)) -- true
```
