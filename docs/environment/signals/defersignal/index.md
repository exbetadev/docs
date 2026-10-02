# defersignal

Fires a signal at the end of the current scheduler step.

```lua
defersignal(signal: RBXScriptSignal, ...: any): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to trigger. |
| `...` | `any` | Arguments forwarded to each connection. |

## Example

```lua
defersignal(game.Players.PlayerAdded, somePlayer)
```
