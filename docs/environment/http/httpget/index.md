# HttpGet

Performs a GET request and returns the response body.

```lua
HttpGet(url: string): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `url` | `string` | Absolute `http://` or `https://` URL. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Response body, or a message describing the failure. |

## Example

```lua
local body = HttpGet("https://api.example.com/data")
print(body)
```

!!! note "Returns a string"
    On a network error or non-200 status this returns an error string instead of `nil`. Use `request` when you need the status code.
