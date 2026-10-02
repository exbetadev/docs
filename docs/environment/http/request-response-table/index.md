# request response table

The table returned by `request`.

## Members

| Name | Type | Description |
| --- | --- | --- |
| `Success` | `boolean` | `true` when the status code is in the 2xx range. |
| `StatusCode` | `number` | The HTTP status code. |
| `StatusMessage` | `string` | Human readable status phrase, for example `Not Found`. |
| `Headers` | `table` | Response headers. |
| `Cookies` | `table` | Response cookies. |
| `Body` | `string` | Response body. |

## Example

```lua
local response = request({ Url = "https://example.com" })
print(response.StatusCode) -- 200
```
