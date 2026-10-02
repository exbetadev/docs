# bit.rshift

Logical right shift, inserting zeros.

```lua
bit.rshift(value: number, count: number): number
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
print(bit.rshift(8, 2)) -- 2
```
