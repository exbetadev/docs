# bit.bdiv

32-bit division.

```lua
bit.bdiv(...: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `...` | `number` | Numbers to divide. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Result wrapped to 32 bits, or 0 on divide-by-zero. |

## Example

```lua
print(bit.bdiv(10, 2)) -- 5
```
