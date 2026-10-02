# bit.ror

Rotates bits right.

```lua
bit.ror(value: number, count: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `number` | Value to rotate. |
| `count` | `number` | Bit positions to rotate. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Rotated result. |

## Example

```lua
print(bit.ror(0x80000000, 1)) -- 0x40000000
```
