# request

Performs a fully configurable HTTP request.

```lua
request(options: table): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `options.Url` | `string` | Target URL. Required. |
| `options.Method` | `string` | One of `GET`, `HEAD`, `POST`, `PUT`, `DELETE`, `OPTIONS`. |
| `options.Headers` | `table` | Optional map of string headers. `Content-Length` cannot be set. |
| `options.Cookies` | `table` | Optional map of string cookies. |
| `options.Body` | `string` | Optional body. Not allowed for `GET` and `HEAD`. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Response table described below. |

## Example

```lua
local response = request({
    Url = "https://api.example.com/users",
    Method = "POST",
    Headers = {
        ["Content-Type"] = "application/json",
    },
    Body = '{"name":"exbeta"}',
})

if type(response) == "table" then
    print(response.StatusCode, response.StatusMessage)
    print(response.Body)
end
```
