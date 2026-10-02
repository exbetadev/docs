# getconnections

Returns all connections attached to a signal.

```lua
getconnections(signal: RBXScriptSignal): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of connection tables. |

## Example

```lua
local connections = getconnections(game.Players.PlayerAdded)
print(#connections)
```
