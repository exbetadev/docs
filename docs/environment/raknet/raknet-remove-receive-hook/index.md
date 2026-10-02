# raknet.remove_receive_hook

Removes a previously added receive hook.

```lua
raknet.remove_receive_hook(callback: function): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `callback` | `function` | The callback returned by `add_receive_hook`. |

## Example

```lua
raknet.remove_receive_hook(hook)
```
