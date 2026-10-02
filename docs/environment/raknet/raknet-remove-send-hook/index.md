# raknet.remove_send_hook

Removes a previously added send hook.

```lua
raknet.remove_send_hook(callback: function): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `callback` | `function` | The callback returned by `add_send_hook`. |

## Example

```lua
raknet.remove_send_hook(hook)
```
