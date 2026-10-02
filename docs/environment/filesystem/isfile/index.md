# isfile

Checks whether a file exists.

```lua
isfile(path: string): boolean
```

## Parameters

| Name | Type | Description |
| --- | --- | --- |
| `path` | `string` | Path relative to the workspace root. |

## Returns

| Type | Description |
| --- | --- |
| `boolean` | `true` when the file exists. |

## Example

```lua
if isfile("config.json") then
    print("exists")
end
```
