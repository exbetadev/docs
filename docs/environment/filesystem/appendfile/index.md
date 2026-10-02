# appendfile

Appends data to the end of a file.

```lua
appendfile(path: string, content: string): (nil?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |
| `content` | `string` | Data to append. |

## Example

```lua
appendfile("log.txt", "new line\n")
```
