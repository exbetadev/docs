# oth.unhook

Removes a hook previously installed with `oth.hook`.

```lua
oth.unhook(fn: function): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The hooked function to restore. |

## Example

```lua
oth.unhook(old)
```
