# getstack

Reads a variable from the call stack.

```lua
getstack(level: number, index: number?): (string?, any?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `number` | Stack level, `1` is the direct caller. |
| `index` | `number?` | Optional variable index inside that frame. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | The variable name. |
| `any?` | The variable value. |

## Example

```lua
local name, value = getstack(1, 1)
print(name, value)
```
