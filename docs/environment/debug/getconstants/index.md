# getconstants

Returns all constants of a function.

```lua
getconstants(fn: function): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of constants. |

## Example

```lua
local function greet(name)
    return "Hello, " .. name
end

print(getconstants(greet)[1]) -- "Hello, "
```
