# loadstring

Compiles Luau source into a callable function.

```lua
loadstring(source: string, chunkname: string?): (function?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `source` | `string` | Luau source code to compile. |
| `chunkname` | `string?` | Optional chunk name used in error messages. |

## Returns

| Type | Description |
| --- | --- |
| `function?` | The compiled function on success. |
| `string?` | Error message when compilation fails. |

## Example

```lua
local fn, err = loadstring("print('Hello')")
if fn then
    fn()
else
    warn("Compilation error:", err)
end
```
