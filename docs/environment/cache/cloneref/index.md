# cloneref

Creates a new reference to an instance that bypasses reference equality checks.

```lua
cloneref(instance: Instance): Instance
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The instance to clone. |

## Returns

| Type | Description |
| --- | --- |
| `Instance` | A distinct reference to the same object. |

## Example

```lua
local ref = cloneref(workspace)
print(ref == workspace) -- false
print(ref.Name)         -- Workspace
```
