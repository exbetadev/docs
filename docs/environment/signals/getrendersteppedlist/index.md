# getrendersteppedlist

Returns the current list of RenderStepped connections.

```lua
getrendersteppedlist(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of connection tables. |

## Example

```lua
local list = getrendersteppedlist()
print(#list)
```
