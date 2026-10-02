# bit.arshift

Arithmetic right shift, preserving the sign bit.

```lua
bit.arshift(value: number, count: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `number` | Value to shift. |
| `count` | `number` | Bit positions to shift. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Shifted result. |

## Example

```lua
print(bit.arshift(-8, 2)) -- -2
```
