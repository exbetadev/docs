# getupvalues

Returns every upvalue of a function.

```lua
getupvalues(fn: function): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The function to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of `{ Name = string, Value = any }`. |

## Example

```lua
local function makeCounter()
    local count = 0
    return function()
        count = count + 1
        return count
    end
end

local counter = makeCounter()
print(getupvalues(counter)[1].Value) -- 0
```
