# raknet.add_receive_hook

Registers a callback invoked for every inbound packet.

```lua
raknet.add_receive_hook(callback: function): function
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
local hook = raknet.add_receive_hook(function(packet)
    print("received:", packet.Id)
end)
```
