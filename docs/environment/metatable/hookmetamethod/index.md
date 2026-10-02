# hookmetamethod

Hooks a single metamethod on an object and returns the original.

```lua
hookmetamethod(object: any, method: string, hook: function): function
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `object` | `any` | The object whose metatable is hooked. |
| `method` | `string` | Metamethod name, for example `"__index"`. |
| `hook` | `function` | The replacement function. |

## Returns

| Type | Description |
| --- | --- |
| `function` | The original metamethod. |

## Example

```lua
local old
old = hookmetamethod(game, "__namecall", function(self, ...)
    if getnamecallmethod() == "Kick" then
        return
    end
    return old(self, ...)
end)
```
