# bit.lshift

Left shift, inserting zeros.

```lua
bit.lshift(value: number, count: number): number
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
print(bit.lshift(1, 2)) -- 4
```
