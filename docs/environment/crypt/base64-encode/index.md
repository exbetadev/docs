# base64_encode

Encodes binary data to base64.

```lua
base64_encode(data: string): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | The bytes to encode. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Base64 representation. |

## Aliases

- `base64.encode`

## Example

```lua
print(base64_encode("hello")) -- aGVsbG8=
```
