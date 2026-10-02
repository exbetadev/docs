# WriteString

Writes a length-prefixed string.

```lua
stream:WriteString(value: string): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `value` | `string` | The string to write. |

## Example

```lua
stream:WriteString("hello")
```
