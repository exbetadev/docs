# WebSocket.OnClose

Fires when the connection closes.

```lua
ws.OnClose:Connect(function())
```

## Example

```lua
ws.OnClose:Connect(function()
    print("connection closed")
end)
```
