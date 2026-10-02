# getconstant

Reads a single constant by index.

```lua
getconstant(fn: function, index: number): any
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to inspect. |
| `index` | `number` | One-based constant index. |

## Returns

| Type | Description |
| --- | --- |
| `any` | The constant value. |

## Example

```lua
print(getconstant(greet, 1)) -- "Hello, "
```
