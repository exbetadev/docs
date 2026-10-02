# isreadonly

Checks whether a table is read-only.

```lua
isreadonly(table: table): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `table` | `table` | The table to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the table is locked. |

## Example

```lua
print(isreadonly(getrawmetatable(game))) -- true
```
