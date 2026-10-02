# bit.bmul

32-bit multiplication.

```lua
bit.bmul(...: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `...` | `number` | Numbers to multiply. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Result wrapped to 32 bits. |

## Example

```lua
print(bit.bmul(2, 3)) -- 6
```
