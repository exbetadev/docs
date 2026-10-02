# setconstant

Replaces a constant, which rewrites string and number literals.

```lua
setconstant(fn: function, index: number, value: any): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to modify. |
| `index` | `number` | One-based constant index. |
| `value` | `any` | The replacement value. |

## Example

```lua
setconstant(greet, 1, "Hi, ")
print(greet("world")) -- "Hi, world"
```
