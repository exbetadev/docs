# Send

Sends the stream as a network packet.

```lua
stream:Send(): boolean
```

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the packet was queued. |

## Example

```lua
local stream = raknet.BitStream.new()
stream:WriteU32(1)
stream:Send()
```
