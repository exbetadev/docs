# bit.tobit

Normalizes a number to a signed 32-bit integer.

```lua
bit.tobit(value: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `number` | The number to normalize. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Normalized result. |

## Example

```lua
print(bit.tobit(0xFFFFFFFF)) -- -1
```
