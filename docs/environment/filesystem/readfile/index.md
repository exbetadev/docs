# readfile

Reads a file from the workspace.

```lua
readfile(path: string): (string?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | File contents, or `nil` on failure. |
| `string?` | Error message when the read fails. |

## Example

```lua
local content, err = readfile("config.json")
if content then
    print(content)
else
    warn(err)
end
```
