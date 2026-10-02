# getgenv

Returns the persistent executor global environment.

```lua
getgenv(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Shared environment across executor scripts. |

## Example

```lua
getgenv().myState = { count = 0 }
print(getgenv().myState.count)
```
