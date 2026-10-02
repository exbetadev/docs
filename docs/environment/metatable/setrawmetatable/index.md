# setrawmetatable

Replaces an object's metatable, bypassing __metatable protection.

```lua
setrawmetatable(object: any, mt: table?): any
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `any` | The object to modify. |
| `mt` | `table?` | The new metatable, or `nil` to remove it. |

## Returns

| Type | Description |
| --- | --- |
| `any` | The object that was passed in. |

## Example

```lua
local t = setmetatable({}, { __metatable = "locked" })
setrawmetatable(t, { __index = function() return 42 end })
print(t.anything) -- 42
```
