# getrunningscripts

Returns scripts that have started execution.

```lua
getrunningscripts(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of running script instances. |

## Example

```lua
for _, script in ipairs(getrunningscripts()) do
    print(script.Name)
end
```
