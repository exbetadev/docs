# filtergc

Filters garbage-collected objects by type and criteria.

```lua
filtergc(filter: string, args: table, returnOne: boolean?): any
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `filter` | `string` | Object type to filter, such as `"function"` or `"table"`. |
| `args` | `table` | Criteria map; keys depend on the filter. |
| `returnOne` | `boolean?` | Return the first match instead of an array. |

## Returns

| Type | Description |
| --- | --- |
| `any` | Matched object, or an array of matches. |

## Example

```lua
local matches = filtergc("function", {
    Hash = "a1b2c3",
})
print(#matches)
```
