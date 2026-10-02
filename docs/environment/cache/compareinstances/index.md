# compareinstances

Checks whether two references point to the same underlying instance.

```lua
compareinstances(a: Instance, b: Instance): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `Instance` | First reference. |
| `b` | `Instance` | Second reference. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when both references are the same object. |

## Example

```lua
local ref = cloneref(workspace)
print(compareinstances(ref, workspace)) -- true
```
