# bit.bswap

Reverses byte order.

```lua
bit.bswap(value: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `number` | The 32-bit value. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Result with bytes swapped. |

## Example

```lua
print(bit.bswap(0x12345678)) -- 0x78563412
```
