# get_comm_channel

Retrieves an existing communication channel by identifier.

```lua
get_comm_channel(id: number?): table?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `number?` | Channel identifier, or `nil` for the current channel. |

## Returns

| Type | Description |
| --- | --- |
| `table?` | The channel handle, or `nil`. |

## Example

```lua
local channel = get_comm_channel(id)
```
