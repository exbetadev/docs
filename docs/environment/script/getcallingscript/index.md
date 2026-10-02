# getcallingscript

Returns the script that invoked the current function.

```lua
getcallingscript(): Instance?
```

## Returns

| Type | Description |
| --- | --- |
| `Instance?` | The calling script, or `nil`. |

## Example

```lua
local script = getcallingscript()
print(script and script.Name)
```
