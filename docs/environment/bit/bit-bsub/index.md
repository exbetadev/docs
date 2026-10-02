# bit.bsub

32-bit subtraction.

```lua
bit.bsub(...: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `...` | `number` | Numbers to subtract from the first. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Result wrapped to 32 bits. |

## Example

```lua
print(bit.bsub(50, 10)) -- 40
```
