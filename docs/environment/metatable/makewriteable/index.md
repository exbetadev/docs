# makewriteable

Unlocks a read-only table.

```lua
makewriteable(table: table): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `table` | `table` | The table to unlock. |

## Example

```lua
local mt = getrawmetatable(game)
makewriteable(mt)
print(isreadonly(mt)) -- false
```
