# crypt.lz4compress

LZ4 compression.

```lua
crypt.lz4compress(data: string): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | Bytes to compress. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Compressed bytes. |

## Example

```lua
local compressed = crypt.lz4compress(data)
```
