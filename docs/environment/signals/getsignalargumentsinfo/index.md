# getsignalargumentsinfo

Returns argument metadata for a signal.

```lua
getsignalargumentsinfo(signal: RBXScriptSignal): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Argument descriptors. |

## Example

```lua
local info = getsignalargumentsinfo(game.Players.PlayerAdded)
print(info)
```
