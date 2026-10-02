# bit.badd

32-bit addition.

```lua
bit.badd(...: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `...` | `number` | Numbers to add. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Result wrapped to 32 bits. |

## Example

```lua
print(bit.badd(10, 20)) -- 30
```
