# iscclosure

Checks whether a value is a C closure.

```lua
iscclosure(value: any): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `any` | The value to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the value is a C closure. |

## Example

```lua
print(iscclosure(print))             -- true
print(iscclosure(function() end))    -- false
```
