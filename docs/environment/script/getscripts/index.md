# getscripts

Returns all client-side scripts currently loaded.

```lua
getscripts(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of script instances. |

## Example

```lua
for _, script in ipairs(getscripts()) do
    print(script:GetFullName())
end
```
