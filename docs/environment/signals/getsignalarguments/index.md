# getsignalarguments

Returns the argument list of a signal.

```lua
getsignalarguments(signal: RBXScriptSignal): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `signal` | `RBXScriptSignal` | The signal to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of argument descriptors. |

## Example

```lua
local args = getsignalarguments(game.Players.PlayerAdded)
print(#args)
```
