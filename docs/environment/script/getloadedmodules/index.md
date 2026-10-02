# getloadedmodules

Returns every ModuleScript that has been required.

```lua
getloadedmodules(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of loaded module instances. |

## Example

```lua
for _, module in ipairs(getloadedmodules()) do
    print(module:GetFullName())
end
```
