# setstack

Overwrites a variable in the call stack.

```lua
setstack(level: number, index: number, value: any): string?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `level` | `number` | Stack level to modify. |
| `index` | `number` | Variable index inside that frame. |
| `value` | `any` | The replacement value. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | The variable name that was changed. |

## Example

```lua
setstack(1, 1, 42)
```
