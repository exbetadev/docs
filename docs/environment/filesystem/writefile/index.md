# writefile

Writes a file, creating any missing parent folders.

```lua
writefile(path: string, content: string): (nil?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |
| `content` | `string` | Data to write. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | Error message when the write fails. |

## Example

```lua
writefile("scripts/main.lua", "print('hi')")
```
