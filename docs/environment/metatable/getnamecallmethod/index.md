# getnamecallmethod

Returns the method name of the active __namecall.

```lua
getnamecallmethod(): string
```

## Returns

| Type | Description |
| --- | --- |
| `string` | The method being called, for example `"Kick"`. |

## Example

```lua
local old
old = hookmetamethod(game, "__namecall", function(self, ...)
    print("Called:", getnamecallmethod())
    return old(self, ...)
end)
```
