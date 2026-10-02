# checkcaller

Checks whether the current call originates from executor code.

```lua
checkcaller(): boolean
```

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the caller is an executor script. |

## Example

```lua
local function sensitive()
    if not checkcaller() then
        error("Access denied")
    end
    print("Allowed")
end

sensitive() -- Allowed
```
