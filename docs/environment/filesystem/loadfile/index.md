# loadfile

Compiles a workspace file into a function without running it.

```lua
loadfile(path: string): (function?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Returns

| Type | Description |
| --- | --- |
| `function?` | The compiled function. |
| `string?` | Error message when compilation fails. |

## Example

```lua
local fn, err = loadfile("scripts/main.lua")
if fn then
    fn()
end
```
