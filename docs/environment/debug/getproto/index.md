# getproto

Returns one nested prototype of a function.

```lua
getproto(fn: function, index: number): function?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The enclosing function. |
| `index` | `number` | One-based prototype index. |

## Returns

| Type | Description |
| --- | --- |
| `function?` | The nested function, or `nil`. |

## Example

```lua
local inner = getproto(fn, 1)
print(type(inner)) -- function
```
