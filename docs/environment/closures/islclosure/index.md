# islclosure

Checks whether a value is a Luau closure.

```lua
islclosure(value: any): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `any` | The value to test. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the value is a Luau closure. |

## Example

```lua
print(islclosure(function() end)) -- true
print(islclosure(print))          -- false
```
