# raknet.add_send_hook

Registers a callback invoked for every outbound packet.

```lua
raknet.add_send_hook(callback: function): function
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `callback` | `function` | Receives the packet table. |

## Returns

| Type | Description |
| --- | --- |
| `function` | The callback, to be passed when removing it. |

## Example

```lua
local hook = raknet.add_send_hook(function(packet)
    print("sending:", packet.Seq)
end)
```
