# getinstances

Returns every instance in the DataModel.

```lua
getinstances(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of all live instances. |

## Example

```lua
for _, inst in ipairs(getinstances()) do
    print(inst:GetFullName())
end
```
