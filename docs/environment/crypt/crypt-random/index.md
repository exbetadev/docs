# crypt.random

Returns a random integer in the range `[min, max]`.

```lua
crypt.random(min: number, max: number): number
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `min` | `number` | Lower bound, inclusive. |
| `max` | `number` | Upper bound, inclusive. |

## Returns

| Type | Description |
| --- | --- |
| `number` | Random integer. |

## Example

```lua
print(crypt.random(1, 100))
```
