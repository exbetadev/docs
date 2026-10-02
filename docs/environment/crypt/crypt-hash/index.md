# crypt.hash

Computes a hash of the input data.

```lua
crypt.hash(data: string, algorithm: string): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | Bytes to hash. |
| `algorithm` | `string` | One of `md5`, `sha1`, `sha256`, `sha384`, `sha512`. |

## Returns

| Type | Description |
| --- | --- |
| `string` | The hash in hex. |

## Example

```lua
print(crypt.hash("test", "sha256"))
```
