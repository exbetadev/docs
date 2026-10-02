# bit.tohex

Converts a number to hex.

```lua
bit.tohex(value: number, length: number?): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `number` | The number to format. |
| `length` | `number?` | Minimum hex digits, default 8. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Hex string. |

## Example

```lua
print(bit.tohex(255)) -- 000000ff
```
