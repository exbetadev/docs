# firesignal

Fires all connections attached to a signal.

```lua
firesignal(signal: RBXScriptSignal, ...: any): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to trigger. |
| `...` | `any` | Arguments forwarded to each connection. |

## Example

```lua
firesignal(game.Players.PlayerAdded, somePlayer)
```
