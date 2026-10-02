# getinfo

Returns debug information for a function or stack level.

```lua
getinfo(target: number | function, options: string?): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `number or function` | A function, or a stack level number. |
| `options` | `string?` | Any subset of `n`, `s`, `l`, `u`, `a`, `f`. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Table with `name`, `source`, `currentline`, `nups`, `numparams`. |

## Example

```lua
local info = getinfo(1, "nsl")
print(info.name, info.currentline)
```
