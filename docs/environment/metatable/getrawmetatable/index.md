# getrawmetatable

Returns an object's metatable, bypassing __metatable protection.

```lua
getrawmetatable(object: any): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `any` | The object to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | The raw metatable, or `nil` when there is none. |

## Example

```lua
local mt = getrawmetatable(game)
print(type(mt)) -- table
```
