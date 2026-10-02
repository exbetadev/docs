# gethiddenproperties

Returns all hidden properties of an instance.

```lua
gethiddenproperties(instance: Instance): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `instance` | `Instance` | The object to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Map of property names to values. |

## Example

```lua
local props = gethiddenproperties(workspace)
for name, value in pairs(props) do
    print(name, value)
end
```
