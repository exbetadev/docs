# queueonteleport

Schedules code to run after the next teleport.

```lua
queueonteleport(code: string): ()
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `code` | `string` | Luau source to execute on arrival. |

## Example

```lua
queueonteleport("print('arrived')")
```
