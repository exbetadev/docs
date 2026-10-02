# getactors

Returns every Actor in the current DataModel.

```lua
getactors(): table
```

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of Actor instances. |

## Example

```lua
for _, actor in ipairs(getactors()) do
    print(actor.Name)
end
```
