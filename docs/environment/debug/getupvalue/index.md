# getupvalue

Reads a single upvalue by index.

```lua
getupvalue(fn: function, index: number): (string?, any?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to inspect. |
| `index` | `number` | One-based upvalue index. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | The upvalue name. |
| `any?` | The upvalue value. |

## Example

```lua
local name, value = getupvalue(counter, 1)
print(name, value) -- count, 0
```
