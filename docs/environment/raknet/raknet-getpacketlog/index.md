# raknet.getpacketlog

Returns the captured packet log.

```lua
raknet.getpacketlog(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of packet tables. |

## Example

```lua
for _, packet in ipairs(raknet.getpacketlog()) do
    print(packet.Seq, packet.Size, packet.Summary)
end
```
