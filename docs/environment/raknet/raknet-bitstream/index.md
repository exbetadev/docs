# raknet.BitStream

Creates an empty bit stream for writing a packet.

```lua
raknet.BitStream.new(): BitStream
```

## Returns

| Type | Description |
| --- | --- |
| `BitStream` | A new stream object. |

## Example

```lua
local stream = raknet.BitStream.new()
stream:WriteU32(12345)
stream:WriteString("hello")

print(stream:GetLength())
```
