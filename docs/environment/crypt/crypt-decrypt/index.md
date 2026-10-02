# crypt.decrypt

AES-CBC decryption.

```lua
crypt.decrypt(data: string, key: string, iv: string?): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | Ciphertext bytes. |
| `key` | `string` | Decryption key, matching the encryption key. |
| `iv` | `string?` | Optional 16-byte initialization vector. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Recovered plaintext. |

## Example

```lua
local plain = crypt.decrypt(encrypted, key)
print(plain) -- secret
```
