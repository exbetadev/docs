# getrawmetatable_from_class

Returns the shared metatable for an instance class name.

```lua
getrawmetatable_from_class(className: string): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `className` | `string` | Class name, for example `"Part"`. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | The class metatable, or `nil` when unknown. |

## Example

```lua
local mt = getrawmetatable_from_class("Part")
print(type(mt)) -- table
```
