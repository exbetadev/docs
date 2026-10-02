# cache.invalidate

Removes an instance from the cache so the next access creates a new reference.

```lua
cache.invalidate(instance: Instance): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The instance to invalidate. |

## Example

```lua
local player = game:GetService("Players").LocalPlayer
cache.invalidate(player)
```
