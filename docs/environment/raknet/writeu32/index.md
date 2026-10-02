# WriteU32

Writes an unsigned 32-bit value.

```lua
stream:WriteU32(value: number): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `number` | The number to encode. |

## Example

```lua
stream:WriteU32(70000)
```
