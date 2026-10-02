# gettenv

Returns the global environment of a thread.

```lua
gettenv(thread: thread): table
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `thread` | `thread` | The coroutine to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `table` | The thread's global environment table. |

## Example

```lua
local co = coroutine.create(function() end)
local env = gettenv(co)
print(type(env)) -- table
```
