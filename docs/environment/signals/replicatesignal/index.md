# replicatesignal

Fires a signal and replicates the result to the server.

```lua
replicatesignal(signal: RBXScriptSignal, ...: any): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to trigger. |
| `...` | `any` | Arguments forwarded to each connection. |

## Example

```lua
replicatesignal(game.Players.PlayerAdded, somePlayer)
```
