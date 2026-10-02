# cansignalreplicate

Checks whether a signal can be replicated to the server.

```lua
cansignalreplicate(signal: RBXScriptSignal): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when replication is permitted. |

## Example

```lua
print(cansignalreplicate(game.Players.PlayerAdded))
```
