# Write

Writes raw bytes into the stream.

```lua
stream:Write(data: string): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `string` | The bytes to append. |

## Example

```lua
stream:Write("\1\2\3")
```
