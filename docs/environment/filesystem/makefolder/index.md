# makefolder

Creates a folder, including missing parents.

```lua
makefolder(path: string): (nil?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Example

```lua
makefolder("a/b/c")
```
