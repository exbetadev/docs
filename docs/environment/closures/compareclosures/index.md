# compareclosures

Compares two functions for equivalence.

```lua
compareclosures(a: function, b: function): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `a` | `function` | First function. |
| `b` | `function` | Second function. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when both functions are equivalent. |

## Example

```lua
local fn1 = loadstring("return 1")
local fn2 = clonefunction(fn1)
print(compareclosures(fn1, fn2)) -- true
```
