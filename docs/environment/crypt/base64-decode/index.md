# base64_decode

Decodes base64 back to bytes.

```lua
base64_decode(encoded: string): string?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `encoded` | `string` | Base64-encoded string. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | Decoded bytes, or `nil` on failure. |

## Aliases

- `base64.decode`

## Example

```lua
print(base64_decode("aGVsbG8=")) -- hello
```
