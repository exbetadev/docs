# crypt.encrypt

AES-CBC encryption.

```lua
crypt.encrypt(data: string, key: string, iv: string?): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | Plaintext bytes. |
| `key` | `string` | Encryption key, 16 or 32 bytes. |
| `iv` | `string?` | Optional 16-byte initialization vector. |

## Returns

| Type | Description |
| --- | --- |
| `string` | The ciphertext. |

## Example

```lua
local key = crypt.generatekey()
local encrypted = crypt.encrypt("secret", key)
```
