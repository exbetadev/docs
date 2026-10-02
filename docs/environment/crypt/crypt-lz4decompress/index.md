# crypt.lz4decompress

LZ4 decompression.

```lua
crypt.lz4decompress(data: string, size: number): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | Compressed bytes. |
| `size` | `number` | Expected decompressed size. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Decompressed bytes. |

## Example

```lua
local original = crypt.lz4decompress(compressed, #data)
```
