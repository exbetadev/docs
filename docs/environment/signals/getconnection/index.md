# getconnection

Returns a single connection by index.

```lua
getconnection(signal: RBXScriptSignal, index: number): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to inspect. |
| `index` | `number` | One-based connection index. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | The connection, or `nil`. |

## Example

```lua
local connection = getconnection(game.Players.PlayerAdded, 1)
print(connection)
```
