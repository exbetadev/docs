# getscriptfromthread

Returns the script that owns a coroutine.

```lua
getscriptfromthread(thread: thread): Instance?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `thread` | `thread` | The coroutine to inspect. |

## Returns

| Type | Description |
| --- | --- |
| `Instance?` | The owning script, or `nil`. |

## Example

```lua
local thread = coroutine.running()
local script = getscriptfromthread(thread)
print(script and script.Name)
```
