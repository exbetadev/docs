# HttpPost

Performs a POST request and returns the response body.

```lua
HttpPost(url: string, body: string?): string
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `url` | `string` | Absolute `http://` or `https://` URL. |
| `body` | `string?` | Optional request body. |

## Returns

| Type | Description |
| --- | --- |
| `string` | Response body, or a message describing the failure. |

## Aliases

- `HttpPostAsync`

## Example

```lua
HttpPost("https://api.example.com/submit", "name=exbeta")
```
