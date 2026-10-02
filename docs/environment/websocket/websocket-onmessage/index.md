# WebSocket.OnMessage

Fires whenever a message arrives.

```lua
ws.OnMessage:Connect(function(message: string))
```

## Members

| Name | Type | Description |
| --- | --- | --- |
| `message` | `string` | The incoming payload. |

## Example

```lua
ws.OnMessage:Connect(function(message)
    print(message)
end)
```
