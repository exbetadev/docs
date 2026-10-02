# create_comm_channel

Creates a cross-thread communication channel.

```lua
create_comm_channel(): (number, table)
```

## Returns

| Type | Description |
| --- | --- |
| `number` | Channel identifier. |
| `table` | Channel handle with an `Event` signal and a `Fire` method. |

## Example

```lua
local id, channel = create_comm_channel()
channel.Event:Connect(function(data)
    print("received", data)
end)
```
