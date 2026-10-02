# getnilinstances

Returns instances with no parent.

```lua
getnilinstances(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of orphaned instances. |

## Example

```lua
for _, inst in ipairs(getnilinstances()) do
    print(inst.Name, inst.ClassName)
end
```
