# WebSocket.Send

Sends a text message over the socket.

```lua
ws:Send(message: string): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `message` | `string` | The payload to send. |

## Example

```lua
ws:Send("ping")
```
