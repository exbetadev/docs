# newcclosure

Wraps a Luau function so it reports as a C closure.

```lua
newcclosure(fn: function): function
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `fn` | `function` | The Luau function to wrap. |

## Returns

| Type | Description |
| --- | --- |
| `function` | A C closure that forwards to `fn`. |

## Example

```lua
local protected = newcclosure(function()
    return "secret"
end)

print(iscclosure(protected)) -- true
print(protected())           -- secret
```
