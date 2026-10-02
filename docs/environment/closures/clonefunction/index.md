# clonefunction

Creates an independent copy of a function.

```lua
clonefunction(fn: function): function
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to clone. |

## Returns

| Type | Description |
| --- | --- |
| `function` | A new function with the same behaviour. |

## Example

```lua
local original = function() return 1 end
local clone = clonefunction(original)

print(original == clone) -- false
print(clone())           -- 1
```
