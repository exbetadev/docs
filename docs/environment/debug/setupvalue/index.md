# setupvalue

Writes a single upvalue by index.

```lua
setupvalue(fn: function, index: number, value: any): string?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to modify. |
| `index` | `number` | One-based upvalue index. |
| `value` | `any` | The new value. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | The upvalue name that was changed. |

## Example

```lua
setupvalue(counter, 1, 100)
print(counter()) -- 101
```
