# getgc

Scans the garbage collector for live objects.

```lua
getgc(includeTables: boolean?): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `includeTables` | `boolean?` | Include tables as well as other types. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Array of garbage-collected objects. |

## Example

```lua
for _, value in ipairs(getgc(true)) do
    if typeof(value) == "function" then
        print(value)
    end
end
```
