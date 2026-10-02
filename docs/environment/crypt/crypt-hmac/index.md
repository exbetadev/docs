# crypt.hmac

Computes an HMAC signature.

```lua
crypt.hmac(data: string, key: string, algorithm: string): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | Message bytes. |
| `key` | `string` | Secret key bytes. |
| `algorithm` | `string` | One of `md5`, `sha1`, `sha256`, `sha384`, `sha512`. |

## Returns

| Type | Description |
| --- | --- |
| `string` | The signature in hex. |

## Example

```lua
local sig = crypt.hmac("message", "secret", "sha256")
```
