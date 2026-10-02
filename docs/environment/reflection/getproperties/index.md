# getproperties

Returns all scriptable and hidden properties.

```lua
getproperties(instance: Instance): table
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
for name, value in pairs(getproperties(workspace)) do
    print(name, value)
end
```
