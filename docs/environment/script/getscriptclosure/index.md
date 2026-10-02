# getscriptclosure

Returns a callable closure for a script's body.

```lua
getscriptclosure(script: Instance): function?
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `script` | `Instance` | The script to wrap. |

## Returns

| Type | Description |
| --- | --- |
| `function?` | The closure, or `nil` when unavailable. |

## Example

```lua
local closure = getscriptclosure(script)
if closure then
    closure()
end
```
