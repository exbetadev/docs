# crypt.generatebytes

Generates random bytes.

```lua
crypt.generatebytes(size: number): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `size` | `number` | Number of bytes to generate. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Random bytes. |

## Example

```lua
local iv = crypt.generatebytes(16)
```
