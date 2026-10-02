# dofile

Compiles a workspace file and runs it immediately.

```lua
dofile(path: string): (nil?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Example

```lua
dofile("scripts/main.lua")
```
