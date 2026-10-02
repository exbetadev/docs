# WebSocket.connect

Opens a WebSocket connection and returns a client object.

```lua
WebSocket.connect(url: string): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `url` | `string` | `ws://` or `wss://` endpoint. |

## Returns

| Type | Description |
| --- | --- |
| `table` | Client with the `OnMessage`, `OnClose`, `Send` and `Close` fields. |

## Example

```lua
local ws = WebSocket.connect("wss://echo.example.com")

ws.OnMessage:Connect(function(message)
    print("received:", message)
end)

ws.OnClose:Connect(function()
    print("closed")
end)

ws:Send("hello")
```
