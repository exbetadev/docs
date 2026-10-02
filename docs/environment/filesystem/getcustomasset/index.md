# getcustomasset

Publishes a workspace file and returns a URI the game can load.

```lua
getcustomasset(path: string): (string?, string?)
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Returns

| Type | Description |
| --- | --- |
| `string?` | An `rbxasset://` URI for the published file. |
| `string?` | Error message when publishing fails. |

## Example

```lua
local uri = getcustomasset("assets/image.png")
local asset = game:GetService("InsertService"):LoadLocalAsset(uri)
```
