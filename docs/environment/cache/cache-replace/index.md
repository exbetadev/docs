# cache.replace

Replaces one instance reference with another in the cache.

```lua
cache.replace(old: Instance, new: Instance): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `old` | `Instance` | The instance to replace. |
| `new` | `Instance` | The replacement instance. |

## Example

```lua
local fake = Instance.new("Part")
cache.replace(workspace.Target, fake)
```
