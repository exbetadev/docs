# getpcd

Returns property change descriptor metadata.

```lua
getpcd(instance: Instance, property: string): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to inspect. |
| `property` | `string` | Property name. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | Descriptor table, or `nil`. |

## Example

```lua
local desc = getpcd(workspace, "Name")
print(desc)
```
